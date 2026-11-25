# Sumidoku

**Self-hosted manga server** — Aidoku WASM and OPDS sources, a REST API, and an embedded web UI, shipped as a single binary or a Docker image, with an official Android client for phones and tablets.

[Website](https://sumidoku.github.io) · [Documentation](https://sumidoku.github.io/docs/intro/) · [Releases](https://github.com/Sumidoku/Sumidoku/releases) · [Android app](https://github.com/Sumidoku/Sumidoku-android/releases)

## Repositories

| Repository | What it is |
| --- | --- |
| [Sumidoku](https://github.com/Sumidoku/Sumidoku) | The manga server: Rust backend, embedded web UI, Aidoku WASM source runtime, OPDS catalogs, library and reading management, chapter downloads, backups and imports from Aidoku/Suwayomi. |
| [Sumidoku-android](https://github.com/Sumidoku/Sumidoku-android) | The official Android client: Kotlin and Jetpack Compose, native offline reading, background downloads and update checks, driving the same server REST API. |
| [Sumidoku.github.io](https://github.com/Sumidoku/Sumidoku.github.io) | The project site and documentation hub. |
| [oauth](https://github.com/Sumidoku/oauth) | OAuth callback relay used by Sumidoku's tracker integrations. Internal component — nothing to install on its own. |

## Contributing

Issues and pull requests are welcome on the [main repository](https://github.com/Sumidoku/Sumidoku). The project is built and maintained by agent sessions — [AGENTS.md](https://github.com/Sumidoku/Sumidoku/blob/main/AGENTS.md) is the entry point for how that works, and [docs/contributors.md](https://github.com/Sumidoku/Sumidoku/blob/main/docs/contributors.md) describes how community PRs are triaged and reviewed.

## License

[MIT](https://github.com/Sumidoku/Sumidoku/blob/main/LICENSE)
