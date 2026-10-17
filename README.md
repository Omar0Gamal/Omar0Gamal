# Omar Gamal

**Backend, distributed systems and full-stack engineer**  
Cairo, Egypt (UTC+2 / UTC+3) · Available full-time (remote, full EU & US overlap)

[Portfolio](https://omar0gamal.vercel.app) · [LinkedIn](https://www.linkedin.com/in/omar-gamal-091044168/) · [Email](mailto:omargamal.dev@outlook.com)

---

## About

Backend, distributed systems, and full-stack engineer with 4+ years of production experience building high-concurrency systems, microservices, and cloud infrastructure. Previously maintained 15+ Java backend services and Linux infrastructure for a 500+ concurrent-user platform at Attila Gaming—reducing crashes by 60% and latency by 40%—and architected a 14-service polyglot platform with Protobuf contracts and Kubernetes automation at Ayist Group. Final-year Computer Science student at Capital University (GPA 3.92/4.0), fluent in English, and available full-time for remote roles with full EU and US morning/afternoon overlap.

---

## Featured Projects

### 1. Nexus Commerce

Multi-tenant e-commerce platform featuring an edge tenant router, a Go modular monolith, Redis inventory locks, and a Next.js merchant operations console and customer storefront.

<p align="center">
  <a href="https://github.com/Omar0Gamal/Nexus-Commerce">
    <img src="https://raw.githubusercontent.com/Omar0Gamal/Nexus-Commerce/main/docs/screenshots/hero.png" alt="Nexus Commerce Storefront and Merchant Console" width="100%" />
  </a>
</p>

- **Stack:** Go 1.24, Gin, sqlc, pgx, PostgreSQL 16, Redis (carts, 15-minute inventory reservation locks, LPUSH/BRPOP job queue), Cloudflare Workers & KV, Caddy, Next.js, Paymob
- **Links:** [Repository](https://github.com/Omar0Gamal/Nexus-Commerce)

---

### 2. JobTrack

Production-grade job application tracker engineered with dual personal and demo sandboxes, signed guest sessions, and SSRF-hardened autofill.

<p align="center">
  <a href="https://jobtrack-demo.vercel.app">
    <img src="https://raw.githubusercontent.com/Omar0Gamal/JobTrack/main/docs/screenshots/hero-showcase.png" alt="JobTrack Flagship Studio Command Center" width="100%" />
  </a>
</p>

- **Stack:** Next.js 15, React 19, TypeScript (strict), Prisma, PostgreSQL (Neon), Auth.js v5, Tailwind CSS, 207 Vitest tests + 5 Playwright E2E tests, GitHub Actions CI
- **Links:** [Live Demo](https://jobtrack-demo.vercel.app) · [Repository](https://github.com/Omar0Gamal/JobTrack)

---

### 3. Cartwright

Distributed saga orchestrator coordinating polyglot services with transactional outbox, idempotency keys, and chaos testing against mid-flight crashes.

- **Stack:** Go (Saga Orchestrator), ASP.NET / C# (Billing), Python (Notification Service), gRPC, Protocol Buffers, NATS JetStream, PostgreSQL, k3s, Terraform, Helm
- **Links:** [Repository](https://github.com/Omar0Gamal/cartwright-saga)

---

### 4. AxiomGraph

Hybrid graph-vector database engineered for GraphRAG workloads, delivering 33,000+ QPS on GPU and 8,600 QPS on CPU while holding 1M nodes under 2 GB RAM.

- **Stack:** C++17, CUDA (cuVS CAGRA), HNSW, Python (nanobind SDK), SQLite, CMake
- **Links:** [Repository](https://github.com/Omar0Gamal/AxiomGraph)

---

### 5. llama.cpp (PR #26933)

Fixed two out-of-bounds memory vulnerabilities in the RPC server through pre-execution tensor shape validation on `SET_ROWS` and `GET_ROWS`.

- **Stack:** C++, RPC Server, Tensor Graph Validation
- **Links:** [Pull Request #26933](https://github.com/ggml-org/llama.cpp/pull/26933)

---

## Tech Stack

### Languages
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)

### Backend
![Gin](https://img.shields.io/badge/Gin-008ECF?style=flat-square&logo=go&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white)
![Protocol Buffers](https://img.shields.io/badge/Protocol_Buffers-4285F4?style=flat-square&logo=google&logoColor=white)
![sqlc](https://img.shields.io/badge/sqlc-00ADD8?style=flat-square&logo=go&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![NATS JetStream](https://img.shields.io/badge/NATS_JetStream-375C96?style=flat-square&logo=natsdotio&logoColor=white)
![Auth.js](https://img.shields.io/badge/Auth.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

### Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

### Data
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

### Infrastructure
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

Reach me at [omargamal.dev@outlook.com](mailto:omargamal.dev@outlook.com) or connect on [LinkedIn](https://www.linkedin.com/in/omar-gamal-091044168/).
