<div align="center">

# Ahmed Shahine

### Backend-Focused Full-Stack .NET Engineer

**Production Systems · Architecture · Performance · Data**

[Portfolio](https://ahmedshahine1.github.io) · [Resume](https://ahmedshahine1.github.io/resume.html) · [LinkedIn](https://linkedin.com/in/ahmed-hani-804120205)

**Production systems · Architecture · Performance · Data · Product Engineering**

[![Portfolio](https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=googlechrome&logoColor=white)](https://ahmedshahine1.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ahmed-hani-804120205)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AhmedShahine1)

</div>

---

## `01` Profile

I'm a software engineer specializing in **ASP.NET Core, Angular, SQL Server, and multi-tenant SaaS systems**. I enjoy working on products where backend architecture, frontend experience, data design, performance, and business workflows all matter.

My work is centered around building maintainable production systems: clear module boundaries, reliable APIs, real-time workflows, secure access control, database performance, and pragmatic engineering decisions.

I graduated in **2024** from **Cairo University — Faculty of Computers and Artificial Intelligence (FCAI)**, specializing in **Decision Support (Operations Research & Decision Support)**. I'm currently continuing postgraduate study in **Information Systems / Business Computing Analysis** while building a parallel path toward **Machine Learning and AI Engineering**.

---

## `02` Production Impact

<table>
<tr>
<td align="center"><b>~60s → &lt;2s</b><br><sub>checkout pipeline</sub></td>
<td align="center"><b>−45%</b><br><sub>p95 API latency</sub></td>
<td align="center"><b>3×</b><br><sub>concurrent load</sub></td>
</tr>
<tr>
<td align="center"><b>20k+</b><br><sub>monthly active users</sub></td>
<td align="center"><b>99%+</b><br><sub>uptime</sub></td>
<td align="center"><b>−35%</b><br><sub>post-release bugs</sub></td>
</tr>
</table>

---

## `03` Engineering Stack

| Layer | Technologies |
|---|---|
| **Backend** | C# · ASP.NET Core · EF Core · Dapper · MediatR · SignalR |
| **Architecture** | Clean Architecture · CQRS · Modular Design · Multi-tenant SaaS |
| **Data & Messaging** | SQL Server · Query Tuning · Indexing · Redis · RabbitMQ |
| **Frontend** | Angular 15–18 · TypeScript · RxJS · NgRx · Blazor Server |
| **Delivery** | AWS S3 · Firebase · Docker · GitHub Actions · CI/CD · Unit Testing |

<details>
<summary><b>Technology badges</b></summary>
<br>

![C#](https://img.shields.io/badge/C%23-111827?style=flat-square&logo=csharp&logoColor=38BDF8)
![.NET](https://img.shields.io/badge/.NET-111827?style=flat-square&logo=dotnet&logoColor=38BDF8)
![Angular](https://img.shields.io/badge/Angular-111827?style=flat-square&logo=angular&logoColor=38BDF8)
![TypeScript](https://img.shields.io/badge/TypeScript-111827?style=flat-square&logo=typescript&logoColor=38BDF8)
![SQL Server](https://img.shields.io/badge/SQL_Server-111827?style=flat-square&logo=microsoftsqlserver&logoColor=38BDF8)
![Redis](https://img.shields.io/badge/Redis-111827?style=flat-square&logo=redis&logoColor=38BDF8)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-111827?style=flat-square&logo=rabbitmq&logoColor=38BDF8)
![Docker](https://img.shields.io/badge/Docker-111827?style=flat-square&logo=docker&logoColor=38BDF8)

</details>

---

## `04` What I Engineer

- **Enterprise SaaS** — tenant isolation, configuration, auditability, permissions, and operational workflows.
- **Backend architecture** — modular monoliths, Clean Architecture, CQRS, service/repository boundaries, EF Core and Dapper.
- **Performance engineering** — query tuning, indexing, batching, caching, and latency reduction.
- **Real-time systems** — SignalR, notifications, event-driven workflows, and background processing.
- **Frontend engineering** — Angular, RxJS, NgRx, reusable UI architecture, state management, and responsive enterprise UX.
- **AI engineering** — building toward practical ML/AI systems that integrate cleanly with production software.

---

## `05` Engineering Stories

### Enterprise CAFM Platform
End-to-end engineering across operational workflows including assets, PPM, work orders, attendance, access control, purchasing, materials, vendors, visitors, spare parts, and document management.

### Direct-to-S3 Document Management
Designed the upload flow as: **Angular → .NET metadata validation → pre-signed URL → direct S3 upload → confirm + persist**. This reduces unnecessary application-server load while keeping authorization and metadata rules in the backend.

### Multi-Tenant Performance Engineering
Redesigned a high-cost checkout path using async refactoring, Redis caching, and query batching: **~60 seconds → under 2 seconds**, alongside tenant-isolated audit logging through MediatR pipeline behaviors.

## `06` Public Code

- **[Maintainify](https://github.com/AhmedShahine1/Maintainify)** — public project available for direct code review.
- **[Backend Developer Assessment](https://github.com/AhmedShahine1/BackEndDevTest)** — ASP.NET Core, EF Core, SQL Server, SignalR, transactions, Angular, and real-time workflows.
- **[System Design Resources](https://github.com/AhmedShahine1/system-design-resources)** — architecture and system-design reference collection.

> Most of my strongest production work belongs to employer/private repositories. The case studies above describe the engineering problems and outcomes without exposing proprietary source code.

---

## `07` Experience

**Full-Stack .NET Developer — CAFM-IMS**  
*Jan 2025 – Present*

- Build and evolve enterprise facility-management modules across .NET, Angular, and SQL Server.
- Improved hot-path performance using Dapper and query-level optimization.
- Apply stronger architectural boundaries to improve maintainability and delivery quality.

**Backend .NET Developer — MasdSoft**  
*Oct 2025 – Mar 2026 · Part-time*

- Redesigned a multi-tenant checkout pipeline from roughly **60 seconds to under 2 seconds**.
- Built tenant-isolated audit logging across multiple clients.
- Reduced p95 API latency by **45%** under significantly higher load.

**Full-Stack .NET Developer — OX Tech.co**  
*Aug 2024 – Apr 2025*

- Worked on systems serving **20,000+ monthly active users**.
- Built real-time functionality with SignalR.
- Integrated payment workflows with reliability and idempotency considerations.

---

## `08` Engineering Principles

> **Design for change. Measure performance. Protect boundaries. Keep business rules explicit.**

I prefer systems that are:

- modular before they are distributed,
- observable before they are optimized,
- explicit about permissions and tenant boundaries,
- designed around business workflows rather than framework conventions,
- and simple enough for the next engineer to understand.

---

## `09` Current Direction

- Deepening **backend architecture, distributed systems, databases, cloud, and system design**.
- Developing a second specialization in **Machine Learning / AI Engineering**.
- Continuing to improve as a backend-focused full-stack software engineer.

---

<div align="center">

### Let's Connect

I'm interested in **software engineering, SaaS architecture, backend systems, AI engineering, and product development**.

[Portfolio](https://ahmedshahine1.github.io) · [LinkedIn](https://linkedin.com/in/ahmed-hani-804120205) · [GitHub](https://github.com/AhmedShahine1)

</div>
