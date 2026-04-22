<p align="center">
    <a href="#"><img width="60%" height="auto" src="https://c.tenor.com/NOYF3f82b_gAAAAC/programmer.gif"/></a>
    <h1 align="center">Hi, I'm Mayank Gupta 👋</h1>
    <h3 align="center">Senior Backend Engineer from India 🇮🇳</h3>
</p>

**Distributed Systems · Java · Spring Boot · Kafka · Microservices · Payments**

Backend engineer with 4+ years building high-availability, high-throughput systems in fintech and enterprise automation. I design for scale, own outcomes end-to-end, and ship with measurable impact.

📍 Bengaluru, India · [LinkedIn](https://linkedin.com/in/mayanksystems) · [Portfolio](https://mayankgupta-portfolio.vercel.app/) · [Email](mailto:ce.mayank8@gmail.com)

---

## 🏗️ What I Build

Systems that handle real load with real consequences:

- **PCI-DSS Token Vault** @ PayU — card tokenization/detokenization microservices across 50+ merchant integrations, targeting 99.99% uptime on Kubernetes
- **Enterprise Job Orchestration** @ HCLSoftware — Kafka-driven event infrastructure processing **150K+ events/day** with zero message loss
- **HDFC Bank EOD Reporting** — SQL optimization reducing report generation **25 min → < 5 min (80% faster)** via composite indexes, materialized views, and CTE rewrites on 12M-row Oracle tables
- **Oracle → PostgreSQL Migration** — 200+ tables migrated using Hibernate dialect abstraction; expanded SQL compatibility by 40% with zero application rewrites for 95% of queries
- **CI/CD Overhaul** — Jenkins + Docker pipeline shrinking deployment time **120 min → 20 min (6×)**; multi-stage Docker cut image size 75% (600MB → 145MB)

---

## 💻 Tech Stack

**Languages** · Java 17+ · Python · SQL · Bash

**Backend** · Spring Boot · Spring Cloud · Spring Security · Spring Data JPA · Hibernate · OAuth2 / JWT · REST APIs · Resilience4j

**Messaging** · Apache Kafka · Event-Driven Architecture · Dead Letter Topics · Kafka Streams

**Databases** · PostgreSQL · MySQL · Oracle SQL · MongoDB · Redis · H2

**Cloud & Infra** · AWS (EC2, RDS, S3, EKS) · Docker · Kubernetes · Jenkins · CI/CD · Prometheus · Grafana · Liquibase

**Practices** · Microservices · Distributed Systems · TDD · SOLID · System Design (HLD/LLD) · Agile/Scrum

---

## 🚀 Featured Projects

### [Finvista Nexus](https://github.com/mayankSystems/finvista-nexus) — Cloud-Native Banking Platform
🏷️ *Spring Boot · Spring Cloud · MySQL · Docker · OAuth2 · Spring Security · JUnit 5*

Full microservices banking platform with three domain services (Accounts, Loans, Cards), API Gateway, and Config Server.

- **OAuth2 Authorization Code** flow for user authentication; **Client Credentials** for service-to-service calls — no user credentials ever touch downstream services
- JWT validation at the gateway layer; method-level `@PreAuthorize` per endpoint
- Containerized via Docker Compose; images on Docker Hub; full Swagger/OpenAPI documentation
- **95%+ test coverage** via JUnit 5 + Mockito + Testcontainers

> Key engineering decision: used Spring Cloud Gateway as the single entry point — all inter-service OAuth2 token exchange is internal, keeping the surface area for auth vulnerabilities minimal.

---

### [Project Chess](https://github.com/mayankSystems/project-chess) — Chess Engine in Java
🏷️ *Java · Swing/AWT · OOP · Strategy / Factory / Observer Patterns · SOLID*

Complete chess engine with GUI, full rule enforcement, and clean domain design.

- **Strategy pattern** per piece type — each piece implements its own `canMoveTo()` rule; the board calls the piece's strategy, no switch/case in game logic
- Check detection: tests all possible moves post-move to verify king safety
- Full coverage: check, checkmate, stalemate, castling, en passant, pawn promotion
- Clean separation between game domain logic and Swing presentation layer

---

## 🎯 Career Highlights

**PayU Digital Labs** — Software Engineer *(Mar 2026 – Present)*
- Architecting fault-tolerant token lifecycle microservices (tokenization / detokenization / revocation) for PCI-DSS Token Vault across 50+ merchant integrations
- Designing Kafka event-driven payment infrastructure on Kubernetes with horizontal pod autoscaling — targeting 99.99% uptime SLA
- Hardening observability via Prometheus + Grafana; reducing MTTR by 40%

**HCLSoftware** — Senior Software Engineer *(Aug 2022 – Mar 2026)*
- Delivered 10+ production REST APIs serving **50,000+ daily transactions at 99.95% uptime**
- Led 5-engineer team to re-architect HDFC Bank's EOD reporting pipeline — **80% faster** generation, eliminated overnight SLA breaches
- Built Kafka event-driven orchestration automating 100% of manual job triggers — **3× throughput (150K+ events/day), zero message loss**
- Migrated billing pipeline to REST microservice — **45% faster** processing via batch API calls, internal networking, and 10-thread ExecutorService
- Established Jenkins + Docker CI/CD compressing release cycles **6×**; enforced TDD via JUnit 5 / Mockito achieving **85%+ coverage**; resolved **350+ defects** sustaining 99.9% stability

---

## 👨🏻‍💻 Engineering Focus

Currently deepening expertise in:
- **Payment systems security** — PCI-DSS, HSM-backed KMS, token vault design
- **High-availability Kafka patterns** — idempotent consumers, exactly-once semantics, consumer lag management
- **System design at scale** — rate limiters, distributed caching, idempotency in payment APIs

---

## 🎓 Education & Credentials

🎓 **M.Tech** — NIT Warangal (GPA: 8.07/10)
🎓 **B.Tech** — NSUT West Campus, GGSIPU (GPA: 8.40/10)
🏆 **GATE CE 2020** — AIR 3770 · 97th Percentile · Score 586
🥇 **Gold Medal** — Geotechnical Engineering Lab, IIT Bombay 2018 (Top 5%)

---

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mayankSystems&show_icons=true&count_private=true&theme=github_dark&hide_border=true&hide=stars)](https://github.com/mayankSystems)
&nbsp;
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mayankSystems&langs_count=6&layout=compact&theme=github_dark&hide_border=true)](https://github.com/mayankSystems)

</div>
