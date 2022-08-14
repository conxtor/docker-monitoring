# Docker monitoring
Not so simple monitoring stack for Docker, without Swarm. Prometheus, node-exporter, Cadvisor and Grafana. Also monitors Traefik proxy. Work in progress

## TL;DR

1. Have https://github.com/conxtor/traefik-letsencrypt-portainerCE-docker-setup/ deployed on your server
2. Clone this repo
3. `cd` into it
4. Copy .env_sample to .env
5. Edit .env file and fill in your values
6. Create directories /data/grafana/lib, /data/grafana/log, /data/prometheus/config and /data/prometheus/db on your host
7. `chmod -R 777 /data/grafana /data/prometheus`
7. Run `docker compose up -d` (Docker Compose v2 as Docker plugin) or `docker-compose up -d` (older Docker Compose version written in Python)

