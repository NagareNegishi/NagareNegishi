# Nagare Nagishi
Full-stack Software Engineer with live products.

BSc Computer Science, Victoria University of Wellington (2025). Tutored AI, Data Structures, and Systems Programming. Previously a Software Engineer at Aviat Networks.

## Technical Skills

### Software Engineering
```
Languages:      Java, C#, C/C++, TypeScript/JavaScript, Python
Backend:        ASP.NET Core, EF Core, ASP.NET Identity, Node.js, Express, Hibernate, JDBC
Frontend:       React, React Native, Tailwind, Vite
Database:       PostgreSQL, SQLite
Testing:        JUnit, xUnit, Jest, Vitest, Ceedling, JaCoCo, Valgrind, Moq
DevOps:         AWS (EC2, RDS, S3, ECR), Docker, Dev Containers, Maven, NuGet, GitHub Actions CI/CD, Render, Cloudflare
```
### Game Development
```
Engines:        Unreal Engine 5, Godot
Core Skills:    Game Architecture, Gameplay Programming, UI Development
Multiplayer:    Networking Layer Implementation, Server-Client Systems, Room/Lobby Management
Pipeline:       Asset Integration, Designer Tools & Workflows
```
## Software Development Experience

### Job Application Tracker (2026)
- Full-stack job tracker with JWT auth, refresh token rotation, and JSON Patch partial updates
- ASP.NET Core API with EF Core, ASP.NET Identity, and PostgreSQL
- React + TypeScript frontend with TanStack Query, table and Kanban views with drag-and-drop
- AI auto-fill using Claude API to extract structured job data from pasted listings
- Deployed to AWS (EC2 + Docker Compose, RDS, S3) with GitHub Actions CI/CD (test → build → migrate → deploy)
- Built from scratch while learning C#, then scaled with Claude Code in Dev Containers
- [View Project](https://github.com/NagareNegishi/Job-Application-Tracker)

### Company Verification (2026)
- Published .NET 10 NuGet package that verifies whether a company is registered and active in a country's official business registry
- Adapter-per-country design keeps core logic untouched when a new registry is added, with New Zealand (NZBN) and Australia (ABR) built in
- Normalized response shape across registries, with third-party adapters declaring their own conformance rules
- Shared core consumed as a class library and an HTTP API, structured so an MCP server can sit on the same core
- Government-registry integration with credential handling, registry-specific filtering, and MBIE attribution compliance
- [View Project](https://github.com/NagareNegishi/company-verification)
- [NuGet](https://www.nuget.org/packages/CompanyVerification.Core)
- [Demo query](https://company-verification.onrender.com/verify?name=Spark%20New%20Zealand&country=NZ) returns live JSON from the NZ register (Render free tier, first request may take 30–60s to wake)

### Pantry2Plate (2026)
- AI-powered recipe generator using Claude API with ingredient and dietary preference matching
- TypeScript monorepo with shared validation types across Express backend, React web, and React Native mobile
- Docker Compose deployment with GitHub Actions CI/CD, Jest and Vitest testing
- [View Project](https://github.com/NagareNegishi/Pantry2Plate)
- [Demo](http://nagarenegishi.com/Pantry2Plate/)

### Distributed Logging System (2025)
- Logging infrastructure with custom Log4j HTTP appender and REST API
- Database persistence with Hibernate/JPA, supporting H2 and external databases
- Integrated JMX monitoring, transaction management, and multi-format export(CSV/HTML/Excel)
- [View Project](https://github.com/NagareNegishi/Distributed-Logging-System)
  
### Coffee Finder (2025)
- Location-based web application using JavaScript, HTML/CSS, and Supabase (PostgreSQL)
- Implemented geolocation services, interactive mapping, and external API integration
- Created custom SQL functions for geospatial queries and distance calculations
- [View Project](https://github.com/NagareNegishi/Coffee-Finder)
- [Demo](https://nagarenegishi.com/Coffee-Finder/)

### SWEN225 Project (2024)
- Robust system architecture using design patterns
- Developed UI controller and data persistence layers in Java
- Practiced agile development in 6-person team environment
- Focused on code maintainability and system scalability
- [View Project](https://github.com/NagareNegishi/LarryCroftsAdventures)

### Technical Expertise
- Full-stack architecture with stateless JWT auth and token rotation
- Test-driven development across Java, C#, C, and TypeScript
- Legacy system analysis with static analysis and memory profiling
- AI-assisted development workflows with Claude Code and Dev Containers
- Monorepo architecture with shared types across web and mobile

## 🎮 Project Portfolio
Practical application of software engineering principles through game development:
- ChopChopServe - Competitive multiplayer cooking game featuring real-time network synchronization and interaction systems | [Code](https://github.com/NagareNegishi/ChopChopServe-Public)
- Goblins' Fury - Tower defense with dynamic difficulty system and modular architecture | [Code](https://github.com/NagareNegishi/Tower-Defense-CGRA252)
- OpenGL Graphics Programming - Rendering fundamentals and techniques: [Ray Tracing](https://github.com/NagareNegishi/OpenGL-Ray-tracing) | [Boids Simulation](https://github.com/NagareNegishi/OpenGL-Boids) | [Geometry & Color](https://github.com/NagareNegishi/OpenGl-Geometry-and-colour) | [Transformations & Shading](https://github.com/NagareNegishi/OpenGl-Transformations-and-shading)
- Bar'acuda - Interactive service management simulation (48hr Game Jam)| [Play](https://games-for-people.itch.io/baracuda) · [Code](https://github.com/NagareNegishi/GGJ-Bar-acuda)
- 1 Fuji 2 Hawk 3 Nasubi - Top-down competitive collector with AI-controlled entities (48hr Game Jam)| [Play](https://negimakushi.itch.io/1-fuji-2-hawk-3-nasubi) · [Code](https://github.com/NagareNegishi/Game-jam2)
- 7 Korobi 8 Oki - Platformer with memory-based progression (48hr Game Jam)| [Play](https://negimakushi.itch.io/7-korobi-8-oki)

## 🗣️ Languages
- Japanese (Native)
- English (Fluent)

## 📫 Contact
- 📧 [negishinaga@gmail.com](mailto:negishinaga@gmail.com)
- 🌐 [nagarenegishi.com](https://nagarenegishi.com)
- 💼 [LinkedIn](https://linkedin.com/in/nagare-negishi)
- 🌏 Auckland, New Zealand
