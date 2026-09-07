<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=2563eb&center=true&vCenter=true&width=750&lines=Autonomous+Software+Architect;Mission-Critical+Backends+%26+Deterministic+Systems;.NET+10+%7C+Python+FastAPI+%7C+TypeScript;OpenCASCADE+CAD+Engines+%26+Three.js+3D+Web" alt="Typing Banner" />

  <p align="center">
    <strong>Aitor Nain Mendoza Vallejo (naindev)</strong><br />
    Madrid, Spain &bull; Autonomous Software Architect &bull; Backend, Deterministic Geometry & Production AI
  </p>

  <p align="center">
    <a href="https://www.naindev.com/"><img src="https://img.shields.io/badge/Official_Portfolio-naindev.com-2563eb?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Web Portfolio" /></a>
    <a href="https://www.linkedin.com/in/aitor-nain-mendoza-vallejo/"><img src="https://img.shields.io/badge/LinkedIn-Aitor_Nain-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:contact@naindev.com"><img src="https://img.shields.io/badge/Direct_Contact-contact@naindev.com-10B981?style=for-the-badge&logo=mail.ru&logoColor=white" alt="Email" /></a>
  </p>
</div>

---

## Architectural Profile & Core Focus

I design and build **fault-tolerant backend architectures, deterministic validation engines, and high-assurance AI integrations** for systems where failure is not an option. My engineering approach enforces strict separation of concerns, formal specification before implementation (Spec-Driven Development), and mathematically verified domain invariants.

### Engineering Pillars

- **Deterministic Computational Systems**: Exact Boundary Representation (B-Rep) solid modeling via OpenCASCADE and CadQuery, domain-isolated 2-manifold topological mesh verification, and content-addressable artifact pipelines.
- **Enterprise Backend Architecture**: Hexagonal Architecture (Ports and Adapters), Clean Architecture, Domain-Driven Design (DDD), and CQRS across asynchronous distributed systems.
- **Production AI Integrations**: Deterministic parameter extraction, robust fallback mechanisms (rule-based offline parsers alongside LLMs), and strict Pydantic JSON contracts.
- **High-Performance Persistence**: Complex relational modeling, multi-tenant isolation, auditing, and high-throughput concurrency control (ETag, rowversion) across Microsoft SQL Server, PostgreSQL, and SQLite.

---

## Flagship Systems & Live Verifiable Deployments

All projects are engineered with verifiable evidence, automated test suites, and 1-click cloud demonstrations:

| System / Repository | Primary Stack | Architecture & Verification | Live Demonstration |
|---|---|---|---|
| **[ParametriCAD AI](https://github.com/Nain9Dev/parametricad-ai)** | Python 3.12, FastAPI, OpenCASCADE, CadQuery, Three.js, React 19, TypeScript, Docker | **Deterministic CAD Engine & 3D Web Viewer.** Constructs exact B-Rep solids, enforces physical fabricability invariants, verifies topological mesh quality (watertightness, 2-manifoldness, normal orientation), and exports 5 engineering formats (GLB, glTF, STEP, STL, DXF) with SHA-256 content addressing. 261 automated tests including Hypothesis property-based testing. | [**Open 3D App**](https://parametricad.naindev.com)<br>[Source Code](https://github.com/Nain9Dev/parametricad-ai) |
| **[Microservice Notifications Core](https://github.com/Nain9Dev/Microservicio-Notificaciones)** | .NET 10, C#, MassTransit, RabbitMQ, MailKit, Clean Architecture, Docker | **Sub-50ms Asynchronous Dispatcher.** Decoupled notification microservice built on message queues with dead-letter exchanges, exponential backoff retries, and cluster isolation. | [**Interactive Demo**](https://www.naindev.com/#demo-notificaciones)<br>[Source Code](https://github.com/Nain9Dev/Microservicio-Notificaciones) |
| **[Financial Policy Operations API](https://github.com/Nain9Dev/API-Gestion-Financiera)** | .NET 10, C#, EF Core 10, SQL Server, Clean Architecture, DDD, Azure | **Enterprise Lifecycle Engine.** Manages insurance policy state transitions (`Draft -> Active -> Cancelled`), tenant isolation, and strict optimistic concurrency control via ETags. | [**Live Swagger API**](https://nain-policy-demo-api.azurewebsites.net/demo/)<br>[Source Code](https://github.com/Nain9Dev/API-Gestion-Financiera) |
| **[Civil Service Examination Platform (TAI)](https://github.com/Nain9Dev/SistemaOposicionesTAI)** | .NET 10, C#, Dapper, SQL Server, React 19, TypeScript | **High-Throughput Assessment System.** Real-time examination evaluation engine executing official INAP scoring algorithms (+1.0 / -0.33) with sub-10ms query response times and responsive SPA interface. | [**Test Platform**](https://www.naindev.com/SistemaOposicionesTAI/)<br>[Source Code](https://github.com/Nain9Dev/SistemaOposicionesTAI) |
| **[Driving School Financial & Ops Engine](https://github.com/Nain9Dev/Gestion-Autoescuela-Python)** | Python 3.12, Pydantic v2, SQLAlchemy, SQLite, Streamlit | **Operational & Ledger Dashboard.** Business accounting platform with deterministic financial validation, automatic balance reconciliations, and PDF invoice generation. | [**Launch Demo**](https://gestion-autoescuela-nain9dev.streamlit.app/)<br>[Source Code](https://github.com/Nain9Dev/Gestion-Autoescuela-Python) |

---

## Technical Stack & Tooling

<div align="center">
  <img src="https://img.shields.io/badge/Python_3.12-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/.NET_10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET 10" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React 19" />
  <br />
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/OpenCASCADE-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="OpenCASCADE" />
  <img src="https://img.shields.io/badge/Microsoft_SQL_Server-CC292B?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" alt="SQL Server" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" alt="RabbitMQ" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</div>

<br />

```text
+-----------------------------------------------------------------------------------+
|                            Presentation & Ingestion                               |
|   React 19 (Three.js / WebGL) | Astro | OpenAPI / REST | Asynchronous Workers     |
+-----------------------------------------+-----------------------------------------+
                                          |
+-----------------------------------------v-----------------------------------------+
|                        Application Orchestration & Ports                          |
|   Spec-Driven Pipelines | CQRS Mediators | Domain Events | MassTransit Queues     |
+-----------------------------------------+-----------------------------------------+
                                          |
+-----------------------------------------v-----------------------------------------+
|                            Domain Core & Pure Logic                               |
|   Boundary Invariants | Pydantic Contracts | Topological Verification | Entities  |
+-----------------------------------------+-----------------------------------------+
                                          |
+-----------------------------------------v-----------------------------------------+
|                        Infrastructure & External Adapters                         |
|   OpenCASCADE (CadQuery) | SQL Server (T-SQL) | PostgreSQL | RabbitMQ | Filesystem |
+-----------------------------------------------------------------------------------+
```

---

## Methodology & Architectural Principles

1. **Spec-Driven Development (SDD)**: Changes originate in explicit specifications (`charter`, `requirements` in EARS format, `architecture` with Mermaid diagrams, `data-model`, `ADRs`, and `traceability`), never directly in unconstrained code.
2. **Deterministic Quality & Zero Assumptions**: All geometric invariants and business rules are validated by automated property-based test suites. No capability is claimed without reproducible automated verification.
3. **Decoupled Domain Layers**: The presentation layer captures input and renders responses; it never calculates business logic, enforces business invariants, or accesses persistence.
4. **Resilient & Cost-Conscious Infrastructure**: Low-overhead architectures designed for minimal compute footprints, high cache hit rates (content addressing), and horizontal process isolation over unsafe threading.

---

## Contact & Technical Consulting

Available for independent software architecture consulting, mission-critical backend design, and deterministic computational systems:

- **Portfolio & Case Studies**: [www.naindev.com](https://www.naindev.com/)
- **Email**: [contact@naindev.com](mailto:contact@naindev.com)
- **LinkedIn**: [Aitor Nain Mendoza Vallejo](https://www.linkedin.com/in/aitor-nain-mendoza-vallejo/)
- **GitHub**: [github.com/Nain9Dev](https://github.com/Nain9Dev)
