# Contributing

Issues and pull requests are welcome.

The entry point is the main repository:
[Sumidoku/Sumidoku](https://github.com/Sumidoku/Sumidoku).

- [AGENTS.md](https://github.com/Sumidoku/Sumidoku/blob/main/AGENTS.md) —
  how the project is built and maintained, the documents that are binding,
  and the verification commands every change must pass.
- [docs/contributors.md](https://github.com/Sumidoku/Sumidoku/blob/main/docs/contributors.md) —
  how community issues and PRs are triaged and reviewed.
- [docs/code-standards.md](https://github.com/Sumidoku/Sumidoku/blob/main/docs/code-standards.md) —
  test, commit, merge and release rules.

A few things worth knowing before opening a PR:

- Run the checks locally first: `cargo nextest run --workspace`,
  `cargo clippy --workspace --all-targets -- -D warnings`, and
  `cd webui && npm ci && npm run check && npm run build` for web UI changes.
- Database schema changes are new numbered migration files only; never edit
  an applied migration.
- Public writing (docs, issue and PR text) describes mechanisms and numbers
  only — no local machine details and no personal attribution.
