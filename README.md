# Hi, I'm Pouya 👋

**Senior Full Stack Engineer** · Strasbourg, France 🇫🇷  
I build **production-grade web, mobile, and systems software** — from custom SSR engines and real-time financial platforms to high-concurrency Go microservices and a blockchain from scratch.

5+ years of shipping. Ex-CTO & Co-founder at **ReboTurn** (Techstars Atlanta). Previously at **Digi Conception** (2024–2025). Currently **freelancing** — building client projects and open-source systems.

> **Engineering philosophy:** Systems should be testable, observable, and replaceable.  
> I enforce 80%+ test coverage, clean layered architecture, and SOLID/CQRS patterns by default.

---

## 🔭 What I'm Currently Building

| Project | What & Why |
|---------|------------|
| **Obol Blockchain Engine** | Custom UTXO ledger in Go 1.25+ evolving into an autonomous AI micro-payment mesh with MCP daemons and Zero-Knowledge Contingent Payments (ZKCP). Proof-of-Work/Authority consensus, P2P TCP node, ECDSA wallet signing. |
| **Go Systems Portfolio** | High-throughput URL shortener (10,000+ RPS, Redis Pub/Sub), concurrent BitTorrent client (custom Bencode parser, TCP wire protocol), raw TCP chat server (bcrypt auth, cursor pagination), and a DNS security audit CLI (SPF/DMARC/DKIM, RFC compliance linting). |
| **MCP Tooling** | Building Model Context Protocol servers (Bun/TypeScript and Go) that let AI agents run deterministic file operations and inspect dev environments with full test isolation via DI. |

---

## 🛠️ Core Tech Stack

**Languages & Runtimes**  
`Go (Golang)` `TypeScript` `JavaScript` `Swift` `PHP`  `Bun`

**Frontend & Mobile**  
`React 19` `Next.js` `Vite (custom SSR)` `TanStack Query` `Tailwind CSS` `Zod` `Three.js` `Framer Motion`  
`SwiftUI` `React Native` `Ionic / Angular`

**Backend & APIs**  
`Node.js` `NestJS` `Go / Gin` `LoopBack 4` `Express` `Supabase` `Laravel` `GraphQL`

**Data & Messaging**  
`PostgreSQL` `MySQL` `MongoDB` `Redis (Pub/Sub & Cache)` `SQLite` `Drizzle ORM` `Prisma`

**Architecture Patterns**  
`CQRS` `Clean Architecture (3-layer)` `Hexagonal Architecture (Ports & Adapters)` `SOLID` `Event-Driven` `Worker Pools` `Domain-Driven Design`

**DevOps & Infra**  
`Docker` `Docker Compose` `GitHub Actions` `GHCR` `Nginx` `Caddy` `AWS S3` `GCP` `GoReleaser`

---

## 🏗️ Featured Projects

### Systems & Go
| Project | What it solves | Stack |
|---------|---------------|-------|
| **[Go Blockchain Engine — Obol](https://github.com/pouyasadri)** | UTXO ledger + PoW/PoA consensus + P2P mesh → evolving into AI agent micro-payment settlement (MCP + ZKCP) | Go 1.25+, ECDSA, bbolt, MCP, gRPC, Docker |
| **[High-Throughput URL Shortener](https://github.com/pouyasadri)** | 10,000+ RPS shortener with async Redis Pub/Sub analytics pipeline and <1ms overhead per request | Go, Gin, Redis, MongoDB, Docker Compose |
| **[Go BitTorrent Client](https://github.com/pouyasadri)** | Full BitTorrent wire-protocol implementation: custom Bencode parser, multi-peer TCP, SHA-1 piece verification, bandwidth throttling | Go 1.25, TCP, Docker |
| **[Automated VPN Provisioning Bot](https://github.com/pouyasadri)** | Telegram bot auto-provisioning VLESS/VMess/Trojan VPN accounts via Hiddify API with 100-worker concurrency pool | Go 1.25, GORM, SQLite, Docker |
| **[DNS Email Security Audit Tool](https://github.com/pouyasadri)** | CLI auditing SPF/DMARC/DKIM/BIMI/MTA-STS at scale with singleflight thundering-herd protection and SARIF/NDJSON output | Go 1.26, Worker Pools, GoReleaser |

### MCP Servers & AI Tooling
| Project | What it solves | Stack |
|---------|---------------|-------|
| **[MCP File Converter](https://github.com/pouyasadri/mcp-file-converter)** | Local stdio MCP server enabling Claude & Cursor to run deterministic file conversions (image, structured data, markup) with SHA-256 provenance manifests | Bun, TypeScript, MCP, Zod, Sharp, Docker |
| **[Environment Validator MCP Server](https://github.com/pouyasadri)** | MCP server letting AI assistants inspect dev tool versions and env vars; 100% DI-isolated TDD, semver constraint engine across 15+ CLI ecosystems | Go 1.24, MCP Go SDK, Semver, Docker |

### Full Stack & Mobile
| Project | What it solves | Stack |
|---------|---------------|-------|
| **Alsace Navette** | Complete overhaul of a legacy Symfony portal → modern full-stack shuttle reservation platform. Custom Vite SSR engine (no Next.js overhead), 3-role portals (Admin/Driver/Customer), CQRS NestJS backend. | React 19, Vite SSR, NestJS, Drizzle ORM, MySQL, Tailwind, Lingui i18n |
| **AI Photobooth SaaS & Fleet** | Multi-platform event kiosk (iPad + Desktop) with Generative AI photo transforms, remote machine telemetry, and automated video synthesis | Swift/SwiftUI, C# (.NET), Next.js, Supabase Realtime, Runware AI |
| **Geofenced Field Sales App** | Role-based mobile app (Admin/Agent) with GPS geofencing for mission check-ins and dynamic field reporting | React Native, Supabase |
| **Real-Time Auction Platform (BidSale)** | WebSocket-driven auction engine with concurrency guards, dynamic bid timers, and automated profitability logic | Laravel, WebSockets, MySQL, JavaScript |
| **Go Real-Time Chat Server** | High-throughput WebSocket server in Go with goroutines/channels + React client for live channels | Go, React, WebSockets |

---

## ✍️ Writing & Teaching

I share what I learn — consistently, not occasionally.

- **[Medium](https://medium.com/@pouyasadri)** — Technical articles on Full Stack architecture, Go systems, Swift, and cloud design. Goal: 1 article/month.
- **[YouTube — @pouyasadri](https://www.youtube.com/@pouyasadri)** — SwiftUI and Swift tutorials for independent iOS developers. Educational content with real-world use cases.

---

## 📈 Activity

<p align="center">
  <img src="https://ghchart.rshah.org/pouyasadri" alt="GitHub Contribution Chart" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/followers/pouyasadri?label=Followers&style=flat-square" alt="Followers" />
  &nbsp;
  <img src="https://img.shields.io/github/last-commit/pouyasadri/pouyasadri?color=green&style=flat-square" alt="Last commit" />
</p>

---

## 🤝 Let's Connect

I'm open to technical conversations, collaboration, and interesting engineering challenges.

<p align="center">
  <a href="mailto:info@pouyasadri.com"><img src="https://img.shields.io/badge/Email-info@pouyasadri.com-c14438?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/seyedpouya-sadri-fard/"><img src="https://img.shields.io/badge/LinkedIn-seyedpouya--sadri--fard-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://www.pouyasadri.com"><img src="https://img.shields.io/badge/Portfolio-pouyasadri.com-000000?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"></a>
  <a href="https://medium.com/@pouyasadri"><img src="https://img.shields.io/badge/Medium-@pouyasadri-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"></a>
  <a href="https://www.youtube.com/@pouyasadri"><img src="https://img.shields.io/badge/YouTube-@pouyasadri-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"></a>
</p>
