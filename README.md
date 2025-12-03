<img src="https://raw.githubusercontent.com/kaadipranav/sentryai/main/.github/banner.png" alt="SentryAI – The Datadog for AI" />

<div align="center">
  <br/>
  <a href="https://sentryai.dev"><img src="https://img.shields.io/badge/status-private_beta_(Jan_2026)-brightgreen?style=for-the-badge" alt="Status"/></a>
  <img src="https://img.shields.io/badge/founder-solo_→_shipping_like_a_team_of_10-blue?style=for-the-badge" alt="Solo founder"/>
  <img src="https://img.shields.io/badge/dogfooding-15k%2B_req%2Fday-ff0066?style=for-the-badge" alt="Dogfooding"/>
  <br/>
  <h1>SentryAI</h1>
  <h3>Real-time observability for production LLMs, agents & RAG</h3>
  <i>Every token traced • Every dollar accounted • Every hallucination caught</i>
  <br/><br/>
  <a href="https://twitter.com/kaadz"><img src="https://img.shields.io/twitter/follow/kaadz?style=social&logo=x&label=%40kaadz" alt="Twitter"/></a>
  <img src="https://img.shields.io/github/stars/kaadzipranav/sentryai?style=social" alt="Stars"/>
</div>

<br/>

### What people are already using it for (private beta testers)
- Catching $47k/month cost explosions before they hit the bill  
- Debugging 47-step agent loops that silently die at step 38  
- Blocking PII leaks & prompt injections in production  
- Proving to investors their RAG actually works

### Features (live or <14 days out)
| Feature                        | Status       | Notes                                    |
|--------------------------------|--------------|------------------------------------------|
| Full prompt/response visibility| Live         | Click → expand → copy                   |
| Token & $-cost per call        | Live         | OpenAI, Anthropic, Groq, etc.           |
| Agent step graph visualizer    | 7 days       | Loops, branches, tool calls             |
| PII + injection auto-redaction | Live         | Regex + LlamaGuard 3                    |
| Real-time dashboard + charts   | Live         | Tailwind + Recharts glory               |
| SDKs (Python • JS/TS)          | Live         | `pip install sentryai` • `npm i sentryai` |
| Alerts → Slack/Discord/email   | Live         | Error rate, cost spikes, jailbreaks     |
| Stripe billing                 | Live         | Free → Pro → pay-as-you-go              |

### Built to scale from day 1
```text
10k+ events/sec   → FastAPI + Redis Streams
Billions of rows  → ClickHouse (sub-100ms queries)
Zero-downtime     → Separate ingest + processor

Roadmap (no bullshit dates)

- Jan 2026 → Private beta (DM @kaadz or reply “beta” on my latest tweet)
- Feb 2026 → Public launch + waitlist explodes
- Q2 2026 → $1M ARR or I delete the repo

  Built in public
  
  One founder. One repo. About to 100x the AI observability game.
  
  → Follow the chaos on Twitter
  
  Star if you're building agents and tired of guessing where your money went

```
