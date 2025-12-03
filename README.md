# SentryAI  [![Python](https://img.shields.io/badge/Python-3.11+-blue?logo=python&logoColor=white)](https://python.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue?logo=typescript&logoColor=white)](https://typescriptlang.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.115+-teal?logo=fastapi)](https://fastapi.tiangolo.com)
[![ClickHouse](https://img.shields.io/badge/ClickHouse-24.x-green?logo=clickhouse)](https://clickhouse.com)
[![Redis](https://img.shields.io/badge/Redis-Streams-red?logo=redis)](https://redis.io)
[![Vercel](https://img.shields.io/badge/Deployed-Vercel-black?logo=vercel)](https://vercel.com)

**The observability platform built for production AI**  
Real-time tracing · Token-level analytics · Cost control · Alerting · Agent debugging

Think **Sentry × Datadog**, but 100% native for LLMs, agents, and RAG.

![](https://img.shields.io/badge/status-private%20beta%20(Jan%202026)-brightgreen)
![](https://img.shields.io/badge/founder-solo%20→%20shipping%20like%20a%20team%20of%2010-ff69b4)
![](https://img.shields.io/badge/dogfooding-10k%2B%20req%2Fday-blue)

### Live Features (already shipped or <7 days away)
- Full prompt / response / metadata visibility
- Token & dollar cost breakdown per call
- Agent step tracing + loop detection
- PII + prompt injection redaction
- Real-time dashboard + Recharts graphs
- Python & JS/TS SDKs (`pip install sentryai` · `npm i sentryai`)
- Alerting → Slack / Discord / webhook
- Stripe billing (free tier → Pro → Enterprise)

### Tech stack (built for speed & scale)
| Layer        | Tech                                      | Why                              |
|-------------|-------------------------------------------|----------------------------------|
| Ingest      | FastAPI + Redis Streams                   | 10k+ events/sec, sub-5ms p95     |
| Storage     | ClickHouse                                | Billions of rows, instant queries|
| Frontend    | React + TypeScript + Tailwind + Recharts  | Looks like a $100M SaaS          |
| SDKs        | Python · TypeScript                       | One-line install, auto-batching  |

### Timeline
- **Jan 2026** → Private beta (DM @kaadz for access)
- **Feb 2026** → Public launch + waitlist opens
- **Q2 2026** → First $1M ARR or bust

### Get in
- Star → follow the rocket
- Twitter → [@kaadz](https://twitter.com/kaadz) (daily build screenshots)
- Want in early? reply “beta” under my latest tweet

Built solo in public.  
If you’re shipping agents or spending >$1k/mo on OpenAI, this will save your ass.

**One founder. One repo. Zero chill.**
