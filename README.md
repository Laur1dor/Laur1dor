<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3c72,100:2a5298&height=280&section=header&text=Laur1dor&fontSize=50&fontColor=ffffff&animation=fadeIn&desc=DevOps%20Engineer%20%7C%20Infrastructure%20and%20Automation%20%7C%20Aspiring%20SRE&textAlignY=30&descAlignY=52&descSize=17&v=4" width="100%"/>

</div>

<div align="center">

<a href="https://t.me/Laur1dor"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/></a>

</div>

### About

Infrastructure and automation engineer, moving toward SRE. I design, containerize, and operate self-managed systems end-to-end — virtualization, networking, storage/backup, monitoring and security.

- Designing reverse-proxy / multi-exit network routing with failover
- Running virtualization and backup on Proxmox VE + Proxmox Backup Server (ZFS RAID, S3-backed storage)

---

### Tech Stack

<img src="https://skillicons.dev/icons?i=linux,docker,ansible,terraform,bash,python,rust,cpp,git,github,githubactions,gitlab,nginx,grafana,prometheus,vscode" />

| Category | Tools |
|---|---|
| **Languages** | Python, Rust, Bash, C++ |
| **Virtualization & Backup** | Proxmox VE, Proxmox Backup Server, ZFS RAID, Garage S3 storage |
| **Containers** | Docker, Docker Compose, Portainer |
| **IaC / Config Management** | Ansible, Terraform |
| **Reverse Proxy** | Traefik, Nginx Proxy Manager, Nginx |
| **Networking / VPN** | Xray, VLESS, SOCKS5, WebSocket Proxying, OpenWrt |
| **Observability** | Prometheus, Grafana, Grafana Alloy, Loki, Promtail, OpenTelemetry, InfluxDB, Telegraf, Elasticsearch, OpenSearch |
| **Security** | CrowdSec, Gotify, Vaultwarden |
| **Telegram Bots** | Media Downloader Bot, Profile Auto-Updater Bot |
| **Messenger Infra** | Matrix Server Deployment, Cross-Messenger Bridges |
| **AI/LLM** | Matrix AI Assistant (photo recognition, translation), Custom LLM Gateway, AI Agent Configuration |
| **CI/CD** | Git, GitHub, GitHub Actions, GitLab |

---

### Courses

| Course | Status | Started | Completed |
|---|---|---|---|
| [Stepik — Course 1547](https://stepik.org/course/1547/) | ✅ Completed | March 2024 | April 16, 2024 |

---

### Projects

**[Matrix-Docker-Ansible-Xray](https://github.com/Laur1dor/Matrix-Docker-Ansible-Xray)** — Turnkey family/team Matrix messenger built on spantaleev/matrix-docker-ansible-deploy: calls & video (Element Call + LiveKit), guest conferences, AI assistant with photo recognition, translator, 6 cross-messenger bridges, moderation, helpdesk, optional Xray (VLESS/REALITY) censorship bypass. Deploys on a single VPS, a home Proxmox box, or behind an existing reverse proxy.

**[tg-ws-proxy-router](https://github.com/Laur1dor/tg-ws-proxy-router)** — Fork of Flowseal/tg-ws-proxy: keeps the original MTProto-over-Cloudflare-WebSocket bridge (TLS ClientHello fragmentation for DPI bypass), adds a SOCKS5 ingress carrying both data and calls, a routing engine for multi-exit failover, dual MTProto entry points (plain + Fake TLS), and an interactive TUI panel for headless server deployment.

**[crowdsec-gotify-aggregator](https://github.com/Laur1dor/crowdsec-gotify-aggregator)** — Rust HTTP relay between CrowdSec and Gotify: groups alerts by source IP within a sliding window and sends one consolidated Gotify notification instead of one per triggered scenario.

**[all-downloader](https://github.com/Laur1dor/all-downloader)** — Self-hosted Telegram bot downloading video/audio/photo posts in max quality via its own Bot API server (files up to 2GB), routes blocked platforms through a VLESS proxy to bypass DPI restrictions.

**[ytm-nd](https://github.com/Laur1dor/ytm-nd)** — Syncs a public YouTube Music playlist into a Navidrome library on a schedule: full playlist listing via YouTube Data API v3, cookie-less audio downloads via yt-dlp's android_vr client, age-restricted tracks handled via yt-dlp-ejs + deno, packaged into one album with tags/cover and delivered as files plus an .m3u playlist.

**[Telegram-Profile-AutoUpdate](https://github.com/Laur1dor/Telegram-Profile-AutoUpdate)** — Pyrogram script that updates a Telegram account's name and bio every 60 seconds with live data: multi-timezone clock, crypto rates (CoinGecko), RUB exchange rates (CBR), with FloodWait/error handling.

**[Extenguished-Destinies](https://github.com/Laur1dor/Extenguished-Destinies)** — Text-based Dark Souls-style adventure in C++17: dungeon exploration, NPCs, inventory and leveling, bonfire-style checkpoints, save/load. In active development.
