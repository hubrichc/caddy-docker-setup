# caddy-docker-setup
Kompletter Standardsetup für Caddy in Docker


Dieses Repository enthält alle notwendigen Dateien, um einen Caddy-Server mit Docker einzurichten.

## Verzeichnisstruktur

```
caddy/
├── Caddyfile
├── docker-compose.yml
├── config/
└── data/
```

## Installationsanleitung

1. Klonen Sie das Repository:
   ```bash
   git clone <repository-url> caddy
   cd caddy
   ```

2. Passen Sie die `Caddyfile`-Konfiguration an Ihre Anforderungen an.

3. Starten Sie den Caddy-Server:
   ```bash
   docker-compose up -d
   ```

4. Zugriff auf den Server:
   - HTTP: `http://localhost`
   - HTTPS: `https://localhost`

Viel Spaß mit Ihrer Caddy-Installation!
