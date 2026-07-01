<div align="center">
  <h1>Alexandre Constancio</h1>
  <h3>Systems Architect · AI Engineer · Infrastructure Builder</h3>
  <p><i>"First, solve the problem. Then, write the code."</i> — John Johnson</p>
</div>

---

## ⚙️ Engineering Philosophy

I design and build systems where **context is the product**. My work spans the full stack — from NixOS system configurations and Rust daemons to Go microservices and Svelte frontends — unified by a relentless focus on **determinism, offline-first architecture, and testable boundaries**.

Core principles:
- **Domain-Driven Design** with Feature-First structure
- **KISS, DRY, SOLID** — pragmatism over dogma
- **Defense in depth** — validation at every layer boundary
- **Local-first** — sync is a feature, not a requirement

---

## 🛠 Technical Landscape

### Languages & Runtimes

| Domain | Stack |
|--------|-------|
| **Systems & Infrastructure** | Rust (tokio, axum, clap), Nix (flakes, home-manager, sops-nix) |
| **Backend & Services** | Go 1.26 (chi, cobra, OpenTelemetry), Python 3.12+ (FastAPI, Celery, SQLAlchemy) |
| **Frontend & Mobile** | Svelte 5 / SvelteKit, Flutter / Dart, TypeScript |
| **Data & ML** | PostgreSQL, Redis, SQLite (Drift), geospatial (rasterio, geopandas) |

### Infrastructure & Tooling

| Layer | Tools |
|-------|-------|
| **System Configuration** | NixOS, Nix Flakes, home-manager, sops-nix (secrets), age encryption |
| **Process & Service Management** | tokio (async runtime), axum (HTTP/WS), Temporal (workflow orchestration) |
| **Package Management** | Cargo, uv, bun, pnpm, Turborepo |
| **Task Runners** | just (Justfile), Make |
| **Observability** | OpenTelemetry (OTLP/gRPC), Sentry, Prometheus |
| **Containerization** | Docker Compose, Caddy (reverse proxy) |
| **CI/CD** | Google Cloud Build, Firebase |
| **Version Control** | Git, lefthook, Husky, commitlint |

### Frontend Ecosystem

| Layer | Stack |
|-------|-------|
| **Framework** | Svelte 5 + SvelteKit, Flutter, Next.js (legacy) |
| **Styling** | Tailwind CSS v4, custom design tokens |
| **Component Libraries** | bindrunes (270+ components, 60+ composables), bits-ui, lucide-svelte |
| **State Management** | flutter_riverpod, zustand, SWR |
| **Forms & Validation** | valibot, react-hook-form, yup, zod |
| **Testing** | Vitest, Playwright (e2e), Storybook |

### Backend Architecture

| Layer | Stack |
|-------|-------|
| **Go Services** | chi router, cobra CLI, golang-jwt, lib/pq, OpenTelemetry, dockertest |
| **Python Services** | FastAPI, SQLAlchemy (async), Alembic, Celery + Redis, pydantic |
| **Rust Services** | tokio async runtime, axum HTTP framework, sysinfo, serde |
| **Databases** | PostgreSQL 15, SQLite (Drift/go-sqlite3), Redis |
| **Auth & Security** | JWT, PKCS#12, sops-nix + age |

### Data & Intelligence

| Layer | Stack |
|-------|-------|
| **Geospatial** | rasterio, geopandas, shapely, pyproj, scikit-image, flutter_map |
| **AI/LLM** | OpenTelemetry-inferred pipelines, tiktoken, RAG architectures |
| **Document Processing** | go-fitz (PDF), unioffice, reportlab, Gotenberg |
| **Search & Retrieval** | Custom MMU designs, RAG pipelines with strict hallucination controls |

---

## 🔭 Current Focus

**LLM Context Architecture**
Designing Memory Management Units (MMU) and RAG pipelines that treat context as a first-class engineering concern — deterministic retrieval, strict token budgets, zero hallucination tolerance.

**NixOS-Native Infrastructure**
Building reproducible system configurations with Nix flakes, integrating Rust daemons and Dart TUIs into a unified, declarative stack. Every service is a flake output.

**Local-First Mobile Ecosystems**
Engineering privacy-centric applications with offline-first sync (PowerSync + Supabase), structured local databases (Drift), and conflict-free replication.

**Intelligence Engine Development**
Building a shared Go intelligence library (talos) that powers classification, LLM orchestration, and persona management across the entire product suite.

---

<div align="center">

**Structured logic. Scalable design. Zero fluff.**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/aleconstancio)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/aleconstancio)

</div>
