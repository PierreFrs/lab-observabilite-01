# Lab Observabilité : Les Bases

Ce dépôt contient l'infrastructure de base pour démarrer avec l'observabilité locale.

## Services inclus
- **Prometheus** (Port 9090) : Collecte et stocke les métriques.
- **Grafana** (Port 3000) : Outil de visualisation (dashboards).
- **Node Exporter** (Port 9100) : Expose les métriques système (CPU, RAM) pour simuler une machine à monitorer.

## Démarrage
1. Lancez les conteneurs : `docker compose up -d`
2. Accédez à Grafana : `http://localhost:3000` (Identifiant: `admin`, Mot de passe: `admin`)
3. Accédez à Prometheus : `http://localhost:9090` pour voir l'état des "Targets" (cibles).
