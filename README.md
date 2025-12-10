# Traefik

Ce dépôt contient une configuration minimale pour démarrer Traefik avec Docker Compose.

## Contenu

- `compose.yaml` : fichier Docker Compose principal.
- `docker/traefik/traefik.toml` : configuration Traefik.

## Prérequis

- Docker (version récente)
- Le plugin Docker Compose (`docker compose`) ou `docker-compose`

## Configuration

La configuration Traefik se trouve dans `docker/traefik/traefik.toml`. Adaptez-la selon vos besoins (entrées, certificates, dashboard, providers, etc.).
