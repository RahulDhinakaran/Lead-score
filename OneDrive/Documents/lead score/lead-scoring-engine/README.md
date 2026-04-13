# Lead Scoring Engine

[![coverage](https://img.shields.io/codecov/c/gh/RahulDhinakaran/Lead-score?style=flat-square)](https://codecov.io/gh/RahulDhinakaran/Lead-score)

Production-ready, modular Lead Scoring Engine built with FastAPI, Scikit-learn/XGBoost, PostgreSQL, Redis, and Celery. Designed for Real Estate and extensible to multiple industries.

Quickstart (development):

1. Copy `.env` and adjust values if needed.

2. Build and run with Docker Compose:

```bash
docker-compose up --build
```

3. API base: `http://localhost:8000/api` — Swagger at `http://localhost:8000/docs`.

Security: protected endpoints require header `x-api-key` using the value from `.env`.

Run tests locally (Python env required):

```bash
pip install -r requirements.txt
pytest -q
```

Deployment notes: see `docs/DEPLOY.md` for production recommendations and CI instructions.
