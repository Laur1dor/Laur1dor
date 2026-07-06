### Обо мне

Инженер по инфраструктуре и автоматизации, двигаюсь в сторону SRE. Проектирую, контейнеризирую и веду self-managed системы полным циклом — виртуализация, сеть, хранилища/бэкапы, мониторинг и безопасность.

- Проектирование reverse-proxy / сетевой маршрутизации с несколькими выходами и failover
- Виртуализация и бэкапы на Proxmox VE + Proxmox Backup Server (ZFS RAID, S3-хранилище)

### Стек

- **Языки**: Python, Rust, Bash, C++
- **Виртуализация и бэкапы**: Proxmox VE, Proxmox Backup Server, ZFS RAID, Garage S3
- **Контейнеры**: Docker, Docker Compose, Portainer
- **IaC / Config Management**: Ansible, Terraform
- **Reverse Proxy**: Traefik, Nginx Proxy Manager, Nginx
- **Сеть / VPN**: Xray, VLESS, SOCKS5, WebSocket-проксирование, OpenWrt
- **Observability**: Prometheus, Grafana, Grafana Alloy, Loki, Promtail, OpenTelemetry, InfluxDB, Telegraf, Elasticsearch, OpenSearch
- **Security**: CrowdSec, Gotify, Vaultwarden
- **Telegram-боты**: бот-загрузчик медиа, бот авто-обновления профиля
- **Мессенджер-инфра**: деплой Matrix-сервера, мосты в другие мессенджеры
- **AI/LLM**: AI-ассистент в Matrix (распознавание фото, перевод), свой LLM gateway, настройка AI-агентов
- **CI/CD**: Git, GitHub, GitHub Actions, GitLab

### Курсы

| Курс | Статус | Начало | Завершение |
|---|---|---|---|
| [Stepik — курс 1547](https://stepik.org/course/1547/) | ✅ Пройден | Март 2024 | 16 апреля 2024 |

### Проекты

**Matrix-Docker-Ansible-Xray** — готовый семейный/командный Matrix-мессенджер на базе spantaleev/matrix-docker-ansible-deploy: звонки/видео (Element Call + LiveKit), гостевые конференции, AI-ассистент с распознаванием фото, переводчик, 6 мостов в другие мессенджеры, модерация, хелпдеск, опциональный обход блокировок через Xray (VLESS/REALITY). Разворачивается на одном VPS, домашнем Proxmox или за существующим reverse-proxy.

**tg-ws-proxy-router** — форк Flowseal/tg-ws-proxy: сохраняет оригинальный MTProto-мост через Cloudflare WebSocket (фрагментация TLS ClientHello для обхода DPI), добавляет SOCKS5-вход (тянет и данные, и звонки), движок маршрутизации для failover на несколько выходов, два MTProto-входа (обычный + Fake TLS) и интерактивную TUI-панель для headless-запуска на сервере.

**crowdsec-gotify-aggregator** — HTTP-релей на Rust между CrowdSec и Gotify: группирует алерты по IP в скользящем окне и шлёт одно сводное уведомление вместо отдельного на каждый сработавший сценарий.

**all-downloader** — self-hosted Telegram-бот, скачивает видео/аудио/фото-посты в макс. качестве через свой Bot API сервер (файлы до 2 ГБ), уводит заблокированные платформы через VLESS-прокси в обход DPI.

**ytm-nd** — синхронизирует публичный плейлист YouTube Music в библиотеку Navidrome по расписанию: полный список треков через YouTube Data API v3, скачивание без cookies через yt-dlp клиент android_vr, возрастные треки — через yt-dlp-ejs + deno, всё собирается в один альбом с тегами/обложкой и отдаётся файлами плюс .m3u плейлистом.

**Telegram-Profile-AutoUpdate** — скрипт на Pyrogram, обновляет имя и био Telegram-аккаунта каждые 60 секунд: время в разных городах, курсы крипты (CoinGecko), курсы валют ЦБ РФ, обработка FloodWait/ошибок.

**Extenguished-Destinies** — текстовое приключение в стиле Dark Souls на C++17: подземелья, NPC, инвентарь и прокачка, костры-чекпоинты, сохранение/загрузка. В разработке.

---

Это русская версия для чтения. В самом профиле на GitHub — английская (README.md), эта лежит рядом файлом README.ru.md.
