# Proxy (Caddy)

Reverse proxy gateway for multiple Docker apps on a single server.

## Setup
1) Copy `.env.example` to `.env` and adjust domains
2) `docker compose up -d`

## Structure
- `docker-compose.yml`: runs the proxy container
- `caddy/Caddyfile`: routing rules
