# Shota Bosikashvili

 Full-Stack Engineer building production-style SaaS, marketplace, and AI product systems with React, Next.js, TypeScript, Node.js, PostgreSQL, Redis, and Docker.

Based in Tbilisi, Georgia · Remote-first · GMT+4 with strong Europe/EMEA overlap  
Open to senior full-stack, product engineering, and React/Next.js TypeScript roles with remote-first teams.

---

## What I Build

I focus on end-to-end product engineering where frontend quality meets backend reliability:

- SaaS dashboards and workflow platforms
- Marketplace and booking flows
- Payments, affiliate tracking, and idempotent webhooks
- Background jobs with Redis/BullMQ
- AI/LLM product interfaces
- Search systems with Meilisearch, pgvector, and OpenAI embeddings
- Testing, CI/CD, Docker-based deployments, and production debugging

---

## Featured Projects

# Rebatik — Cashback Marketplace                                                                              
                                                   
  Cashback marketplace with affiliate tracking — reward flows, withdrawals, referrals, transaction history, and 
  a Chrome extension for one-click activation at checkout.                                                      
                                                                                                                
  ## What I built                                                                                               
                                                                                                                
  - Built cashback dashboard flows for available balance, pending rewards, withdrawals, referrals, and
  transaction history using **Next.js**, **TypeScript**, and **TanStack Query**.
  - Designed a double-entry ledger (CREDIT/DEBIT, SQL-level status rules, idempotency keys) and integrated
  **Admitad** affiliate tracking for **AliExpress, Alibaba, Western Union, Aviasales, and Kaspersky** — taking
  clicks through to confirmed cashback via postback ingestion and daily reconciliation.
  - Shipped a **Manifest v3 Chrome extension** that auto-detects merchant pages, shows a floating cashback
  activation banner with live rates, and auto-applies coupon codes at checkout via merchant-specific DOM
  selectors.
  - Built a **Hono** API on **Drizzle/PostgreSQL** with **Redis-backed BullMQ** workers for affiliate postback
  ingestion, payouts, and **Socket.IO** live balance updates, covered by 180+ unit, integration, and E2E tests.

  ## Stack

  **Frontend** — Next.js · TypeScript · TanStack Query
  **Backend** — Hono · Drizzle ORM · PostgreSQL · Redis · BullMQ · Socket.IO
  **Auth & Payments** — Better Auth · Stripe · Resend
  **Extension** — Manifest v3 · service worker + content scripts
  **Affiliate** — Admitad (AliExpress, Alibaba, Western Union, Aviasales, Kaspersky)
  **Testing** — Vitest · Playwright (180+ tests)
  **Infra** — Docker

---

### ContractFlow AI — AI Proposal & Contract Workflow Platform

AI-powered proposal and contract workflow platform for marketing agencies.

**What I built**
- Built proposal workflow screens for AI draft generation, approvals, billing, team roles, and client-facing document views.
- Implemented streaming AI drafts over Server-Sent Events with provider failover.
- Built a durable BullMQ background job workflow with persisted job state, retries, backoff, and worker heartbeats.
- Designed secure foundations with HMAC-based sessions, secure cookies, rate limiting, CSP protections, webhook validation, and Paddle billing.

**Stack:** Next.js, TypeScript, NestJS, BullMQ, Redis, PostgreSQL, Paddle, Docker, Railway

🔗 https://contractflow.social

---

### Lumina Marketplace — Premium Rental Marketplace with AI Search

Multilingual premium rental marketplace with booking flows, host tools, and semantic search.

**What I built**
- Built marketplace UI for search filters, listing pages, booking flows, host dashboard, and responsive mobile layouts.
- Implemented sub-second search on 100K+ rows using OpenAI embeddings, pgvector HNSW, Meilisearch, and PostgreSQL full-text fallback.
- Moved indexing and embedding generation to a BullMQ worker to keep user-facing APIs fast.
- Added production-oriented infrastructure with Docker, Kubernetes, GitHub Actions, OpenTelemetry, and automated tests.

**Stack:** Next.js, TypeScript, PostgreSQL, Drizzle ORM, Redis, BullMQ, Meilisearch, pgvector, OpenAI, Docker, Kubernetes

🔗 https://web-production-0666c.up.railway.app

---

### AI Chess Coach — AI Coaching Platform with Voice Feedback

AI chess coaching SaaS with Stockfish analysis, personalized feedback, voice explanations, and subscription access.

**What I built**
- Built an interactive chess coaching UI with move review, ELO-adaptive feedback, voice explanations, and post-game analysis.
- Ran Stockfish WASM in a Web Worker for responsive client-side analysis, with server-side Stockfish fallback for deeper reviews.
- Integrated Stripe/Paddle checkout, idempotent webhooks, Redis rate limiting, and AI/TTS providers.
- Reduced game-state write load with Redis-buffered delta writes and PostgreSQL fallback.

**Stack:** Next.js, TypeScript, Stockfish WASM, Web Workers, PostgreSQL, Redis, Stripe, Paddle, OpenAI/TTS

🔗 https://web-production-5b8f2.up.railway.app

---

## Technical Stack

**Core:** React, Next.js, TypeScript, Node.js, NestJS, PostgreSQL, Prisma, Redis, Docker, GitHub Actions  
**Frontend:** App Router, React Server Components, Tailwind CSS, shadcn/ui, Radix UI, Redux Toolkit, RTK Query, TanStack Query, React Hook Form, Zod  
**Backend:** REST APIs, OpenAPI, Server-Sent Events, WebSockets, JWT, OAuth, RBAC, HMAC sessions  
**Data & Search:** pgvector, Meilisearch, PostGIS, Drizzle ORM  
**Infrastructure:** Railway, Hetzner VPS, Vercel, Caddy, BullMQ, Kubernetes, Cloudflare, Sentry, OpenTelemetry  
**Payments & Auth:** Stripe, Stripe Connect, Paddle, NextAuth, Better Auth, AWS Cognito  
**Testing:** Vitest, Jest, Playwright, Testcontainers  
**AI Tools:** Claude Code, Codex, Cursor, Gemini, OpenAI API

---

## Contact

Email: shbosika@gmail.com  
LinkedIn: https://linkedin.com/in/shota-bosikashvili  
Portfolio: https://shotabosikashvili.vercel.app/
