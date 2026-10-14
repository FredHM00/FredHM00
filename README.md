<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,100:6366f1&height=130&section=header&text=Frederick%20H.%20Martins&fontColor=ffffff&fontSize=32&animation=fadeIn" width="100%"/>

# 42 School | Python Backend

Backend-leaning portfolio. 42 School (C, algorithms) + Python APIs (FastAPI, PostgreSQL).

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=333)
![Linux](https://img.shields.io/badge/Linux-000000?style=flat&logo=linux&logoColor=white)

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

## Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FredHM00/FredHM00/main/dist/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/FredHM00/FredHM00/main/dist/github-snake.svg" />
  <img alt="Contribution snake (orange on blue, auto light/dark)" src="https://raw.githubusercontent.com/FredHM00/FredHM00/main/dist/github-snake.svg" width="100%" />
</picture>

> The snake above is generated daily from my contribution graph by the `Generate contribution snake` workflow. If the image is not showing yet, run the workflow once manually (Actions tab → Run workflow).

## Run dataguard-api

```bash
git clone https://github.com/FredHM00/dataguard-api.git
cd dataguard-api
cp .env.example .env
docker compose up -d --build
curl -s localhost:8000/health
```

OpenAPI: `http://localhost:8000/docs`

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,100:0ea5e9&height=110&section=footer" width="100%"/>
