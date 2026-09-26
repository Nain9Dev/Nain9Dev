<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=2563eb&center=true&vCenter=true&width=750&lines=Full+Stack+Software+Architect;Python+%26+.NET+Backends+%7C+Vue+3+Frontends;Deterministic+Product+Conformance+%26+Trustworthy+AI;MCP+%7C+Open+Core+%7C+Immutable+Contracts" alt="Full Stack Software Architect" />

  <p align="center">
    <strong>Aitor Nain Mendoza Vallejo (naindev)</strong><br />
    Madrid, Spain &bull; Full Stack Software Architect &bull; CTO at Contrast3D x NainDev
  </p>

  <p align="center">
    <a href="https://www.naindev.com/"><img src="https://img.shields.io/badge/Portfolio-naindev.com-2563eb?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" /></a>
    <a href="https://www.linkedin.com/in/aitor-nain-mendoza-vallejo/"><img src="https://img.shields.io/badge/LinkedIn-Aitor_Nain-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:contact@naindev.com"><img src="https://img.shields.io/badge/Email-contact@naindev.com-10B981?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email" /></a>
  </p>
</div>

---

## About

I am a full stack software architect with a backend focus. I specialize in **critical systems, trustworthy AI, and deterministic conformance**: architectures that validate products of any domain against explicit, versioned specifications, starting with 3D assets.

I deliver the complete product (data model, backend, and frontend) and integrate AI through **human-in-the-loop MCP tooling**, on **Open Core** architectures with clean code and immutable contracts.

**What I bring to a team or client:**

- **Python and .NET at the same level.** Python (FastAPI, Pydantic v2) for AI, validation, data, and 3D. .NET (ASP.NET Core) for business APIs and Microsoft-based clients.
- **End-to-end ownership.** PostgreSQL or SQL Server schemas, async APIs, accessible Vue 3 frontends (WCAG 2.2 AA), CI/CD, and deployment on Linux VPS or Azure.
- **Verifiable delivery.** Spec-driven development, property-based testing, and traceability from each requirement to the test that proves it.
- **Legacy modernization.** Incremental migration of .NET Framework backends to modern .NET without stopping the business.

---

## Current Work (Private Code)

My main work is not public. The first two systems I lead under my NainDev brand, outside working hours; the third is my full-time role as a .NET developer in the insurance sector. They are listed in order of focus and described by architecture and stack only:

- **Multi-Domain Deterministic Conformance Chassis (Open Core)**: Python 3.12 (`uv` monorepo), FastAPI, Pydantic v2, PostgreSQL, Model Context Protocol (MCP), pytest & Hypothesis, Docker, self-hosted CI.
  - *Architecture*: A domain-agnostic conformance chassis that receives an artefact, identifies what it is, measures facts about it, proposes the objectives and profile that apply, validates it, directs its fail-closed correction, and emits a verdict that is reproducible byte-for-byte. Each market domain plugs in as a versioned profile from a frozen, persisted catalogue; the catalogue version is recorded in every verdict.
  - *First profile, in production*: Real-time 3D assets (glTF/GLB). Binary stream parsing and byte-level container validation (IEEE-754 little-endian chunk extraction), exact computational geometry invariants (2D UV winding, polygon clipping, watertight manifold verification, differential texel density scaling), and a validate → repair → revalidate loop.
  - *Next profile, specified*: Tabular fiscal documents (invoice arithmetic, mandatory legal fields, and tax ID check-digit algorithms), which proves the same engine works outside 3D.
  - *Delivery*: Reproducible dual-contract audit reports (canonical JSON + human-readable Markdown), an HTTP service with OpenAPI, PostgreSQL persistence for stateful validation sessions, and stdio MCP tooling so AI agents run validations under human oversight.

- **High-Concurrency Multi-Tenant Operations & Commercial Platform**: Python 3.12, FastAPI, PostgreSQL, async SQLAlchemy, Alembic, Vue 3, TypeScript, Pinia, Tailwind CSS, Web Push (VAPID), Docker.
  - *Core capabilities*: Zero-data-loss collaboration using entity `version` tracking and field-level merge resolution on HTTP 409 conflicts. Data integrity enforced by PostgreSQL primitives (`citext`, partial unique indexes, and atomic `activity_events` audit logging within single transactions). Accessible frontend (WCAG 2.2 AA, TipTap rich text, interactive 3D model viewers) and near-zero compute cost on self-hosted environments backed by local CI runner fleets.

- **Insurance-Sector Backend & Legacy .NET Modernization (full-time role)**: C#, ASP.NET Core, .NET Framework (4.7.2+) to modern .NET, ASP.NET Web API, Azure services, SQL Server, Clean Architecture, DDD.
  - *Core capabilities*: RESTful APIs for insurance policy management and risk scoring. Maintenance, security hardening, and incremental modernization of mission-critical business backends. Integration layer orchestrating multiple third-party enterprise providers (payment gateways, digital signature APIs, financial scoring services, cloud storage, and automated transactional document generation).

---

## Public Reference Projects

Open-source projects with source code, automated tests, and live demos:

| Project | Stack | What it demonstrates | Links |
|---|---|---|---|
| **[ParametriCAD AI](https://github.com/Nain9Dev/parametricad-ai)** | Python 3.12, FastAPI, OpenCASCADE, CadQuery, Three.js, React 19, TypeScript, Docker | **Deterministic CAD engine and 3D web viewer.** Builds exact B-Rep solids, enforces fabricability invariants, verifies mesh topology (watertightness, 2-manifoldness, normal orientation), and exports GLB, glTF, STEP, STL, and DXF with SHA-256 content addressing. 261 automated tests, including Hypothesis property-based tests. | [**Live app**](https://parametricad.naindev.com)<br>[Source](https://github.com/Nain9Dev/parametricad-ai) |
| **[Financial Policy Operations API](https://github.com/Nain9Dev/API-Gestion-Financiera)** | .NET 10, C#, EF Core 10, SQL Server, Clean Architecture, DDD, Azure | **Enterprise lifecycle engine.** Insurance policy state transitions (`Draft -> Active -> Cancelled`), tenant isolation, and optimistic concurrency control via ETags. | [**Live Swagger**](https://nain-policy-demo-api.azurewebsites.net/demo/)<br>[Source](https://github.com/Nain9Dev/API-Gestion-Financiera) |
| **[Civil Service Examination Platform (TAI)](https://github.com/Nain9Dev/SistemaOposicionesTAI)** | .NET 10, C#, Dapper, SQL Server, React 19, TypeScript | **Assessment system.** Exam evaluation engine applying the official INAP scoring rules (+1.0 / -0.33) with a responsive SPA. | [**Live demo**](https://www.naindev.com/SistemaOposicionesTAI/)<br>[Source](https://github.com/Nain9Dev/SistemaOposicionesTAI) |
| **[NainOrder Core API](https://github.com/Nain9Dev/NainOrder)** | .NET 10, C#, EF Core 10, SQL Server, Clean Architecture, CQRS, DDD | **E-commerce transactional core.** Order processing with CQRS, aggregate boundaries, and optimistic locking. | [Source](https://github.com/Nain9Dev/NainOrder) |
| **[Notifications Microservice](https://github.com/Nain9Dev/Microservicio-Notificaciones)** | .NET 10, C#, MassTransit, RabbitMQ, MailKit, Docker | **Asynchronous dispatcher.** Message-driven notification service with dead-letter exchanges and exponential backoff retries. | [**Live demo**](https://www.naindev.com/#demo-notificaciones)<br>[Source](https://github.com/Nain9Dev/Microservicio-Notificaciones) |
| **[Driving School Operations Engine](https://github.com/Nain9Dev/Gestion-Autoescuela-Python)** | Python 3.12, Pydantic v2, SQLAlchemy, SQLite, Streamlit | **Operations and ledger dashboard.** Accounting with deterministic financial validation, balance reconciliation, and PDF invoice generation. | [**Live demo**](https://gestion-autoescuela-nain9dev.streamlit.app/)<br>[Source](https://github.com/Nain9Dev/Gestion-Autoescuela-Python) |

---

## Tech Stack

| Area | Default choice | Also in production experience |
|---|---|---|
| **Languages** | Python, C#, TypeScript, SQL | |
| **Backend (Python)** | FastAPI, Pydantic v2, async SQLAlchemy, Alembic | Streamlit, OpenCASCADE / CadQuery |
| **Backend (.NET)** | ASP.NET Core Web API, Clean Architecture, EF Core, Dapper for heavy reads | .NET Framework, ASP.NET Web API 2 / MVC 5, stored procedures |
| **Frontend** | Vue 3, TypeScript, Pinia, Vite, Tailwind CSS, Astro | React 19, Three.js / WebGL, Razor + jQuery |
| **Data** | PostgreSQL, SQL Server | SQLite, Redis |
| **AI integration** | Model Context Protocol (MCP), human-in-the-loop workflows, fail-closed contracts | Local LLMs (Ollama) |
| **Testing** | pytest + Hypothesis, xUnit v3, Vitest + Playwright, Testcontainers | |
| **Infrastructure** | Docker / Compose, GitHub Actions (self-hosted runners), Linux VPS, Azure | RabbitMQ / MassTransit |

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" alt="Pydantic" />
  <img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <br />
  <img src="https://img.shields.io/badge/Vue.js_3-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue 3" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white" alt="Astro" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge" alt="SQL Server" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</div>

```text
+-----------------------------------------------------------------------------------+
|                                  Presentation                                     |
|   Vue 3 + TypeScript (WCAG 2.2 AA) | Astro | Three.js / WebGL 3D viewers          |
+-----------------------------------------+-----------------------------------------+
                                          |  OpenAPI contracts
+-----------------------------------------v-----------------------------------------+
|                                  Application                                      |
|   FastAPI | ASP.NET Core | MCP tools with human-in-the-loop approval              |
+-----------------------------------------+-----------------------------------------+
                                          |
+-----------------------------------------v-----------------------------------------+
|                                    Domain                                         |
|   Deterministic invariants | Immutable contracts (Pydantic v2 / C# records)       |
+-----------------------------------------+-----------------------------------------+
                                          |
+-----------------------------------------v-----------------------------------------+
|                                 Infrastructure                                    |
|   PostgreSQL | SQL Server | Docker | GitHub Actions | Linux VPS | Azure           |
+-----------------------------------------------------------------------------------+
```

---

## How I Work

1. **Spec-driven development**: Every change starts in a specification (charter, EARS requirements, architecture with Mermaid diagrams, data model, ADRs, and traceability), never directly in code.
2. **Nothing claimed without a test**: Business rules and geometric invariants are covered by automated and property-based tests. A requirement without a test is not done.
3. **Strict layer boundaries**: The frontend presents and the backend decides. Business logic lives in the domain and services; data access lives only in repositories.
4. **Immutable public contracts**: APIs, schemas, and reports are versioned contracts. Breaking changes are explicit and documented.
5. **Human-in-the-loop AI**: AI agents act through MCP tools with deterministic checks and human approval, and fail closed when uncertain.
6. **Open Core and cost awareness**: Free and open-source tooling for demos and proofs of concept; production costs are evaluated against each product's business model.

---

## Contact

Open to part-time, remote projects in software architecture, backend engineering, legacy .NET modernization, and deterministic conformance systems:

- **Portfolio**: [www.naindev.com](https://www.naindev.com/)
- **Email**: [contact@naindev.com](mailto:contact@naindev.com)
- **LinkedIn**: [Aitor Nain Mendoza Vallejo](https://www.linkedin.com/in/aitor-nain-mendoza-vallejo/)
