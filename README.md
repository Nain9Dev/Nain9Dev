<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=2563eb&center=true&vCenter=true&width=750&lines=Autonomous+Software+Architect;Full+Stack+Delivery+%7C+.NET+%26+Python;Deterministic+Product+Validation+(3D+%26+Specs);Enterprise+Backends+%26+Legacy+Modernization" alt="Typing Banner" />

  <p align="center">
    <strong>Aitor Nain Mendoza Vallejo (naindev)</strong><br />
    Madrid, Spain &bull; Autonomous Software Architect &bull; Full Stack: .NET & Python, Deterministic Validation & Production AI
  </p>

  <p align="center">
    <a href="https://www.naindev.com/"><img src="https://img.shields.io/badge/Official_Portfolio-naindev.com-2563eb?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Web Portfolio" /></a>
    <a href="https://www.linkedin.com/in/aitor-nain-mendoza-vallejo/"><img src="https://img.shields.io/badge/LinkedIn-Aitor_Nain-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:contact@naindev.com"><img src="https://img.shields.io/badge/Direct_Contact-contact@naindev.com-10B981?style=for-the-badge&logo=mail.ru&logoColor=white" alt="Email" /></a>
  </p>
</div>

---

## Architectural Profile & Core Focus

I design, build, and deliver complete software products—spanning robust database modeling, high-throughput backend systems (.NET and Python), and accessible modern frontends. My focus centers on **deterministic validation of market products (technical specifications, 3D assets, and data integrity), enterprise backend architectures, legacy .NET modernization, and production AI integrations**.

### Engineering Pillars

- **Deterministic Validation & Conformance**: Deterministic product validation engines, 3D asset & geometry verification against industry standards (topology, watertightness, texel density), Boundary Representation (B-Rep) solid modeling via OpenCASCADE, and canonical audit reporting.
- **Enterprise Backend Architecture & Legacy Modernization**: Clean Architecture, Domain-Driven Design (DDD), and CQRS across ASP.NET Core and FastAPI. Modernizing legacy .NET systems, high-throughput microservices, and resilient message-driven pipelines.
- **Full Stack & High-Performance Persistence**: Complete product ownership from relational design and auditing to client-side delivery. Multi-tenant isolation, transactional event logging, and strict optimistic concurrency control (PostgreSQL, SQL Server). Accessible, high-performance web frontends (Vue 3, TypeScript, Astro, WCAG 2.2 AA).
- **Production AI & Autonomous Integrations**: Deterministic parameter extraction, robust offline rule-based fallbacks alongside LLMs, and fail-closed Pydantic/OpenAPI contracts.

---

## Flagship Systems & Live Verifiable Deployments

All projects are engineered with verifiable evidence, automated test suites, and 1-click cloud demonstrations:

| System / Repository | Primary Stack | Architecture & Verification | Live Demonstration |
|---|---|---|---|
| **[ParametriCAD AI](https://github.com/Nain9Dev/parametricad-ai)** | Python 3.12, FastAPI, OpenCASCADE, CadQuery, Three.js, React 19, TypeScript, Docker | **Deterministic CAD Engine & 3D Web Viewer.** Constructs exact B-Rep solids, enforces physical fabricability invariants, verifies topological mesh quality (watertightness, 2-manifoldness, normal orientation), and exports 5 engineering formats (GLB, glTF, STEP, STL, DXF) with SHA-256 content addressing. 261 automated tests including Hypothesis property-based testing. | [**Open 3D App**](https://parametricad.naindev.com)<br>[Source Code](https://github.com/Nain9Dev/parametricad-ai) |
| **[Microservice Notifications Core](https://github.com/Nain9Dev/Microservicio-Notificaciones)** | .NET 10, C#, MassTransit, RabbitMQ, MailKit, Clean Architecture, Docker | **Sub-50ms Asynchronous Dispatcher.** Decoupled notification microservice built on message queues with dead-letter exchanges, exponential backoff retries, and cluster isolation. | [**Interactive Demo**](https://www.naindev.com/#demo-notificaciones)<br>[Source Code](https://github.com/Nain9Dev/Microservicio-Notificaciones) |
| **[Financial Policy Operations API](https://github.com/Nain9Dev/API-Gestion-Financiera)** | .NET 10, C#, EF Core 10, SQL Server, Clean Architecture, DDD, Azure | **Enterprise Lifecycle Engine.** Manages insurance policy state transitions (`Draft -> Active -> Cancelled`), tenant isolation, and strict optimistic concurrency control via ETags. | [**Live Swagger API**](https://nain-policy-demo-api.azurewebsites.net/demo/)<br>[Source Code](https://github.com/Nain9Dev/API-Gestion-Financiera) |
| **[NainOrder Core API](https://github.com/Nain9Dev/NainOrder)** | .NET 10, C#, EF Core 10, SQL Server, Clean Architecture, CQRS, DDD | **E-Commerce Transactional Core.** Domain-driven order processing engine with CQRS pattern, aggregate boundaries, optimistic locking, and clean architectural separation. | [**Source Code**](https://github.com/Nain9Dev/NainOrder) |
| **[Civil Service Examination Platform (TAI)](https://github.com/Nain9Dev/SistemaOposicionesTAI)** | .NET 10, C#, Dapper, SQL Server, React 19, TypeScript | **High-Throughput Assessment System.** Real-time examination evaluation engine executing official INAP scoring algorithms (+1.0 / -0.33) with sub-10ms query response times and responsive SPA interface. | [**Test Platform**](https://www.naindev.com/SistemaOposicionesTAI/)<br>[Source Code](https://github.com/Nain9Dev/SistemaOposicionesTAI) |
| **[Driving School Financial & Ops Engine](https://github.com/Nain9Dev/Gestion-Autoescuela-Python)** | Python 3.12, Pydantic v2, SQLAlchemy, SQLite, Streamlit | **Operational & Ledger Dashboard.** Business accounting platform with deterministic financial validation, automatic balance reconciliations, and PDF invoice generation. | [**Launch Demo**](https://gestion-autoescuela-nain9dev.streamlit.app/)<br>[Source Code](https://github.com/Nain9Dev/Gestion-Autoescuela-Python) |

> **Note on Commercial Projects:** In addition to public open-source systems, I architect and build proprietary multi-tenant platforms (PostgreSQL, version-concurrency, transactional event sourcing) and multi-domain deterministic conformance engines under private client engagements.

---

## Technical Stack & Tooling

<div align="center">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/.NET_10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET 10" />
  <img src="https://img.shields.io/badge/Python_3.12-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Vue.js_3-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white" alt="Vue 3" />
  <img src="https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white" alt="Astro" />
  <br />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Microsoft_SQL_Server-CC292B?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" alt="SQL Server" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" alt="RabbitMQ" />
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/OpenCASCADE-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="OpenCASCADE" />
</div>

<br />

```text
+-----------------------------------------------------------------------------------+
|                            Presentation & Ingestion                               |
|   Vue 3 / TypeScript | Astro | React 19 (Three.js / WebGL) | OpenAPI / REST       |
+-----------------------------------------+-----------------------------------------+
                                          |
+-----------------------------------------v-----------------------------------------+
|                        Application Orchestration & Ports                          |
|   Spec-Driven Pipelines | Clean Architecture | CQRS Mediators | MassTransit Queues|
+-----------------------------------------+-----------------------------------------+
                                          |
+-----------------------------------------v-----------------------------------------+
|                            Domain Core & Pure Logic                               |
|   Deterministic Conformance       | Boundary Invariants | Pydantic Contracts      |
+-----------------------------------------+-----------------------------------------+
                                          |
+-----------------------------------------v-----------------------------------------+
|                        Infrastructure & External Adapters                         |
|   PostgreSQL (citext/version) | SQL Server | OpenCASCADE | Docker | GitHub Actions  |
+-----------------------------------------------------------------------------------+
```

---

## Methodology & Architectural Principles

1. **Spec-Driven Development (SDD)**: Changes originate in explicit specifications (`charter`, `requirements` in EARS format, `architecture` with Mermaid diagrams, `data-model`, `ADRs`, and `traceability`), never directly in unconstrained code.
2. **Deterministic Quality & Zero Assumptions**: All geometric invariants, market specifications, and business rules are validated by automated property-based test suites. No capability is claimed without reproducible automated verification.
3. **Decoupled Domain Layers**: The presentation layer captures input and renders responses; it never calculates business logic, enforces business invariants, or accesses persistence.
4. **Resilient & Cost-Conscious Infrastructure**: Low-overhead architectures designed for minimal compute footprints, high cache hit rates (content addressing), and horizontal process isolation over unsafe threading.

---

## Contact & Technical Consulting

Available for independent software architecture consulting, enterprise backend engineering, and deterministic computational systems:

- **Portfolio & Case Studies**: [www.naindev.com](https://www.naindev.com/)
- **Email**: [contact@naindev.com](mailto:contact@naindev.com)
- **LinkedIn**: [Aitor Nain Mendoza Vallejo](https://www.linkedin.com/in/aitor-nain-mendoza-vallejo/)
- **GitHub**: [github.com/Nain9Dev](https://github.com/Nain9Dev)
