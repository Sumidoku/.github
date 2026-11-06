# Sumidoku

**Self-hosted manga server** — Aidoku WASM and OPDS sources, a REST API, and an embedded web UI, shipped as a single binary or a Docker image.

[Website](https://sumidoku.github.io) · [Documentation](https://sumidoku.github.io/docs/intro/) · [Releases](https://github.com/Sumidoku/Sumidoku/releases)

![The Sumidoku library view](https://raw.githubusercontent.com/Sumidoku/Sumidoku/main/docs/images/library.png)

## Repositories

| Repository | What it is |
| --- | --- |
| [Sumidoku](https://github.com/Sumidoku/Sumidoku) | The manga server: Rust backend, embedded web UI, Aidoku WASM source runtime, OPDS catalogs, library and reading management, chapter downloads, backups and imports from Aidoku/Suwayomi. |
| [Sumidoku.github.io](https://github.com/Sumidoku/Sumidoku.github.io) | The project site and documentation hub. |
| [oauth](https://github.com/Sumidoku/oauth) | OAuth callback relay used by Sumidoku's tracker integrations. Internal component — nothing to install on its own. |

## Get started

```sh
docker compose up -d
```

Then open http://localhost:3000. A portable Windows app is also available on the [latest release](https://github.com/Sumidoku/Sumidoku/releases/latest). See the [installation guide](https://sumidoku.github.io/docs/installation/) for all options.

## Contributing

Issues and pull requests are welcome on the [main repository](https://github.com/Sumidoku/Sumidoku). The project is built and maintained by agent sessions — [AGENTS.md](https://github.com/Sumidoku/Sumidoku/blob/main/AGENTS.md) is the entry point for how that works, and [docs/contributors.md](https://github.com/Sumidoku/Sumidoku/blob/main/docs/contributors.md) describes how community PRs are triaged and reviewed.

## License

[MIT](https://github.com/Sumidoku/Sumidoku/blob/main/LICENSE)
