# 👋 Kaadz | Building WatchLLM

<div align="center">

```ascii
██╗    ██╗ █████╗ ████████╗ ██████╗██╗  ██╗██╗     ██╗     ███╗   ███╗
██║    ██║██╔══██╗╚══██╔══╝██╔════╝██║  ██║██║     ██║     ████╗ ████║
██║ █╗ ██║███████║   ██║   ██║     ███████║██║     ██║     ██╔████╔██║
██║███╗██║██╔══██║   ██║   ██║     ██╔══██║██║     ██║     ██║╚██╔╝██║
╚███╔███╔╝██║  ██║   ██║   ╚██████╗██║  ██║███████╗███████╗██║ ╚═╝ ██║
 ╚══╝╚══╝ ╚═╝  ╚═╝   ╚═╝    ╚═════╝╚═╝  ╚═╝╚══════╝╚══════╝╚═╝     ╚═╝
```

### *Cut AI costs by 70% • Semantic caching for LLM APIs*

[![Live](https://img.shields.io/badge/🚀_LIVE-watchllm.dev-00ff88?style=for-the-badge)](https://watchllm.dev)
[![Deployed](https://img.shields.io/badge/⚡_CLOUDFLARE-WORKERS_@_EDGE-FF6B35?style=for-the-badge)](https://proxy.watchllm.dev)
[![Ship](https://img.shields.io/badge/💪_SOLO-SHIPPING_FAST-ff0066?style=for-the-badge)](https://twitter.com/kaad_zz)

[![Twitter](https://img.shields.io/twitter/follow/kaad_zz?style=for-the-badge&logo=x&color=000000&labelColor=1DA1F2)](https://twitter.com/kaad_zz)
[![GitHub Stars](https://img.shields.io/github/stars/kaadipranav?style=for-the-badge&logo=github&color=black)](https://github.com/kaadipranav)

</div>

---

## Currently Building

<table>
<tr>
<td width="60%">

### WatchLLM
**Drop-in OpenAI proxy with semantic caching**

```typescript
const client = new OpenAI({
  apiKey: 'lgw_proj_xxxxx',
  baseURL: 'https://proxy.watchllm.dev/v1'
});

// That's it. 70% savings activated.
```

**Impact:**
- 🔥 70% cost reduction on AI API bills
- ⚡ <50ms cache hit response time
- 🚀 5-minute integration time
- 🌍 Edge deployment on Cloudflare

**Stack:** TypeScript • Next.js • Hono • Cloudflare Workers • Supabase • Redis

**Status:** 🟢 Live at [watchllm.dev](https://watchllm.dev)

</td>
<td width="40%">

```mermaid
graph TD
    A[Your App] -->|Request| B[WatchLLM Edge]
    B -->|Cache Check| C{Semantic Match?}
    C -->|✅ HIT| D[Return <50ms]
    C -->|❌ MISS| E[OpenAI/Anthropic]
    E -->|Cache + Return| D
    style B fill:#00ff88,stroke:#00cc66
    style D fill:#ffeb3b,stroke:#ffc107
    style E fill:#ff6b6b,stroke:#cc5555
```

</td>
</tr>
</table>

---

## Tech Stack

```typescript
const kaadz = {
  languages: ['TypeScript', 'Python', 'JavaScript'],
  frontend: ['React', 'Next.js 14', 'TailwindCSS'],
  backend: ['Hono', 'Node.js', 'Cloudflare Workers'],
  databases: ['PostgreSQL', 'Supabase', 'Upstash Redis'],
  deployment: ['Vercel', 'Cloudflare', 'Docker'],
  tools: ['Git', 'VS Code', 'Linear', 'Cursor'],
  currentFocus: 'Building WatchLLM to $1K MRR',
  sleepSchedule: 'Optional'
};
```

---

## GitHub Stats

<div align="center">

![](https://github-readme-stats.vercel.app/api?username=kaadipranav&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=00ff88&icon_color=00ff88&text_color=ffffff)

![](https://github-readme-streak-stats.herokuapp.com/?user=kaadipranav&theme=radical&hide_border=true&background=0d1117&ring=00ff88&fire=ff6b35&currStreakLabel=00ff88)

</div>

---

## Contribution Graph

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kaadipranav/kaadipranav/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kaadipranav/kaadipranav/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/kaadipranav/kaadipranav/output/github-contribution-grid-snake.svg">
</picture>

---

## What I'm Up To

```bash
$ cat current_focus.txt
```
- 📈 Scaling WatchLLM to first $1K MRR
- 🏗️ Building in public on Twitter [@kaad_zz](https://twitter.com/kaad_zz)
- 💰 Learning growth & monetization
- 🎯 Shipping fast, iterating faster
- 🤝 Open to collaboration on indie projects

---

## Let's Connect

<div align="center">

[![Website](https://img.shields.io/badge/🌐_Website-Kaadz.me-00ff88?style=for-the-badge)](https://Kaadz.me)
[![Twitter](https://img.shields.io/badge/𝕏_Twitter-@kaad__zz-000000?style=for-the-badge&logo=x)](https://twitter.com/kaad_zz)
[![IndieHackers](https://img.shields.io/badge/🚀_IndieHackers-kaadz-0E2439?style=for-the-badge)](https://indiehackers.com/kaadz)
[![Email](https://img.shields.io/badge/📧_Email-kiwi092020@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kiwi092020@gmail.com)

</div>

---

<div align="center">

**"Building products that make AI affordable for everyone"**

*Solo indie maker • TypeScript enthusiast • Building @watchllm*

![Profile Views](https://komarev.com/ghpvc/?username=kaadipranav&color=00ff88&style=flat-square&label=Profile+Views)

</div>
