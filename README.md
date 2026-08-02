# ⚡ Aitor Nain Mendoza Vallejo — Backend & API Solutions (.NET | Python)
**Madrid, España 🇪🇸 | Desarrollador Backend & Consultor de Software de Negocio**

[![Web Portfolio](https://img.shields.io/badge/Portafolio_Oficial-naindev.com-2563eb?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.naindev.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aitor_Nain-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aitor-nain-mendoza-vallejo/)
[![Email](https://img.shields.io/badge/Contacto_Directo-contact@naindev.com-10B981?style=for-the-badge&logo=mail.ru&logoColor=white)](mailto:contact@naindev.com)

---

## 🎯 Objetivo y Propuesta de Valor

> **Trabajo principalmente con APIs, lógica de negocio y bases de datos. En este portfolio comparto proyectos personales y demos que muestran lo que sé hacer y lo que sigo aprendiendo.**
> Mi objetivo principal es ayudar a empresas, startups y profesionales a **construir, escalar y refactorizar software de negocio los fines de semana**, asegurando máxima calidad arquitectónica, persistencia robusta y código fácil de mantener y evolucionar.

### 💼 Especialidades para Proyectos y Consultoría de Fin de Semana:
* 🛠️ **Desarrollo y Arquitectura de APIs REST (.NET 10 & Python 3.12):** Diseño por contrato, JWT, observabilidad, control de concurrencia avanzado (ETag, `rowversion`) y versionado seguro.
* 🏛️ **Clean Architecture & Domain-Driven Design (DDD):** Refactorización de código heredado, eliminación de deuda técnica y separación estricta entre dominio y capas de infraestructura (EF Core 10, Dapper, SQLAlchemy).
* 💾 **Optimización de Bases de Datos (SQL Server & SQLite):** Consultas T-SQL de alto rendimiento, índices, procedimientos almacenados, auditoría y aislamiento multitenant.
* ⚡ **Integraciones Cloud & Asíncronas (Coste 0€ / Bajo Coste):** Implementación de microservicios desatendidos (Workers), colas de mensajería (RabbitMQ / CloudAMQP) y despliegues eficientes en Azure App Service, Streamlit Cloud y GitHub Pages.

---

## 🚀 Escaparate de Proyectos & Demos en Vivo (1-Clic)

Todos mis desarrollos se construyen bajo la premisa de la **evidencia verificable**. Ningún proyecto requiere descargas complejas ni configuraciones locales; puedes probarlos en tiempo real sobre la nube o revisar su arquitectura directamente:

| Proyecto / Dominio | Stack Técnico | Estado & Evidencia | Acceso Rápido (1-Clic) |
| :--- | :--- | :--- | :--- |
| 🛡️ **[API de Operaciones de Pólizas](https://github.com/Nain9Dev/API-Gestion-Financiera)** | `.NET 10` `EF Core 10` `SQL Server` `Clean Architecture` `Azure` | **Demo HTTPS en vivo.** Gestión del ciclo `Draft -> Active -> Cancelled`, aislamiento por organización y control de concurrencia ETag. | [**▶ Probar API en Azure**](https://nain-policy-demo-api.azurewebsites.net/demo/)<br>[📁 Ver Repositorio](https://github.com/Nain9Dev/API-Gestion-Financiera) |
| ⚡ **[Servicio de Notificaciones Cloud](https://github.com/Nain9Dev/Microservicio-Notificaciones)** | `.NET 10` `MassTransit` `RabbitMQ (CloudAMQP)` `MailKit` | **Simulación en vivo.** Microservicio desacoplado conectando a clúster RabbitMQ con procesamiento en <350ms y despacho de emails HTML. | [**▶ Abrir Demo Web**](https://www.naindev.com/#demo-notificaciones)<br>[📁 Ver Repositorio](https://github.com/Nain9Dev/Microservicio-Notificaciones) |
| 🏛️ **[Sistema Oposiciones TAI](https://github.com/Nain9Dev/SistemaOposicionesTAI)** | `.NET 10` `Dapper` `T-SQL Stored Procedures` `SPA Responsive` | **Demo Interactiva.** Plataforma de estudio real con cronómetro de examen INAP, baremo oficial (+1/-0,33) y analítica en `localStorage` (0€ coste). | [**▶ Probar App en Vivo**](https://www.naindev.com/SistemaOposicionesTAI/)<br>[📁 Ver Repositorio](https://github.com/Nain9Dev/SistemaOposicionesTAI) |
| 🚗 **[Gestión Autoescuela NainDev](https://github.com/Nain9Dev/Gestion-Autoescuela-Python)** | `Python 3.12` `Pydantic v2` `Streamlit` `SQLAlchemy` `SQLite` | **Demo Web 24/7.** Dashboard contable y operativo para autoescuelas. Imputa clases, calcula saldos y emite facturas oficiales descargables en PDF. | [**▶ Probar Demo en Cloud**](https://gestion-autoescuela-nain9dev.streamlit.app/)<br>[📁 Ver Repositorio](https://github.com/Nain9Dev/Gestion-Autoescuela-Python) |
| 🕹️ **[Pong Arcade Canvas](https://www.naindev.com/pong-game/)** | `HTML5` `Vanilla CSS` `JavaScript` `Canvas API` | **Juego en Navegador.** Prototipo dinámico con físicas en tiempo real, múltiples niveles de IA y modo local para dos jugadores. | [**▶ Jugar en Navegador**](https://www.naindev.com/pong-game/)<br>[📁 Ver Código](https://github.com/Nain9Dev/nain9dev.github.io/tree/main/pong-game) |

---

## 🛠️ Stack Arquitectónico y Tecnologías

```text
       ┌───────────────────────────────┐
       │   APIs & Aplicaciones Web     │ ── ASP.NET Core 10 | Python FastAPI / Streamlit | Vanilla Web
       └───────────────┬───────────────┘
                       ▼
       ┌───────────────────────────────┐
       │   Capa de Dominio & Negocio   │ ── Clean Architecture | DDD | Pydantic v2 | Patrón de Contratos
       └───────────────┬───────────────┘
                       ▼
       ┌───────────────────────────────┐
       │  Persistencia & Asincronía    │ ── SQL Server (T-SQL) | SQLite | EF Core 10 | Dapper | RabbitMQ
       └───────────────────────────────┘
```

---

## 🤝 ¿Tienes una idea o un backend que mejorar este fin de semana?

Si buscas un desarrollador confiable para impulsar una funcionalidad crítica, optimizar consultas pesadas en SQL Server o construir desde cero el cerebro relacional de tu producto con código limpio e insustituible, escríbeme y revisamos el alcance en un brief rápido de 30 minutos:

* 🌐 **Portafolio Interactivo:** [www.naindev.com](https://www.naindev.com/)
* 📧 **Correo Electrónico:** [contact@naindev.com](mailto:contact@naindev.com)
* 💼 **LinkedIn:** [Aitor Nain Mendoza Vallejo](https://www.linkedin.com/in/aitor-nain-mendoza-vallejo/)
