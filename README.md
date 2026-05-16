# Course Materials Service

A practice backend API for an e-learning platform that recommends educational resources to students.

## Features

- REST API for course items (courses, labs, tasks, steps)
- `/status` health check and `/items` endpoints
- Bug investigation and fix workflow
- Dockerized deployment to a Linux VM

## Tech stack

- Python 3.12+, FastAPI
- pytest for testing
- Docker + Docker Compose
- Caddy reverse proxy

## Quick start

```bash
# Local
uv sync
uv run fastapi dev src/app/main.py

# Docker
docker compose up --build
```

## Project structure

- `src/app/` — FastAPI application
- `tests/` — pytest suite
- `docker-compose.yml` — full stack with Caddy
