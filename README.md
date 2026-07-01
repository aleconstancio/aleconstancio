<div align="center">
  <h2>Alexandre Constancio</h2>
  <h3>Systems Architect · AI Engineer · Infrastructure Builder</h3>
</div>

---

Full stack engineer who delves too much into infra and multiplatform development.

- **Multiplatform:** Flutter and Dart for cross-platform mobile and desktop — offline-first apps with Drift local databases, Riverpod state management, go_router navigation, and Supabase sync.
- **Go Backends:** Microservices and shared libraries with Chi router, cobra CLI, golang-jwt auth, lib/pq, OpenTelemetry tracing, and dockertest for integration testing against real PostgreSQL and Redis.
- **Svelte 5 Web:** SvelteKit applications with Tailwind v4, Svelte 5 runes, bits-ui primitives. Created **bindrunes** — a published component framework (270+ components, 60+ composables) with full SvelteKit integration.
- **NixOS-Native Infra:** Reproducible system configurations with Nix flakes — Rust daemons (tokio/axum), Dart TUIs, home-manager, sops-nix + age for secrets. Declarative from kernel to UI.
- **AI & Data Intelligence:** LLM orchestration with RAG pipelines, Memory Management Units, and deterministic retrieval. Geospatial analysis with rasterio, geopandas, FastAPI, and Celery + Redis task queues.

---

## Tech Stack

### Languages & Runtimes

| Domain | Stack |
|--------|-------|
| **Systems** | <img src="https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white" alt="Rust" /> <img src="https://img.shields.io/badge/Nix-5277C3?style=flat&logo=nixos&logoColor=white" alt="Nix" /> tokio, axum, clap, flakes, home-manager |
| **Backend** | <img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white" alt="Go" /> <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python" /> chi, cobra, OpenTelemetry, FastAPI, Celery |
| **Frontend** | <img src="https://img.shields.io/badge/Svelte-FF3E00?style=flat&logo=svelte&logoColor=white" alt="Svelte" /> <img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white" alt="Flutter" /> <img src="https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white" alt="Dart" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript" /> SvelteKit, Riverpod, Tailwind v4 |
| **Data** | <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL" /> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" alt="Redis" /> <img src="https://img.shields.io/badge/SQLite-07405E?style=flat&logo=sqlite&logoColor=white" alt="SQLite" /> Drift, geopandas, rasterio |

### Infrastructure & Tooling

| Layer | Tools |
|-------|-------|
| **System Config** | <img src="https://img.shields.io/badge/NixOS-5277C3?style=flat&logo=nixos&logoColor=white" alt="NixOS" /> Nix Flakes, home-manager, sops-nix, age |
| **Async Runtime** | <img src="https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white" alt="Rust" /> tokio, axum |
| **Observability** | <img src="https://img.shields.io/badge/OpenTelemetry-60E6CC?style=flat&logo=opentelemetry&logoColor=black" alt="OTel" /> <img src="https://img.shields.io/badge/Sentry-362D59?style=flat&logo=sentry&logoColor=white" alt="Sentry" /> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white" alt="Prometheus" /> |
| **Containers** | <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker" /> <img src="https://img.shields.io/badge/Caddy-FF6B35?style=flat&logoColor=white" alt="Caddy" /> Docker Compose |
| **Task Runners** | <img src="https://img.shields.io/badge/just-1A1A1A?style=flat&logoColor=white" alt="just" /> just, Make |
| **CI/CD** | <img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white" alt="GCP" /> <img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat&logo=firebase&logoColor=white" alt="Firebase" /> Cloud Build |
| **Version Control** | <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub" /> lefthook, Husky, commitlint |

### Frontend Ecosystem

| Layer | Stack |
|-------|-------|
| **Framework** | <img src="https://img.shields.io/badge/Svelte-FF3E00?style=flat&logo=svelte&logoColor=white" alt="Svelte" /> Svelte 5 + SvelteKit, <img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white" alt="Flutter" /> Flutter |
| **Styling** | <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white" alt="Tailwind" /> Tailwind v4, custom design tokens |
| **Components** | bindrunes (270+ components), bits-ui, lucide-svelte |
| **State** | flutter_riverpod, zustand, SWR |
| **Testing** | <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white" alt="Vitest" /> <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white" alt="Playwright" /> Vitest, Playwright, Storybook |

### Backend Architecture

| Layer | Stack |
|-------|-------|
| **Go** | chi, cobra, golang-jwt, lib/pq, OpenTelemetry, dockertest |
| **Python** | <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" alt="FastAPI" /> FastAPI, SQLAlchemy, Alembic, Celery, pydantic |
| **Rust** | <img src="https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white" alt="Rust" /> tokio, axum, sysinfo, serde |
| **Databases** | <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL" /> PostgreSQL, <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" alt="Redis" /> Redis, SQLite (Drift) |
| **Auth** | JWT, PKCS#12, sops-nix + age |

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/aleconstancio)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/alexandreconstancio)

</div>
