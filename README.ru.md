### Обо мне

Инженер по инфраструктуре и автоматизации, двигаюсь в сторону SRE. Проектирую, контейнеризирую и веду self-managed системы полным циклом: провижининг, config management, reverse-proxy/сетевые слои, security-мониторинг, алертинг, хранилища.

- Автоматизация деплоя через Ansible + Docker Compose
- Проектирование reverse-proxy / сетевых слоёв маршрутизации с failover
- Пайплайны security-мониторинг → алертинг
- Инфра-тулинг на Python, Rust, Bash
- Сейчас учу: Kubernetes, Terraform, Prometheus/Grafana

### Стек

- **Языки**: Python, Rust, Bash/Shell, C++, JavaScript, Batch (винда)
- **Контейнеры**: Docker, Docker Compose, multi-stage Dockerfile, Portainer
- **Config Management/IaC**: Ansible (полные плейбуки деплоя сервисов)
- **Reverse proxy/сеть**: Traefik, Nginx Proxy Manager, Xray, VLESS, SOCKS5, WebSocket-проксирование, failover-роутинг с несколькими выходами
- **Security/мониторинг**: CrowdSec, Gotify (свой сервис агрегации алертов), diun (слежка за обновлениями образов)
- **Хранилища/секреты**: ZFS, Garage (S3-совместимое хранилище), Vaultwarden
- **Мессенджеры/боты**: Telegram Bot API, деплой Matrix-сервера, плагины maubot
- **AI/LLM**: свой LLM-gateway сервис
- **Тесты**: pytest-сьюты в паре проектов
- **Git/CI**: GitHub Actions

### Проекты

**homelab** — self-hosted инфра-стек: reverse proxy, оркестрация контейнеров, секреты, S3-хранилище, ZFS, чат/медиа-сервисы, автослежка за обновлениями образов.

**Matrix-Docker-Ansible-Xray** — Ansible-деплой Matrix-сервера с Xray-роутингом, чат-бот плагинами и LLM gateway.

**crowdsec-gotify-aggregator** — сервис на Rust, дедуп и агрегация security-алертов CrowdSec в одно уведомление Gotify.

**tg-ws-proxy-router** — прокси-роутер (SOCKS5+WebSocket) с failover на несколько выходов, TUI-панель, кросс-платформенные деплой-скрипты.

**all-downloader** — self-hosted Telegram-бот, multi-stage Docker сборки, VLESS-роутинг.

**ytm-nd** — контейнеризированный sync-сервис с автоматизацией через entrypoint.

---

Это русская версия для чтения. В самом профиле на GitHub стоит английская (README.md), эта — README.ru.md, лежит рядом в репо.
