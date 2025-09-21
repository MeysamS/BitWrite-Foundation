# BitWrite.Foundation

**BitWrite.Foundation** is a lightweight yet powerful framework built on **.NET 9**, designed for **modular microservices architectures** with full support for **Domain-Driven Design (DDD)** and **CQRS** patterns.

It provides a clean, opinionated foundation to help developers build scalable, maintainable, and testable distributed systems with ease.

### ✨ Key Features

* **DDD-Ready Architecture** – Clear separation of concerns across Domain, Application, Infrastructure, and API layers.
* **CQRS Support** – Command & Query separation with built-in integration for [BwCqrs](https://github.com/MeysamS/BwCqrs).
* **Microservices Friendly** – Modular structure with support for service isolation, messaging, and outbox patterns.
* **Modern Dev Experience** – Ready-to-use templates (`dotnet new`) for rapid service scaffolding.
* **Observability & Security** – Integrated logging, tracing, metrics, and authentication/authorization best practices.
* **Automated Backlog Management** – GitHub Action automatically imports `.github/backlog.yml` into Issues with Epic, Feature, Milestone, and Labels.

### 🚀 Goals

* Provide a **solid foundation** for enterprise-grade microservices.
* Simplify **CQRS + DDD adoption** without extra complexity.
* Enable teams to focus on **business logic**, not boilerplate code.

### 📂 Backlog & Automation

The backlog of features, improvements, and tasks is defined in `.github/backlog.yml`.  
A GitHub Action (`.github/workflows/import-backlog.yml`) automatically creates Issues from the backlog whenever it is updated.  
- Prevents duplicate Issues
- Maintains Epic, Feature, Milestone, and Labels
- Supports full modular and event-driven architecture

### 💡 Contribution

BitWrite.Foundation is still evolving. Contributions, feedback, and ideas are welcome!
