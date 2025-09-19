# Compose

Docker compose pour déploiement. Chaque service est déployé via [Komo.do](https://komo.do/) depuis un dépot local.

# Dépôt Docker Compose

Ce dépôt contient des fichiers de configuration Docker Compose pour différents services auto-hébergés.

# Services déployés via docker compose :

## Stack réseau :

### AdGuard

Fichiers : [`adguard/compose.yaml`](adguard/compose.yaml)

## Stack cloud :

### Immich

Fichiers : [`immich/hwaccel.ml.yml`](immich/compose.yml)

### Vaultwarden

Fichiers : [`vaultwarden/compose.yaml`](vaultwarden/compose.yaml)

## Stack médias :

### Jellyfin (avec transcodage nvidia)

Fichiers : [`jellyfin/compose.yaml`](jellyfin/compose.yaml)

## Stack LLM :

### Ollama

Fichiers : [`ollama/compose.yaml`](ollama/compose.yaml)