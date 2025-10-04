# Infra

Ce repo contient la plupart des services que j'héberge au quotidien. 

# Caractéristiques du cluster :

## Machines physiques

Un rpi 4 : Home Assistant

Un cluster Proxmox avec stockage CEPH distribué : 3 nodes - 32 CPU / 80 GB DDR

- Amélia - I76700K : 8c/16GB - Routeur full open-source sur NIC Intel 4x2.5G : Opensense VM, Wazuh & Suricata VM, Adguard LXC, Speedtest LXC, Proxy LXC (nginx, crowdsec, dbip, fail2ban, anubis)

- Anne - R3500GEPro : 8c/16GB - Forgejo LXC, Komodo LXC, SemaphoreUI LXC, Monitoring VM (Grafana, Prometheus & InfluxDB)

- Grace - R2700X : 16c/48 GB + passtrough GPU : Stockage VM (Openmediavault), Médias VM, Cloud VM, Frontend VM, LLM VM, Lab VM, KubeMaster VM, KubeWorker VM, ...

Pour de la virtualisation, j'aurai tendance à ne pas utiliser de processeurs hétérogènes. La DDR provient de chez G.Skill.

## Stockage

Les systèmes Proxmox sont sur SSD. En plus, le stockage de masse se compose comme suit :

- Un stockage distribué CEPH de 2x2 To pour les volumes des conteneurs, les métadonnées étant sur nvme.
- Un stockage médias partagé via samba chiffré géré par OpenMediaVault

Certains disques (médias) sont reconditionnés. Tous sont de la marque Seagate. Les SSD sont tous de la marque Samsung.

## Consommation 

En moyenne, mon infrastructure consomme 136 Wh. L'inférence GPU provoque des pics à 500W.