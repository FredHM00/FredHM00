# Fred H. Martins — 42 School | Python Backend

Backend-leaning portfolio. 42 School (C, algorithms) + Python APIs (FastAPI, PostgreSQL).

## Showcase — start here

| Project | What it is | Stack |
|---|---|---|
| **[dataguard-api](https://github.com/FredHM00/dataguard-api)** | Educational REST API for fictitious service records — JWT auth, encrypted sensitive notes, audit trail | Python 3.12, FastAPI, PostgreSQL 16, SQLAlchemy 2.x, Alembic, Docker |
| **[Push_Swap](https://github.com/FredHM00/Push_Swap)** | 42 sorting project with limited stack operations | C, algorithms, complexity |
| **[Libft_42](https://github.com/FredHM00/Libft_42)** | Custom C library recreating libc + utils, reused across 42 projects | C, memory management |

> Portfolio intent: only 42 projects + `dataguard-api` stay public and pinned. Lab exercises, bootcamp forks and drafts are private, archived or removed.

## Stack

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic` `Docker` `pytest` `C` `Git` `Linux (WSL2)`

## What I am doing now

- 42 curriculum (Libft, Push_swap → next projects)
- Python modules (stdlib → data-oriented scripting)
- `dataguard-api`: hardening basics — JWT, rate-limit, audit, CI (Bandit, pip-audit, Gitleaks)

## Run dataguard-api

```bash
git clone https://github.com/FredHM00/dataguard-api.git
cd dataguard-api
cp .env.example .env
docker compose up -d --build
curl -s localhost:8000/health
```

OpenAPI: `http://localhost:8000/docs`