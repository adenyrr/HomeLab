# Prod

Environnement de production

# Caractéristiques :

Un rpi 4 : Home Assistant

Un cluster Proxmox avec stockage CEPH distribué : 3 nodes - 32 CPU / 80 GB DDR

- Amélia - 8c/16GB - Routeur full open-source sur NIC Intel 4x2.5G : Opensense VM, Wazuh & Suricata VM, Adguard LXC, Speedtest LXC, Proxy LXC (nginx, crowdsec, dbip, fail2ban, anubis)
- Anne - 8c/16GB - Forgejo LXC, Komodo LXC, SemaphoreUI LXC, Monitoring VM (Grafana, Prometheus & InfluxDB)
- Grace - 16c/48 GB + passtrough GPU : Stockage VM (Openmediavault), Médias VM, Cloud VM, Frontend VM, LLM VM, Lab VM, KubeMaster VM, KubeWorker VM, ...