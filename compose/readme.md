# Compose

Docker compose pour déploiement. Chaque service est déployé via [Komo.do](https://komo.do/) depuis un dépot local.


# Services déployés :

## Stack réseau :

### AdGuard

    AdGuard est un service de DNS complet avec GUI, blocages, réécritures DNS. Supporte DoH, DoT ou encore Quic.

Fichiers : [`adguard/compose.yaml`](adguard/compose.yaml)

## Stack cloud :

### Authentik

    Authentik permet de centraliser la configuration des identifiants en un point unique. SSO, LDAP, OICD, ...

Fichiers : [`authentik/compose.yaml`](authentik/compose.yaml)

### Immich

Fichiers : [`immich/compose.yml`](immich/compose.yml)

### Vaultwarden

Fichiers : [`vaultwarden/compose.yaml`](vaultwarden/compose.yaml)

## Stack médias :

### Jellyfin (avec transcodage nvidia)

Fichiers : [`jellyfin/compose.yaml`](jellyfin/compose.yaml)

## Stack LLM :

### Ollama

Fichiers : [`ollama/compose.yaml`](ollama/compose.yaml)