### Обо мне

DevOps / SRE инженер. Проектирую, контейнеризирую и веду self-managed системы полным циклом — виртуализация, сеть, хранилища/бэкапы, мониторинг и безопасность.

### Стек

- **Языки**: Python, Rust, Bash, C++
- **Cloud**: AWS (EC2, S3, биллинг), Google Cloud (Compute Engine, биллинг)
- **Виртуализация и бэкапы**: Proxmox VE, Proxmox Backup Server, rclone, ZFS RAID, Garage S3, AWS S3
- **Контейнеры**: Docker, Docker Compose, LXC
- **IaC / Config Management**: Ansible, Terraform
- **Reverse Proxy**: Traefik, Nginx, Nginx Proxy Manager, Apache
- **Network Engineering**: WireGuard, AmneziaWG, Xray, VLESS, REALITY, Hysteria2, SOCKS5, WebSocket-проксирование, администрирование OpenWrt
- **Observability**: Prometheus, Grafana, Grafana Alloy, Loki, Promtail, OpenTelemetry, InfluxDB, Telegraf, Elasticsearch, OpenSearch
- **Security**: CrowdSec, nftables/iptables, UFW, Fail2ban, Cloudflare, Authelia/Authentik
- **Telegram-боты**: бот-загрузчик медиа (all-downloader), бот авто-обновления профиля (Telegram-Profile-AutoUpdate)
- **Мессенджер-инфра**: деплой Matrix-сервера (звонки Element Call/LiveKit, гостевые конференции, модерация, хелпдеск), 6 мостов в другие мессенджеры
- **AI/LLM**: динамический роутинг моделей (свап по задаче и по исчерпанию токенов), настройка AI-агентов через MCP, настройка RAG
- **CI/CD**: Git, GitHub, GitHub Actions, GitLab

### Курсы

| Курс | Статус | Начало | Завершение |
|---|---|---|---|
| [Stepik — курс 1547](https://stepik.org/course/1547/) | ✅ Пройден | Март 2024 | 16 апреля 2024 |

### Проекты

| Проект | Описание | Статус |
|---|---|---|
| Matrix-Docker-Ansible-Xray | Готовый семейный/командный Matrix-мессенджер на базе spantaleev/matrix-docker-ansible-deploy: звонки/видео (Element Call + LiveKit), гостевые конференции, AI-ассистент с распознаванием фото, переводчик, 6 мостов в другие мессенджеры, модерация, хелпдеск, опциональный обход блокировок через Xray (VLESS/REALITY). | Активен |
| tg-ws-proxy-router | Форк Flowseal/tg-ws-proxy: сохраняет оригинальный MTProto-мост через Cloudflare WebSocket, добавляет SOCKS5-вход (данные + звонки), движок маршрутизации с failover на несколько выходов, два MTProto-входа (обычный + Fake TLS), интерактивную TUI-панель для headless-запуска. | Активен |
| crowdsec-gotify-aggregator | HTTP-релей на Rust между CrowdSec и Gotify: группирует алерты по IP в скользящем окне, шлёт одно сводное уведомление вместо отдельного на каждый сценарий. | Активен |
| all-downloader | Self-hosted Telegram-бот, скачивает видео/аудио/фото в макс. качестве через свой Bot API сервер (файлы до 2 ГБ), уводит заблокированные платформы через VLESS-прокси в обход DPI. | Активен |
| ytm-nd | Синхронизирует публичный плейлист YouTube Music в Navidrome по расписанию: полный список треков через YouTube Data API v3, скачивание без cookies через yt-dlp (android_vr), возрастные треки — через yt-dlp-ejs + deno, всё в один альбом, отдаётся файлами и .m3u плейлистом. | Активен |
| Telegram-Profile-AutoUpdate | Скрипт на Pyrogram, обновляет имя и био Telegram-аккаунта каждые 60 секунд: время в городах, курсы крипты, курсы валют, обработка FloodWait/ошибок. | Активен |
| Extenguished-Destinies | Текстовое приключение в стиле Dark Souls на C++17: подземелья, NPC, инвентарь и прокачка, костры-чекпоинты, сохранение/загрузка. | Заброшен |

---

Это русская версия для чтения. В самом профиле на GitHub — английская (README.md), эта лежит рядом файлом README.ru.md.
