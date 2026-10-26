# AI Insurance Risk & Fraud Platform

Plateforme complète simulant un système de tarification et de détection de
fraude en assurance, avec pipeline MLOps de bout en bout.

## Lancer l'environnement

```bash
docker compose up -d --build
```

Services disponibles :
- Airflow : http://localhost:8080 (admin / admin)
- MLflow : http://localhost:5000
- API : http://localhost:8000/docs
- Prometheus : http://localhost:9090
- Grafana : http://localhost:3000 (admin / admin)

## Structure

Voir la documentation dans chaque sous-dossier (`src/`, `airflow/`, `api/`,
`monitoring/`, `spark_jobs/`).
