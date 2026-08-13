<div align="center">

# Hi, I'm Taegwan Hong 👋

### Backend Engineer based in Japan

I build maintainable backend systems by connecting  
**architecture, data flow, reliability, and user needs.**

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

</div>

---

## About Me

I'm a backend-focused software engineer working in Japan.

I care about separating responsibilities, making data flows explicit, handling failures intentionally, and leaving systems easier to test and change.

My current engineering focus includes:

- Designing maintainable backend architecture
- Separating HTTP, business, and persistence responsibilities
- Building reliable data flows with validation and error handling
- Improving software through testing, logging, and automation
- Developing through small Issues, feature branches, and Pull Requests
- Connecting technical decisions to the user problem behind them

Rather than collecting technologies in isolation, I prefer integrating them into working applications and documenting why each engineering decision was made.

---

# Selected Projects

## Dotnet Backend Study

> Evolving a simple ASP.NET MVC CRUD application into a structured and maintainable backend system.

A backend engineering study project that incrementally introduces architectural and reliability improvements into an existing application.

### Engineering Work

- Controller → Service → Repository architecture
- Repository abstraction and Unity Dependency Injection
- Entity Framework 6 and SQL Server persistence
- DTO and Entity separation with AutoMapper
- Service-layer validation
- Global HTTP 400 / 404 / 500 exception handling
- Application logging with log4net
- MSTest service-layer unit tests
- Issue-driven development through feature branches and Pull Requests

### Recent Improvement

Implemented server-side pagination with:

- LINQ `OrderByDescending`, `Skip`, and `Take`
- Pagination request and response DTOs
- Total count and page metadata
- Invalid parameter and out-of-range handling
- Previous/Next controls in Vue.js
- Unit tests for pagination and boundary behavior

Development trail:  
[Issue #26](https://github.com/lemonwasp/dotnet-study/issues/26) → [Merged PR #27](https://github.com/lemonwasp/dotnet-study/pull/27)

### Stack

`C#` · `ASP.NET MVC 5` · `.NET Framework 4.8`  
`Entity Framework 6` · `SQL Server` · `Vue.js` · `MSTest`

➡️ [View Dotnet Backend Study](https://github.com/lemonwasp/dotnet-study)

---

## Tsunagaroom

> Helping seniors and their families stay connected through asynchronous video communication.

Tsunagaroom is a Java/JSP team project that plays unread family videos for senior users and automatically records their reactions during playback.

### Problem and Approach

Traditional video calls require both sides to be available at the same time.

The application instead uses asynchronous videos so family members and senior users can communicate without coordinating a live call.

### My Contributions

- Designed the interaction between video playback and automatic reaction recording
- Structured the Servlet → Logic → DAO processing flow
- Designed unread/read video-state management
- Implemented and reviewed parts of the recording and upload workflow
- Participated in screen, server, and database design
- Coordinated specifications and implementation decisions within the team

This was a team project, and the repository distinguishes my contributions from the work of the full team.

### Stack

`Java 21` · `Jakarta Servlet` · `JSP`  
`JavaScript` · `MySQL 8` · `Apache Tomcat 10`

➡️ [View Tsunagaroom](https://github.com/lemonwasp/tsunagaroom)

---

# Currently Building

## AI Lead Conversion Platform

> A privacy-safe reconstruction of a lead-conversion prototype developed during a 2024 AI hackathon in Ulm, Germany.

The original prototype was created as a team project using corporate data and received a hackathon award.

The current repository is an independent reconstruction using synthetic CRM data. It does not contain the original dataset, proprietary code, internal documents, or credentials.

### Planned System

- Reproducible machine-learning pipeline
- Leakage-safe data splitting and evaluation
- FastAPI prediction and explanation endpoints
- React and TypeScript dashboard
- Human-reviewed LLM-assisted outreach drafts
- Automated testing, Docker, and CI

**Current phase:** repository and safety foundation, including a minimal API health endpoint and automated test.

➡️ [View AI Lead Conversion Platform](https://github.com/lemonwasp/ai-lead-conversion-platform)

---

# Core Technologies

| Area | Technologies |
|---|---|
| **Primary Languages** | C#, Java, TypeScript, JavaScript, Python, SQL |
| **Backend** | ASP.NET MVC, .NET Framework, Entity Framework, JSP/Servlet, NestJS, FastAPI |
| **Databases** | SQL Server, PostgreSQL, PostGIS, MySQL, SQLite |
| **Frontend** | Vue.js, React, Next.js, Razor |
| **Quality** | MSTest, Selenium, validation, exception handling, logging |
| **Infrastructure** | Docker, GitHub Actions, AWS and Azure fundamentals |
| **Workflow** | Git, GitHub, Bitbucket, Issues, feature branches, Pull Requests |
| **Applied AI** | PyTorch, Machine Learning, Azure OpenAI, LangChain |

---

# Global Experience

| Country | Experience |
|---|---|
| 🇯🇵 **Japan** | Software engineering career · Japanese IT environment |
| 🇩🇪 **Germany** | 1-month intensive AI training · Machine Learning, Deep Learning, Azure OpenAI · Hackathon winning team |
| 🇺🇿 **Uzbekistan** | 1-week international internship · Cross-cultural professional experience |
| 🇷🇴 **Romania** | 1-month independent stay · Romanian language learning · Experience adapting to everyday life in Europe |
| 🇰🇷 **Korea** | Software engineering education · Team and personal development projects |

These experiences have strengthened my adaptability and ability to learn and collaborate across different technical and cultural environments.

---

# Languages

| Language | Level |
|---|---|
| 🇰🇷 Korean | Native |
| 🇯🇵 Japanese | Professional working proficiency · JLPT N1 |
| 🇬🇧 English | TOEIC Speaking AL |
| 🇷🇴 Romanian | Beginner · Currently learning |

---

# Current Focus

- Backend architecture and database design
- Automated testing and CI
- Reliability, observability, and performance
- Cloud infrastructure fundamentals
- Applied AI integrated with production-oriented software

---

# Engineering Approach

When introducing a technology or architectural pattern, I try to answer:

> **Why is it needed?**  
> **What problem does it solve?**  
> **Where should it belong?**  
> **What trade-offs does it introduce?**

I prefer small, reviewable improvements over large unexplained rewrites.

My goal is to become an engineer who can connect implementation details with the larger system, the development process, and the user problem behind it.

---

<div align="center">

**Backend Engineering · Reliability · Global Collaboration · Applied AI**

</div>
