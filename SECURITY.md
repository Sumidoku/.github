# Security Policy

## Reporting a vulnerability

Please report security vulnerabilities through GitHub's private vulnerability
reporting on the affected repository (**Security → Advisories → Report a
vulnerability**). Do not open a public issue for an unfixed vulnerability.

This is a small project without a formal response SLA, but reports are read
and triaged. Fixes ship in the next release and are called out in the release
notes once public.

## Scope and threat model

Sumidoku is a self-hosted server that stores your library database, source
packages, and (optionally) tracker and OPDS credentials. Keep these in mind
when deploying:

- Authentication is off by default. If the instance is reachable by anyone
  but you, set an admin password — see
  [docs/authentication.md](https://github.com/Sumidoku/Sumidoku/blob/main/docs/authentication.md).
- Do not expose the port directly to the internet without authentication and
  TLS termination in front of it.
- Source packages are third-party WASM/JavaScript executed by the server;
  install sources only from repositories you trust.
