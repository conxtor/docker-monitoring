# docker-monitoring
Not so simple monitoring stack for Docker, without Swarm. Prometheus, node-exporter, Cadvisor and Grafana. Also monitors Traefik proxy. Work in progress

## TL;DR

1. Clone this repo
2. `cd` into it
2. Copy .env_sample to .env
3. Edit .env file and fill in your values
4. run `docker compose up -d` (Docker Compose v2 as Docker plugin) or `docker-compose up -d` (older Docker Compose version written in Python)

