<div align="center">

# Hi, I'm Taegwan Hong 👋

### Backend Engineer based in Japan 🇯🇵

Building backend systems with a focus on  
**Architecture · Data · Reliability · Automation**

<br>

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

<br>

> From implementing features to understanding  
> the architecture, data, and systems behind them.

</div>

---

## 👨‍💻 About Me

I'm a software engineer based in Japan, primarily focused on **backend engineering**.

I enjoy understanding not only how to make software work, but also why systems are designed the way they are:

- How should responsibilities be separated?
- How should data move through an application?
- How should failures be handled?
- How can a system remain testable and maintainable as it grows?
- How does a technical decision affect the user experience?

I prefer learning technologies by integrating them into real applications and improving those applications through small, reviewable changes.

| | |
|---|---|
| 📍 **Based in** | Japan |
| 🧭 **Core Direction** | Backend Engineering |
| 🔧 **Current Focus** | Architecture · Databases · Testing · Automation |
| 🌍 **Languages** | Korean · Japanese · English · Romanian |
| 🚀 **Growing Toward** | Cloud · Distributed Systems · Applied AI |

---

## 🎯 Current Focus

| Area | Focus |
|---|---|
| **Backend Engineering** | C# · .NET · Java · TypeScript · SQL |
| **Currently Deepening** | Architecture · Database Design · Testing · CI/CD |
| **Expanding Into** | Cloud Infrastructure · Performance · Observability |
| **Exploring** | Distributed Systems · AI-enabled Software |

---

# 🚀 Featured Projects

## 🏗️ Dotnet Backend Study

> Evolving a simple ASP.NET MVC CRUD application into a structured and maintainable backend system.

This project started as a small CRUD application and is being incrementally improved to understand why common backend architecture and infrastructure components are introduced.

### Engineering Focus

`Architecture` · `Persistence` · `Dependency Injection`  
`Testing` · `Error Handling` · `Maintainability`

### Implemented

- Controller → Service → Repository architecture
- Repository abstraction
- Unity Dependency Injection
- Entity Framework 6 and SQL Server persistence
- Code First Migrations
- DTO and Entity separation
- AutoMapper
- Service-layer validation
- Global HTTP 400 / 404 / 500 exception handling
- Application logging with log4net
- MSTest service-layer unit tests
- Vue.js integration

### Recent Engineering Improvement

Implemented server-side pagination with:

- LINQ `OrderByDescending`, `Skip`, and `Take`
- Pagination request and response DTOs
- Total count and pagination metadata
- Invalid parameter and out-of-range handling
- Previous/Next controls in Vue.js
- Boundary and validation tests

Development trail:

[Issue #26](https://github.com/lemonwasp/dotnet-study/issues/26)  
→ [Merged PR #27](https://github.com/lemonwasp/dotnet-study/pull/27)

### Stack

`C#` · `ASP.NET MVC 5` · `.NET Framework 4.8`  
`Entity Framework 6` · `SQL Server` · `Vue.js` · `MSTest`

➡️ [Explore Dotnet Backend Study](https://github.com/lemonwasp/dotnet-study)

---

## 👥 Tsunagaroom

> Helping seniors and their families stay connected through asynchronous video communication.

Tsunagaroom is a Java/JSP team project designed around a simple problem:

**Traditional video calls require both sides to be available at the same time.**

The application instead delivers family videos to senior users and automatically records their reactions during playback.

### Core Experience

```text
Family records a video
        ↓
Senior plays an unread video
        ↓
Camera and microphone recording starts
        ↓
Playback ends
        ↓
Reaction video is uploaded
        ↓
Original video is marked as read
