# Inventory Management System (Blazor / .NET 10)

**Inventory Management System** — a full-stack single-page web application built with **Blazor (ASP.NET Core Blazor, .NET 10)**, using Clean Architecture and Use-Case Driven Development.  
This project demonstrates modern Microsoft-stack development for internal business systems: server-side Blazor, EF Core, ASP.NET Core Identity, plugin-based repositories (In-Memory + EF Core), and a testable, SOLID codebase.

---

## Key Features

- Blazor Server-side rendering (Static SSR + Interactive SSR)
- Razor / Blazor components and reusable UI modules
- Forms submission, client + server validation
- Custom validation using `ValidationAttribute`
- Authentication & Authorization with ASP.NET Core Identity
- Policy-based authorization
- Dependency Injection (built-in .NET DI)
- Clean Architecture (Domain / Use Cases / Plugins / WebApp)
- Repository pattern with plugin support:
  - `InMemory` plugin for quick testing
  - `EF Core (SQL Server)` plugin for production
- Entity Framework Core + SQL Server
- Use-case driven service layer for separable business logic
- Example monitoring / utilities-ready code for enterprise usage

---

## Technology Stack

- .NET 10 (C#)
- ASP.NET Core Blazor (Server-side)
- Entity Framework Core (SQL Server)
- ASP.NET Core Identity
- Bootstrap (UI scaffolding)
- GitLab / Git for source control
- Docker / IIS / Hyper-V (optional deployment targets)

---

## Repository Structure (high-level)

