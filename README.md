# Homelab Docker — Monitoring & Dev

Documentazione dei due stack Docker Compose dell'host: monitoraggio (Uptime Kuma,
Prometheus, exporter, Grafana) e ambiente di sviluppo del sito (code-server,
FileBrowser), con limiti di memoria, restart policy e volumi dedicati.

## Contenuto

| File | Ruolo |
|---|---|
| `docker-report.html` | report dei container e delle scelte operative |
| `js/docker-i18n.js` | traduzioni IT/EN |

## Nota

I file compose originali sono gestiti fuori da questo repo (Portainer) e non
contengono segreti versionati. Le password di esempio nel report sono placeholder.
