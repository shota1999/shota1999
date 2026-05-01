# Shota Bosikashvili

Full-stack developer building React/Next.js SaaS products.

Open to full-stack, React, and Next.js roles · Tbilisi, Georgia · Remote / relocation

Currently working on Rebatik and WestoreHub — production web platforms focused on cashback, marketplaces, dashboards, and operational workflows.

## 🚀 Projects

### ContractFlow AI
AI proposal and contract workflow platform for marketing agencies.

- Built proposal workflow screens for AI draft generation, approvals, billing, team roles, and client-facing document views.
- Implemented streaming AI drafts over Server-Sent Events with provider failover and a durable BullMQ background job workflow.
- Built a Next.js + NestJS + BullMQ system with Paddle billing, document workflow states, and HMAC-based session authentication.

🔗 https://contractflow.social

---

### Lumina Marketplace
Premium rental marketplace with multilingual UI and AI semantic search.

- Built marketplace UI for search filters, listing pages, booking flows, host dashboard, and responsive mobile layouts.
- Implemented sub-second search on 100K+ rows using OpenAI embeddings, pgvector HNSW, Meilisearch, and PostgreSQL full-text fallback.
- Moved indexing and embedding generation to a BullMQ worker to keep user-facing APIs fast, with deployment via Kubernetes and GitHub Actions.

🔗 https://web-production-0666c.up.railway.app

---

### AI Chess Coach
AI chess coaching platform with voice feedback and Stockfish analysis.

- Built an interactive chess coaching UI with move review, ELO-adaptive feedback, voice explanations, and post-game analysis.
- Ran Stockfish WASM in a Web Worker for responsive client-side analysis, with server-side Stockfish fallback for deeper reviews.
- Integrated Stripe/Paddle checkout, idempotent webhooks, Redis rate limiting, and AI/TTS providers for coaching feedback.

🔗 https://web-production-5b8f2.up.railway.app

## 🧠 Stack

**Core:** React, Next.js, TypeScript, Node.js, NestJS, PostgreSQL, Prisma, Redis, Docker, GitHub Actions  
**Frontend:** Tailwind CSS, shadcn/ui, Radix UI, Redux Toolkit, RTK Query, TanStack Query, React Hook Form, Zod  
**Backend:** REST APIs, OpenAPI, Server-Sent Events, WebSockets, JWT, OAuth, RBAC, HMAC sessions  
**Data & Search:** pgvector, Meilisearch, PostGIS, Drizzle ORM  
**Infrastructure:** Railway, Hetzner VPS, Vercel, Caddy, BullMQ, Kubernetes, Cloudflare, Sentry, OpenTelemetry  
**Payments & Auth:** Stripe, Stripe Connect, Paddle, NextAuth, Better Auth, AWS Cognito  
**Testing:** Vitest, Jest, Playwright, Testcontainers  
**AI Tools:** Claude Code, Codex, Cursor, Gemini, OpenAI API

## 📫 Contact

✉️ shbosika@gmail.com  
💼 https://linkedin.com/in/shota-bosikashvili  
🌐 https://portfolio-kappa-five-m04vuctlxj.vercel.app/
