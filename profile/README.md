# bogocat

A small software-and-homelab org. We build practical software — dashboards, content pipelines, RPG tools, infrastructure automation — on a self-hosted stack. Most of our work is private; a few projects are open-sourced under MIT.

## Open source

| Project | What it is |
|---|---|
| [tms](https://github.com/bogocat/tms) | Tmux session manager + GitHub-issue agent dispatch. Browse sessions with `tms`, dispatch an agent on an issue with `tmq <repo> <issue>`. Small, dependency-light. |
| [FrameCache](https://github.com/bogocat/framecache) | Offline-first Android photo frame for [Immich](https://immich.app). Caches photos locally so WiFi drops are invisible. |
|[jellyfin-3ds](https://github.com/bogocat/jellyfin-3ds) | The first native Jellyfin client for Nintendo 3DS |


## What we work on

A high-level look at the private side, for context:

- **Homelab platform** — 3-node k3s on Proxmox, ArgoCD GitOps, ~30 deployed apps, monitoring and backups wired end-to-end.
- **Content intelligence** — multi-pass LLM pipelines that distill books, news, and video into a unified entity graph (claims, quotes, entities, predictions).
- **RPG tooling** — a solo TTRPG companion pairing an AI Dungeon Master with Obsidian-compatible markdown vaults.
- **AI-assisted engineering** — most of our coding runs through AI agents; we ship the workflow tools we use.

## Reach

- GitHub: [@jakecelentano](https://github.com/jakecelentano)
- Issues, PRs, and feature requests are best filed on the specific repo.
