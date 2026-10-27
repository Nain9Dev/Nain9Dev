<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg" />
    <img src="assets/banner-light.svg" alt="Aitor Nain Mendoza Vallejo, Arquitecto de Software Full Stack" width="100%" />
  </picture>

  <p>Madrid, España &bull; CTO en <a href="https://github.com/naindev-contrast3d">Contrast3D x NainDev</a></p>

  <p>
    <a href="https://www.naindev.com/"><img src="https://img.shields.io/badge/Portfolio-naindev.com-2563eb?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" /></a>
    <a href="https://www.linkedin.com/in/aitor-nain-mendoza-vallejo/"><img src="https://img.shields.io/badge/LinkedIn-Aitor_Nain-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:contact@naindev.com"><img src="https://img.shields.io/badge/Email-contact@naindev.com-10B981?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email" /></a>
    <a href="https://github.com/naindev-contrast3d"><img src="https://img.shields.io/badge/Org-Contrast3D_x_NainDev-00FFE0?style=for-the-badge&logo=github&logoColor=black" alt="Contrast3D x NainDev" /></a>
  </p>

  <p>
    <a href="README.md"><img src="https://img.shields.io/badge/Language-English-blue.svg" alt="Language: English" /></a>
    <a href="#"><img src="https://img.shields.io/badge/Versi%C3%B3n-Espa%C3%B1ol-red.svg" alt="Versión en Español" /></a>
  </p>
</div>

## Qué construyo

<table>
  <tr>
    <td width="33%" valign="top">
      <b>Backends y APIs</b><br />
      Servicios en Python (FastAPI) y .NET (C#) sobre PostgreSQL o SQL Server, con contratos probados. También mantenimiento y modernización incremental de .NET heredado.
    </td>
    <td width="33%" valign="top">
      <b>Validación determinista</b><br />
      Verificaciones 3D y CAD que ofrecen el mismo veredicto en cada ejecución, con informes reproducibles y herramientas de IA bajo supervisión humana (MCP).
    </td>
    <td width="33%" valign="top">
      <b>Aplicaciones web completas</b><br />
      Interfaces accesibles en Vue 3 y TypeScript (WCAG 2.2 AA), entregadas con Docker e integración continua.
    </td>
  </tr>
</table>

## Arquitectura de sistemas y estándares de ingeniería

Las aplicaciones del portfolio operan como una plataforma integrada de contextos delimitados autónomos (DDD):

- **[Mapa de contextos empresariales y topología](https://github.com/Nain9Dev/engineering-handbook/blob/main/architecture/enterprise-context-map.md)**: Planos de arquitectura C4 Nivel 1/2, enrutamiento asíncrono de eventos de dominio sobre RabbitMQ y contratos de frontera.
- **[Funciones de idoneidad arquitectónica](https://github.com/Nain9Dev/engineering-handbook/blob/main/architecture/fitness-functions.md)**: Verificaciones automatizadas en CI (`NetArchTest` en .NET, inspección AST en Python) que garantizan el aislamiento de capas.
- **[FinOps y modelo de capacidad en producción](https://github.com/Nain9Dev/engineering-handbook/blob/main/architecture/finops-capacity-planning.md)**: Modelado de costes en dos niveles, desde demostración de portfolio a 0,00 EUR hasta producción enterprise de 10k peticiones/min.

## Proyectos destacados

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://parametricad.naindev.com/"><img src="assets/projects/parametricad-ai.jpg" alt="ParametriCAD AI" /></a><br />
      <b>ParametriCAD AI</b><br />
      Motor CAD determinista y visor 3D. Sólidos exactos, validación topológica de mallas y exportación a GLB, STEP y STL.<br />
      <a href="https://parametricad.naindev.com/">Demostración</a> &middot; <a href="https://github.com/Nain9Dev/parametricad-ai">Código</a>
    </td>
    <td width="33%" valign="top">
      <a href="https://3d.naindev.com/"><img src="assets/projects/nain3d.jpg" alt="Demostración de conformidad 3D con IA" /></a><br />
      <b>Demostración de conformidad 3D con IA</b><br />
      Pasarela de validación de modelos 3D con verificaciones a nivel de byte e informes reproducibles.<br />
      <a href="https://3d.naindev.com/">Demostración</a> &middot; <a href="https://github.com/Nain9Dev/Nain3D">Código</a>
    </td>
    <td width="33%" valign="top">
      <a href="https://prospect.naindev.com/"><img src="assets/projects/nainprospect.jpg" alt="NainProspect" /></a><br />
      <b>NainProspect</b><br />
      Pasarela de prospección B2B con categorización por IA y mecanismo de exclusión legal voluntaria (FastAPI, Vue 3).<br />
      <a href="https://prospect.naindev.com/">Demostración</a> &middot; <a href="https://github.com/Nain9Dev/NainProspect">Código</a>
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <a href="https://order.naindev.com/"><img src="assets/projects/nainorder.jpg" alt="NainOrder" /></a><br />
      <b>NainOrder</b><br />
      Motor de pedidos de comercio electrónico basado en Clean Architecture, DDD táctico y CQRS (.NET).<br />
      <a href="https://order.naindev.com/">Demostración</a> &middot; <a href="https://github.com/Nain9Dev/NainOrder">Código</a>
    </td>
    <td width="33%" valign="top">
      <a href="https://notify.naindev.com/"><img src="assets/projects/nainnotify.jpg" alt="NainNotify" /></a><br />
      <b>NainNotify</b><br />
      Envío asíncrono de correos electrónicos con pasarela HTTP desacoplada del worker (.NET, RabbitMQ).<br />
      <a href="https://notify.naindev.com/">Demostración</a> &middot; <a href="https://github.com/Nain9Dev/NainNotify">Código</a>
    </td>
    <td width="33%" valign="top">
      <a href="https://configurator.naindev.com/"><img src="assets/projects/nainconfigurator.jpg" alt="NainConfigurator" /></a><br />
      <b>NainConfigurator</b><br />
      Configurador de productos B2B dirigido por catálogo con aislamiento multi-empresa (ASP.NET Core, React).<br />
      <a href="https://configurator.naindev.com/">Demostración</a> &middot; <a href="https://github.com/Nain9Dev/NainConfigurator">Código</a>
    </td>
  </tr>
</table>

<details>
<summary><b>Más proyectos (10)</b></summary>

| Proyecto | Descripción | Enlaces |
|---|---|---|
| **NainLegacyModernizer** | Arnés de modernización .NET con cero tiempo de inactividad. Proxy inverso Strangler Fig con YARP y ejecución en sombra con doble escritura (.NET 10). | [Código](https://github.com/Nain9Dev/NainLegacyModernizer) |
| **nain-mcp-validator** | Servidor independiente de Model Context Protocol (MCP) para verificaciones deterministas de invariantes de mallas 3D (C1-C10) e identificación por contenido. | [Código](https://github.com/Nain9Dev/nain-mcp-validator) |
| **NainPolicy** | API de ciclo de vida de pólizas con aislamiento por organización y concurrencia optimista (.NET 10, SQL Server, Vue 3). Utiliza datos sintéticos. | [En vivo](https://policy.naindev.com/) &middot; [Código](https://github.com/Nain9Dev/NainPolicy) |
| **NainTAI** | Simulador de exámenes de oposiciones con corrección en servidor y cliente con capacidades offline (.NET 10, PostgreSQL, React 19). | [En vivo](https://tai.naindev.com/) &middot; [Código](https://github.com/Nain9Dev/NainTAI) |
| **NainDrive** | Motor de facturación determinista con aritmética decimal y conciliación exacta (Python, Vue 3). | [En vivo](https://drive.naindev.com/) &middot; [Código](https://github.com/Nain9Dev/NainDrive) |
| **NainWrite** | Entorno de reescritura de texto en español con validación de preservación semántica (TypeScript, Web Workers). | [En vivo](https://write.naindev.com/) &middot; [Código](https://github.com/Nain9Dev/NainWrite) |
| **HaveTickets** | Venta de entradas de cine y reserva de butacas (.NET 10, Blazor WebAssembly). | [En vivo](https://tickets.naindev.com/) &middot; [Código](https://github.com/Nain9Dev/HaveTickets) |
| **GameHaven** | Catálogo de videojuegos independientes modernizado de escritorio a web (.NET 10, Vue 3). | [En vivo](https://gamehaven.naindev.com/) &middot; [Código](https://github.com/Nain9Dev/GameHaven) |
| **Orbe Runner 3D** | Juego de carreras 3D arcade sin motor de videojuegos tradicional (TypeScript, Three.js). | [Jugar](https://orbe.naindev.com/) &middot; [Código](https://github.com/Nain9Dev/Orbe3D) |
| **Pong Arcade 3D** | Juego 3D para navegador con partidas reproducibles (TypeScript, Three.js). | [Jugar](https://pong.naindev.com/) &middot; [Código](https://github.com/Nain9Dev/PongArcade) |

</details>

## Stack tecnológico

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,cs,dotnet,ts,vue,react,tailwind,astro,postgres,docker,githubactions,azure,threejs&amp;perline=14" alt="Python, FastAPI, C#, .NET, TypeScript, Vue, React, Tailwind CSS, Astro, PostgreSQL, Docker, GitHub Actions, Azure, Three.js" />
</p>

<details>
<summary><b>Metodología de trabajo</b></summary>

- **Especificación primero.** Todo cambio comienza en una especificación, nunca directamente en código.
- **Nada afirmado sin una prueba.** Un requisito sin un test que lo demuestre no está terminado.
- **Supervisión humana.** Los agentes de IA actúan mediante herramientas MCP con verificaciones deterministas y aprobación humana, fallando de forma segura (fail-closed) ante la incertidumbre.

</details>

## Contacto

Disponible para proyectos remotos a tiempo parcial en desarrollo de backends y APIs, modernización de .NET heredado y validación determinista.

**[contact@naindev.com](mailto:contact@naindev.com)** &middot; [naindev.com](https://www.naindev.com/) &middot; [LinkedIn](https://www.linkedin.com/in/aitor-nain-mendoza-vallejo/)
