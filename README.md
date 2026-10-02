<div align="center">
  <img src="assets/123123123.png" alt="Kaadz — Systems // Design // Code" width="100%" />
</div>

<br/>

# Kaadipranav

### I build infrastructure for coding agents, cybersecurity, and technical education.

My work focuses on systems that make complex software workflows more reliable, inspectable, and usable by other people.

---

## Selected work

### [WatchLLM](https://github.com/WatchLLM/watchllm-oss)
> **Deterministic runtime governance for autonomous coding agents.**

An open-core platform that intercepts file operations from coding agents (like Claude Code and Aider), parses them with Tree-sitter AST, and blocks unsafe operations (secrets leaks, boundary violations, unauthenticated mutations) before code reaches disk.

* **Tech:** TypeScript · Python · Rust · Tree-sitter · JSON Schema · VS Code IPC
* **Status:** Open-Core Kernel (v0.1.1) · Monorepo Development
* **Links:** [Repository](https://github.com/WatchLLM/watchllm-oss) · [Website](https://watchllm.dev) · [Documentation](https://docs.watchllm.dev) · [Quickstart Demo](https://github.com/WatchLLM/watchllm-oss#quickstart)

---

### [Klyd](https://github.com/klyd-studio/klyd-harness)
> **Decision memory for coding agents.**

A local memory harness that uses Git hooks to capture architectural decisions from commit diffs via LLM call, stores them in SQLite with vector embeddings, and re-injects relevant constraints into future agent sessions to prevent architectural drift.

* **Tech:** Python 3.11 · SQLite (C-runtime custom functions & recursive CTEs) · Git Hooks · BYOK LLMs
* **Status:** Distributed on PyPI (`v0.2.2`)
* **Links:** [Repository](https://github.com/klyd-studio/klyd-harness) · [PyPI: klyd](https://pypi.org/project/klyd/) · [Architecture & Workflow](https://github.com/klyd-studio/klyd-harness#the-workflow)

---

### [Codify](https://github.com/Codify-PSBB/CODIFY-WEBAPP-CORE)
> **A student-built coding platform for a student-run coding club.**

A purpose-built competition and assignment platform running in school computer labs. Features client-side Python execution via Pyodide WASM, manual admin review workflows, and serverless SQLite atomic scoring with zero RCE attack surface.

* **Tech:** React · Vite · Monaco Editor · Pyodide (WASM) · Cloudflare Workers · Cloudflare D1 · WebCrypto
* **Status:** Internal tool deployed at PSBB Schools (~50–68 registered students in Grades 8–9 cohort)
* **Links:** [Repository](https://github.com/Codify-PSBB/CODIFY-WEBAPP-CORE) · [Platform Information](https://github.com/Codify-PSBB/CODIFY-WEBAPP-CORE#why-codify-exists)

---
