<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg" />
    <img src="assets/banner-light.svg" alt="Aitor Nain Mendoza Vallejo, Full Stack Software Architect" width="100%" />
  </picture>

  <p>Madrid, Spain &bull; CTO at <a href="https://github.com/naindev-contrast3d">Contrast3D x NainDev</a></p>

  <p>
    <a href="https://www.naindev.com/"><img src="https://img.shields.io/badge/Portfolio-naindev.com-2563eb?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" /></a>
    <a href="https://www.linkedin.com/in/aitor-nain-mendoza-vallejo/"><img src="https://img.shields.io/badge/LinkedIn-Aitor_Nain-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:contact@naindev.com"><img src="https://img.shields.io/badge/Email-contact@naindev.com-10B981?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email" /></a>
    <a href="https://github.com/naindev-contrast3d"><img src="https://img.shields.io/badge/Org-Contrast3D_x_NainDev-00FFE0?style=for-the-badge&logo=github&logoColor=black" alt="Contrast3D x NainDev" /></a>
  </p>

  <p>
    <a href="#"><img src="https://img.shields.io/badge/Language-English-blue.svg" alt="Language: English" /></a>
    <a href="README.es.md"><img src="https://img.shields.io/badge/Versi%C3%B3n-Espa%C3%B1ol-red.svg" alt="Versión en Español" /></a>
  </p>
</div>

## What I build

<table>
  <tr>
    <td width="33%" valign="top">
      <b>Backends and APIs</b><br />
      Python (FastAPI) and .NET (C#) services on PostgreSQL or SQL Server, with tested contracts. Also maintenance and incremental modernization of legacy .NET.
    </td>
    <td width="33%" valign="top">
      <b>Deterministic validation</b><br />
      3D and CAD checks that give the same verdict every time, with reproducible reports and AI tools that work under human oversight (MCP).
    </td>
    <td width="33%" valign="top">
      <b>Complete web apps</b><br />
      Accessible Vue 3 and TypeScript frontends (WCAG 2.2 AA), delivered with Docker and continuous integration.
    </td>
  </tr>
</table>

## System Architecture & Engineering Standards

The portfolio applications operate as an integrated platform of autonomous Bounded Contexts (DDD):

- **[Enterprise Context Map & Topology](https://github.com/Nain9Dev/engineering-handbook/blob/main/architecture/enterprise-context-map.md)**: C4 Level 1/2 architectural blueprints, asynchronous domain event routing over RabbitMQ, and boundary contracts.
- **[Architectural Fitness Functions](https://github.com/Nain9Dev/engineering-handbook/blob/main/architecture/fitness-functions.md)**: Automated CI checks (`NetArchTest` in .NET, AST inspection in Python) enforcing layer boundary isolation.
- **[FinOps & Production Capacity Model](https://github.com/Nain9Dev/engineering-handbook/blob/main/architecture/finops-capacity-planning.md)**: Two-tier cost modeling from 0,00 EUR portfolio demonstration to 10k req/min enterprise production.

## Featured projects

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://parametricad.naindev.com/"><img src="assets/projects/parametricad-ai.jpg" alt="ParametriCAD AI" /></a><br />
      <b>ParametriCAD AI</b><br />
      Deterministic CAD engine and 3D viewer. Exact solids, mesh topology checks, GLB, STEP and STL export.<br />
      <a href="https://parametricad.naindev.com/">Live demo</a> &middot; <a href="https://github.com/Nain9Dev/parametricad-ai">Code</a>
    </td>
    <td width="33%" valign="top">
      <a href="https://3d.naindev.com/"><img src="assets/projects/nain3d.jpg" alt="3D AI Conformance Demo" /></a><br />
      <b>3D AI Conformance Demo</b><br />
      3D asset validation gateway with byte-level checks and reproducible reports.<br />
      <a href="https://3d.naindev.com/">Live demo</a> &middot; <a href="https://github.com/Nain9Dev/Nain3D">Code</a>
    </td>
    <td width="33%" valign="top">
      <a href="https://prospect.naindev.com/"><img src="assets/projects/nainprospect.jpg" alt="NainProspect" /></a><br />
      <b>NainProspect</b><br />
      B2B prospecting gateway with AI categorization and a legal opt-out gate (FastAPI, Vue 3).<br />
      <a href="https://prospect.naindev.com/">Live demo</a> &middot; <a href="https://github.com/Nain9Dev/NainProspect">Code</a>
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <a href="https://order.naindev.com/"><img src="assets/projects/nainorder.jpg" alt="NainOrder" /></a><br />
      <b>NainOrder</b><br />
      E-commerce order engine on Clean Architecture, tactical DDD and CQRS (.NET).<br />
      <a href="https://order.naindev.com/">Live demo</a> &middot; <a href="https://github.com/Nain9Dev/NainOrder">Code</a>
    </td>
    <td width="33%" valign="top">
      <a href="https://notify.naindev.com/"><img src="assets/projects/nainnotify.jpg" alt="NainNotify" /></a><br />
      <b>NainNotify</b><br />
      Asynchronous email dispatch with the HTTP gateway separated from the worker (.NET, RabbitMQ).<br />
      <a href="https://notify.naindev.com/">Live demo</a> &middot; <a href="https://github.com/Nain9Dev/NainNotify">Code</a>
    </td>
    <td width="33%" valign="top">
      <a href="https://configurator.naindev.com/"><img src="assets/projects/nainconfigurator.jpg" alt="NainConfigurator" /></a><br />
      <b>NainConfigurator</b><br />
      Catalog-driven B2B product configurator with multi-company isolation (ASP.NET Core, React).<br />
      <a href="https://configurator.naindev.com/">Live demo</a> &middot; <a href="https://github.com/Nain9Dev/NainConfigurator">Code</a>
    </td>
  </tr>
</table>

<details>
<summary><b>More projects (10)</b></summary>

| Project | What it is | Links |
|---|---|---|
| **NainLegacyModernizer** | Zero-downtime legacy .NET modernization harness. Strangler Fig reverse proxying via YARP with dual-write shadow running (.NET 10). | [Code](https://github.com/Nain9Dev/NainLegacyModernizer) |
| **nain-mcp-validator** | Standalone Model Context Protocol (MCP) server for deterministic 3D mesh invariant checks (C1-C10) and content addressing. | [Code](https://github.com/Nain9Dev/nain-mcp-validator) |
| **NainPolicy** | Policy lifecycle API with per-organization isolation and optimistic concurrency (.NET 10, SQL Server, Vue 3). Uses synthetic data. | [Live](https://policy.naindev.com/) &middot; [Code](https://github.com/Nain9Dev/NainPolicy) |
| **NainTAI** | Civil service exam simulator with server-side marking and an offline-capable client (.NET 10, PostgreSQL, React 19). | [Live](https://tai.naindev.com/) &middot; [Code](https://github.com/Nain9Dev/NainTAI) |
| **NainDrive** | Deterministic billing engine with decimal arithmetic that reconciles exactly (Python, Vue 3). | [Live](https://drive.naindev.com/) &middot; [Code](https://github.com/Nain9Dev/NainDrive) |
| **NainWrite** | Spanish text rewriting workbench with semantic preservation checks (TypeScript, Web Workers). | [Live](https://write.naindev.com/) &middot; [Code](https://github.com/Nain9Dev/NainWrite) |
| **HaveTickets** | Cinema ticketing and seat reservation (.NET 10, Blazor WebAssembly). | [Live](https://tickets.naindev.com/) &middot; [Code](https://github.com/Nain9Dev/HaveTickets) |
| **GameHaven** | Indie game storefront modernized from a desktop app to the web (.NET 10, Vue 3). | [Live](https://gamehaven.naindev.com/) &middot; [Code](https://github.com/Nain9Dev/GameHaven) |
| **Orbe Runner 3D** | 3D arcade runner without a game engine (TypeScript, Three.js). | [Play](https://orbe.naindev.com/) &middot; [Code](https://github.com/Nain9Dev/Orbe3D) |
| **Pong Arcade 3D** | Browser 3D game with reproducible matches (TypeScript, Three.js). | [Play](https://pong.naindev.com/) &middot; [Code](https://github.com/Nain9Dev/PongArcade) |

</details>

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,cs,dotnet,ts,vue,react,tailwind,astro,postgres,docker,githubactions,azure,threejs&amp;perline=14" alt="Python, FastAPI, C#, .NET, TypeScript, Vue, React, Tailwind CSS, Astro, PostgreSQL, Docker, GitHub Actions, Azure, Three.js" />
</p>

<details>
<summary><b>How I work</b></summary>

- **Spec first.** Every change starts in a specification, never directly in code.
- **Nothing claimed without a test.** A requirement without a test that proves it is not done.
- **Human in the loop.** AI agents act through MCP tools with deterministic checks and human approval, and fail closed when unsure.

</details>

## Work with me

Open to part-time, remote projects in backend and API development, legacy .NET modernization and deterministic validation.

**[contact@naindev.com](mailto:contact@naindev.com)** &middot; [naindev.com](https://www.naindev.com/) &middot; [LinkedIn](https://www.linkedin.com/in/aitor-nain-mendoza-vallejo/)
