# WormholeSystems

Wormhole mapping and collaboration platform for EVE Online — live at [wormhole.systems](https://wormhole.systems/). Real-time chain maps, signature tracking, smart routing and killmail intelligence for corporations and alliances living in wormhole space.

## Repositories at a glance

| Repository | What it is | Status |
|---|---|---|
| [WormholeSystems](https://github.com/WormholeSystems/WormholeSystems) | The application — Laravel 12, Inertia.js, Vue 3 | [![tests](https://github.com/WormholeSystems/WormholeSystems/actions/workflows/tests.yml/badge.svg)](https://github.com/WormholeSystems/WormholeSystems/actions/workflows/tests.yml) [![linter](https://github.com/WormholeSystems/WormholeSystems/actions/workflows/lint.yml/badge.svg)](https://github.com/WormholeSystems/WormholeSystems/actions/workflows/lint.yml) [![last commit](https://img.shields.io/github/last-commit/WormholeSystems/WormholeSystems)](https://github.com/WormholeSystems/WormholeSystems/commits) |
| [wormholesystems-containers](https://github.com/WormholeSystems/wormholesystems-containers) | Production docker stack for self-hosting | [![submodules](https://github.com/WormholeSystems/wormholesystems-containers/actions/workflows/update.yml/badge.svg)](https://github.com/WormholeSystems/wormholesystems-containers/actions/workflows/update.yml) [![last commit](https://img.shields.io/github/last-commit/WormholeSystems/wormholesystems-containers)](https://github.com/WormholeSystems/wormholesystems-containers/commits) |
| [wormholesystems-cli](https://github.com/WormholeSystems/wormholesystems-cli) | `wsctl` — setup wizard and management tool | [![CI](https://github.com/WormholeSystems/wormholesystems-cli/actions/workflows/ci.yml/badge.svg)](https://github.com/WormholeSystems/wormholesystems-cli/actions/workflows/ci.yml) [![release](https://img.shields.io/github/v/release/WormholeSystems/wormholesystems-cli)](https://github.com/WormholeSystems/wormholesystems-cli/releases/latest) |

**How it fits together:** [WormholeSystems](https://github.com/WormholeSystems/WormholeSystems) is the application itself. [wormholesystems-containers](https://github.com/WormholeSystems/wormholesystems-containers) packages it as a production docker stack (Traefik with automatic SSL, frankenPHP, MySQL, Redis, Reverb). [wsctl](https://github.com/WormholeSystems/wormholesystems-cli) sets that stack up interactively and keeps its EVE data updated.

## Run your own instance

```bash
curl --proto '=https' --tlsv1.2 -sSf https://install.wormhole.systems | sh
```

One command installs `wsctl` and walks you through the whole setup — domains, EVE credentials, secrets, SSL, database. See the [container stack README](https://github.com/WormholeSystems/wormholesystems-containers#readme) for details and requirements.

## Features

- **Interactive maps** — real-time wormhole mapping with drag-and-drop chain visualization
- **Collaborative mapping** — live collaboration for corporations and alliances
- **Signature tracking** — centralized wormhole signature management
- **Smart routing** — pathfinding through chains with mass calculations
- **Activity monitoring & intel** — killmail feeds, automated notes and insights per system
- **Access control** — permission management down to character level

## Community & contact

- **Discord**: [Join our Discord](https://discord.gg/rpfWCzVJS7)
- **Email**: [nicolaskion07@gmail.com](mailto:nicolaskion07@gmail.com)
- **Developer**: [NicolasKion](https://github.com/NicolasKion) — [nicolaskion.dev](https://nicolaskion.dev)

Contributions are welcome — bug reports, feature suggestions and pull requests alike.

## License

MIT — see the individual repositories.
