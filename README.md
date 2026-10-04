<h1 align="center">Alok Jaiswal</h1>

<p align="center">
  <b>Full-stack engineer · 5 years · I build and run AI-powered products end to end</b><br/>
  TypeScript · React / Next.js · Node.js · PostgreSQL · AWS · LLM apps (RAG, agents, evals)
</p>

<p align="center">
  <sub>263 merged PRs and 38 releases on a live product since June 2026 · LLM features gated by evals in CI · MERN apps for 15,000+ daily users at DXC Technology</sub>
</p>

<p align="center">
  Gurugram, India · Open to Senior Full-Stack and Product Engineer roles (Gurugram, Bengaluru or remote)<br/>
  <a href="mailto:jaisss.alok@gmail.com">jaisss.alok@gmail.com</a> ·
  <a href="https://www.linkedin.com/in/alokjais/">LinkedIn</a> ·
  <a href="https://alokjaiss.github.io/Resume/">Resume</a> ·
  <a href="https://codecraft-murex.vercel.app">Blog</a>
</p>

---

### About

I've shipped production web apps for 5 years. I spent four of them at DXC Technology building MERN applications for enterprise clients. Since December 2025 I've run PixelWeb Tech, where I design, build and operate products for paying clients.

I own work from the first issue to the production dashboard: AI features with evals in CI, releases behind a review-and-test gate, and decision records that explain why.

### Selected work

**[Sahayak AI](https://github.com/alokjaiss/sahyak-ai)**: an open-source AI assistant any business adds to its website with one script tag. It answers visitors in Hindi and English from the business's own content, cites its sources, captures leads and hands off to WhatsApp.

- Hybrid retrieval: pgvector (HNSW) and Postgres full-text search in one SQL query, merged with Reciprocal Rank Fusion
- A provider-agnostic tool-calling agent loop streamed over SSE (Claude, OpenAI-compatible APIs, and an offline model for CI)
- An eval suite that gates CI at 85%. Its first run scored 63% and exposed Hindi tokenisation bugs; the fixes took it to 100%
- Multi-tenant and secure by default: hashed keys, origin allow-lists, rate limits, SSRF-safe ingestion. 52 tests run on PGlite and Postgres 16
- `TypeScript` `Node.js` `React` `PostgreSQL + pgvector` `Docker` `GitHub Actions`

**[Bhajoshom](https://bhajoshom.com)**: a live music and meditation platform. I've built and operated it since June 2026: 418 commits, 263 merged PRs and 38 releases, every change going issue → branch → reviewed PR → release.

- Next.js 16 (App Router) and React 19 on Supabase (PostgreSQL, Auth, Realtime); audio in a private Cloudflare R2 bucket served only through a Worker
- Co-listening rooms on Supabase Realtime, lock-screen and media-key control, and an installable PWA
- An admin CMS with signed sessions, bulk track management and direct-to-R2 uploads
- Architecture decisions recorded as ADRs, such as "serve stale or fail loudly, never mock data" and "withdraw records instead of deleting them"
- `Next.js` `TypeScript` `Supabase` `Cloudflare Workers` `R2` `Zustand` `Tailwind CSS` · Client project, so the code is private

**[Sanatan Dharma Wiki](https://sanatan-dharma-wiki.vercel.app)**: an open, source-cited encyclopedia ([code](https://github.com/alokjaiss/sanatan-dharma-wiki)). Astro and TypeScript, with content validation in CI and a review flow in which AI drafts and humans approve every change through pull requests.

<!--
Uncomment when the Hisaab repo is public (Milestone 1):

**[Hisaab](https://github.com/alokjaiss/hisaab)**: a payments and ledger platform built never to double-charge. Idempotent APIs, a double-entry ledger in PostgreSQL, Razorpay webhooks through a transactional outbox to Kafka, OpenTelemetry traces end to end, and load tests in CI.
-->

### Experience

**Founder and Full-Stack Engineer, PixelWeb Tech** · Gurugram · Dec 2025 – present
- Design, build and operate client products end to end, including Bhajoshom and Sahayak AI
- Build e-commerce sites for Indian businesses with Razorpay, UPI and cash-on-delivery payments

**Software Engineer, DXC Technology** · Mumbai · Nov 2021 – Nov 2025 (promoted Aug 2023)
- Built and scaled MERN applications serving 15,000+ daily active users, and cut page load latency by 28%
- Replaced a third-party reporting tool with in-house React and PostgreSQL dashboards, saving $18,000 a year
- Added Redis caching and query optimisation that cut database reads by 40%
- Mentored 3 junior developers, and set up linting, CI and Jest tests that cut post-release bugs by 30%

### How I work

- **Every change is traceable.** Issue → branch → PR with a walkthrough → review → release notes.
- **Decisions are written down.** ADRs record what was chosen, what was rejected, and why.
- **Quality is measured.** Tests and type checks gate merges, and LLM features ship behind evals.
- **AI agents speed me up; I own what ships.** I use Claude Code daily. I design the system, review every diff, and keep tests as the gate.

### Stack

| | Production experience | Building now (Q4 2026) |
|---|---|---|
| **Languages** | TypeScript, JavaScript, SQL | Python (FastAPI) |
| **Frontend** | React, Next.js, Redux Toolkit, Zustand, Tailwind CSS | Playwright end-to-end tests |
| **Backend** | Node.js, Express, REST, SSE, WebSockets, JWT, OAuth 2.0, RBAC | Kafka (Redpanda), transactional outbox |
| **Data** | PostgreSQL (pgvector, full-text search), Supabase, MongoDB, Redis | |
| **Cloud and DevOps** | Docker, GitHub Actions, AWS (S3, CloudFront, EC2, Lambda), Cloudflare Workers and R2, Vercel | Kubernetes (Helm), Terraform, AWS ECS, RDS and SQS |
| **AI** | RAG, hybrid search, tool calling, agent loops, LLM evals, Anthropic and OpenAI SDKs | Tracing for AI agents |
| **Quality and ops** | Vitest, Jest, React Testing Library | OpenTelemetry, Grafana, k6 load tests |

### Writing

I write tutorials on web development, AI, Python and DevOps at [CodeCraft](https://codecraft-murex.vercel.app).

---

<p align="center">Hiring for a full-stack or AI product role? Email me at <a href="mailto:jaisss.alok@gmail.com">jaisss.alok@gmail.com</a>.</p>
