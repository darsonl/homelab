My Homelab Setup:

* OS： Debian Server
* Container: Docker + Docker Compose
* Network Setup: Via DDNS and cronjob IP update to bind dynamic IP
* 配合路由器或 Linux 排程任務（cron job）定期更新 IP
* Reverse Proxy for hosting multiple services: Nginx Proxy Manager（NPM）
* Services (in containers): Immich, Plex, Portainer
* Scheduled automated backup: Via cron job
