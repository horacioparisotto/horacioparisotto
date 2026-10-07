# Horacio Parisotto

**Senior Full-Stack & AI Engineer · Founder @ OurBlock.io**<br>
AI Agents · MCP · RAG · Vector Search · AI Vision (Claude + Gemini) · Real-Time Video · TypeScript · React · React Native · Next.js · Node.js · Go · Python · AWS · GCP

6+ years shipping production software, now focused on AI products, performance and cost efficiency · Lead engineer on a Forbes-featured startup · 2,700+ contributions last year

[Portfolio](https://www.horacioparisotto.com) · [LinkedIn](https://linkedin.com/in/horacioparisotto)

---

### Stack

**Languages:** TypeScript, JavaScript, Python, Go, C++ (Arduino / ESP32 firmware), HTML, CSS

**Frontend & Mobile:** React, Next.js, React Native (iOS & Android), Tailwind CSS, Redux, Zustand, React Query

**Backend & Data:** Node.js, Express, Go, PostgreSQL, MongoDB, Elasticsearch, Redis, Firebase (Firestore, Auth, Realtime Database, Cloud Functions), GraphQL, BullMQ, Drizzle ORM

**AI & LLMs:** Anthropic Claude, Claude Code, Google Gemini, OpenAI, AI Agents, MCP, RAG, Tool Use, Structured Output, Vector Search (Elasticsearch kNN, sqlite-vec, pgvector), Embeddings, Hybrid Search, LLM Evaluation (nDCG), Multi-provider AI Vision, ElevenLabs

**Distributed Systems:** Async Processing, Idempotency, Two-Phase Execution, Job Queues, Server-Sent Events, Zero-Downtime Migrations

**Real-Time & Media:** FFmpeg, RTSP/HLS, MediaMTX, IoT (ESP32 firmware)

**Cloud & DevOps:** Docker, Google Cloud Run, Cloud Functions, AWS, Vercel, Cloudflare, Git, GitHub Actions, Jest, Vitest, Sentry, PM2

**Integrations:** Stripe, Mercado Pago, Twilio (WhatsApp Business), Resend, Webhooks, OAuth 2.0, JWT, Auth0

---

### Featured Projects

**HarrisTime.ca** · Full-Stack Engineer (GCP). Arena scheduling and live digital signage platform in Canada: 30+ screens across 17 facilities for 10 client organizations, including municipalities, with 37,000+ events scheduled for 600+ teams. Traced a runaway Firebase bill to queries loading the entire database history and cut it from $2,353 to $6.49/month (99.7%, roughly $28k a year), then rebuilt the platform from scratch as a multi-venue system: an LLM scheduling assistant on Gemini, an ESP32 horn controller, automated league schedule sync in Python, and Docker images on Google Cloud Run. Migrated with zero downtime, 175 tests gating CI.

**Tur.com** · Senior Full-Stack Engineer (Go). Multi-tenant travel marketplace live in 10 countries, on a custom Go backend with PostgreSQL, MongoDB and AWS. Designed hybrid semantic search (vector and keyword search on Elasticsearch with OpenAI embeddings): nDCG@5 from 0.41 to 0.75 and empty searches from 31 to 0 in offline evaluation. Built a self-service backoffice powering 42 live landing pages, tiered installment payments, and led a performance investigation that took mobile Lighthouse from 43 to 61 and desktop from 74 to 91. 71 pull requests across 4 repositories, all backward-compatible.

**Lit** · Lead Engineer (React Native). Curated influencer marketplace featured by Forbes: brands list events, creators apply, chat with the brand, check in with a QR code at the venue and deliver content for review. Took an unfinished draft from an outside team and built the product end to end through its launch on Google Play and the App Store, with Mercado Pago plans, a Next.js admin panel for curation and the marketing website.

**Automated Code Review Agent** · Confidential client (AI Agents). Mined 750+ review comments across 1,300+ pull requests into a knowledge base of the team's conventions, then encoded it into a self-gating Claude Code skill that reviews real, open PRs and cross-references sibling code for repeated bugs.

**OurBlock.io** · Founder & Engineer (AI / Edge). 24/7 AI camera-security platform, live in production on a rural property. Multi-provider AI vision (Claude + Gemini) with a 94% lower AI cost per frame, RAG search over the event log (sqlite-vec + OpenAI embeddings), a tool-calling agent for natural-language investigations, an RTSP-to-HLS video pipeline on FFmpeg, ElevenLabs voice alerts and a Twilio WhatsApp panic button. Runs on a Node.js backend on a single mini PC on site, with no database server.

**Autonomous AI Agent Platform** · Confidential client (AI Agents). Designed with the company's CTO: an autonomous remediation agent that turns a reported incident into finished, assigned follow-up work. It works through narrow, named MCP tools instead of direct database access, holds no standing credentials (every call runs under the identity of whoever triggered it), and uses two-phase execution with idempotency guarantees.
