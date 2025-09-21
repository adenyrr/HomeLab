# Compose

Docker compose pour déploiement. Chaque service est déployé via [Komo.do](https://komo.do/) depuis un dépot local.


# Services déployés :

## Stack réseau :

### AdGuard

    AdGuard est un service de DNS complet avec GUI, blocages, réécritures DNS. Supporte DoH, DoT ou encore Quic.

- Fichiers: [`adguard/compose.yaml`](adguard/compose.yaml)
- Tutoriels: SOON
- Site du projet: [AdGuard.com](https://adguard.com/fr/adguard-home/overview.html)
- Code source: [GH AdGuard](https://github.com/AdguardTeam/AdGuardHome)

### Wazuh

    Wazuh est une plateforme de surveillance et de réponse aux évènements d'une infrastructure.

- Fichiers: [`wazuh/compose.yaml`](wazuh/compose.yaml)
- Tutoriels: SOON
- Site du projet: [Wazuh.com](https://wazuh.com/)
- Code source: [GH Wazuh](https://github.com/Wazuh/Wazuh)


## Stack cloud :

### Authentik

    Authentik permet de centraliser la configuration des identifiants en un point unique. SSO, LDAP, OICD, ...

- Fichiers: [`authentik/compose.yaml`](authentik/compose.yaml)
- Tutoriels: SOON
- Site du projet: [Authentik.io](https://goauthentik.io/)
- Code source: [GH Authentik](https://github.com/goauthentik/authentik)

### Immich

    Immich est un gestionnaire de sauvegardes photos et vidéos, avec applications mobiles.

- Fichiers: [`immich/compose.yml`](immich/compose.yml)
- Tutoriels: SOON
- Site du projet: [Immich.app](https://immich.app/)
- Code source: [GH Immich](https://github.com/immich-app/immich)

### Vaultwarden

    Vaultwarden est un fork de Bitwarden, le gestionnaire de mot de passe.

- Fichiers: [`vaultwarden/compose.yaml`](vaultwarden/compose.yaml)
- Tutoriels: SOON
- Site du projet: [Vaultwarden.net](https://www.vaultwarden.net/)
- Code source: [GH Vaultwarden](https://github.com/dani-garcia/vaultwarden)

### Linkwarden

    Linkwarden est un manager de marque-pages. Il permet de sauvegarder, trier et consulter plus tard des liens.

- Fichiers: [`linkwarden/compose.yml`](linkwarden/compose.yml)
- Tutoriels: SOON
- Site du projet: [Linkwarden.app](https://linkwarden.app/)
- Code source: [GH Linkwarden](https://github.com/linkwarden/linkwarden)

## Stack monitoring

### Grafana

    Grafana permet de mettre en forme de manière complètement libre les données récoltées par d'autres sources.

- Fichiers: [`grafana/compose.yaml`](grafana/compose.yaml)
- Tutoriels: SOON
- Site du projet: [Grafana.com](https://grafana.com/)
- Code source: [GH Grafana](https://github.com/grafana/grafana)


## Stack médias :

### Jellyfin (avec transcodage nvidia)

    Jellyfin est une plateforme de streaming entièrement autohébergée, similaire à Plex.

- Fichiers: [`jellyfin/compose.yaml`](jellyfin/compose.yaml)
- Tutoriels: [become.sh](https://docs.become.sh/services/jellyfin/)
- Site du projet: [Jellyfin.org](https://jellyfin.org/)
- Code source: [GH Jellyfin](https://github.com/jellyfin/jellyfin)

## Stack LLM :

### Ollama + OpenWebUI

    Ollama est une plateforme permettant de télécharger et utiliser des LLM. OpenWebUI est une interface de gestion d'Ollama permettant d'utiliser outils, fonctions, RAG, chatbot et plus encore.

- Fichiers: [`ollama/compose.yaml`](ollama/compose.yaml)
- Tutoriels: [become.sh](https://docs.become.sh/services/ollama/)
- Site du projet: [Ollama.com](https://ollama.com/) && [OpenWebUI.com](https://openwebui.com/)
- Code source: [GH Ollama](https://github.com/ollama/ollama) && [GH OpenWebUI](https://github.com/open-webui/open-webui)