<div align="center">
  <h1>Hi there, I'm Paras Dev Tyagi 👋</h1>
  <h3>Software Engineer | Backend, Distributed Systems, AI/LLM Applications</h3>

  <a href="https://www.linkedin.com/in/iampdt/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:parasdevtyagi@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://pdt001.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://leetcode.com/u/Paras_dev/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
  </a>
</div>

<br/>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=00C4FF&center=true&vCenter=true&width=640&lines=Backend+APIs+for+financial+data;LLM+agents+with+approval+gates;Real-time+systems+on+Cloudflare;Measured%2C+tested%2C+shipped+on+free+tiers" alt="Typing SVG" />
</div>

---

### 👨‍💻 About Me

* 💼 **Work:** Software Engineer at **DSP Asset Managers**, Bengaluru. REST APIs, data models, caching and monitoring for portfolio and trade data (Python, FastAPI, Django, PostgreSQL, Redis).
* 🔭 **Building:** systems I can run, break on purpose and measure. Six of them are below, each with the numbers I measured.
* 🌱 **Going deeper on:** distributed systems, consistency and failure handling.
* ⚡ **Problem solving:** C++ for DSA; 5-star on CodeChef.
* 🌍 **Location:** Bengaluru, India.

---

### 🚀 Projects

| Project | What it is | Measured | Links |
| --- | --- | --- | --- |
| **Scalable Event Notification Platform** | Multi-tenant email, webhook and in-app delivery: idempotent ingestion, a PostgreSQL `SKIP LOCKED` job queue, retries and a Kafka outbox | 1,617+ deliveries/s after fixing WAL-write contention; 6,000 of 6,000 delivered with a worker killed mid-batch | [Case study](https://pdt001.vercel.app/projects/notification-platform) · [Code](https://github.com/iampdt/scalable-event-notification-platform) |
| **Tollgate** | An OpenAI-compatible LLM gateway on Cloudflare Workers: provider fallback, circuit breakers, per-key limits, tracing and a semantic cache | 60 ms median overhead; wrong cached answers cut from 22 of 40 to 0 with an LLM judge | [Live](https://tollgate.iampdt.workers.dev) · [Case study](https://pdt001.vercel.app/projects/tollgate) · [Code](https://github.com/iampdt/tollgate) |
| **CodePilot** | A five-agent coding agent that plans, writes, runs and debugs code in a non-root, read-only, no-network Docker sandbox | Built a tested FastAPI service in 3 min 6 s; sandbox hardened with 16 attack tests | [Live replay](https://codepilot.iampdt.workers.dev) · [Case study](https://pdt001.vercel.app/projects/codepilot) · [Code](https://github.com/iampdt/codepilot) |
| **LifeOS** | An AI agent over my Notion (FastAPI, LangGraph, pgvector RAG): the model proposes changes, deterministic code applies them after approval | 34 of 34 evals, including 7 prompt-injection cases; in production at $0/month | [Live demo](https://lifeos-demo-rho.vercel.app) · [Case study](https://pdt001.vercel.app/projects/lifeos) · [Code](https://github.com/iampdt/lifeos) |
| **Lineless** | A walk-in queue on phones: each queue is a Cloudflare Durable Object with SQLite, pushing updates over WebSockets | 1,000 phones on one queue at 231 ms p99 in production; wait-time error cut from 6.5 to 2.2 min | [Live](https://lineless.iampdt.workers.dev) · [Case study](https://pdt001.vercel.app/projects/lineless) · [Code](https://github.com/iampdt/lineless) |
| **Blackbox** | A Chrome extension that records a page's API calls, replays them with the backend off and flags API schema drift | 8 of 8 sessions replayed exactly (1 of 8 for naive mocks); about 1 ms recording overhead | [Live demo](https://blackbox.iampdt.workers.dev) · [Case study](https://pdt001.vercel.app/projects/blackbox) · [Code](https://github.com/iampdt/blackbox) |

---

### 🛠️ Tech Stack & Tools

**Languages**
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

**Backend, Data & Messaging**
<p align="left">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
</p>

**AI & LLM**
<p align="left">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG_%2B_pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge" />
</p>

**Cloud, DevOps & Frontend**
<p align="left">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
</p>

---

### 📈 Coding & GitHub Analytics

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=iampdt&amp;theme=radical&amp;hide_border=true&amp;background=0D1117" height="195" alt="GitHub Streak" />
  <img src="https://leetcard.jacoblin.cool/Paras_dev?theme=radical&amp;font=Fira%20Code&amp;ext=activity&amp;hide_border=true" height="195" alt="LeetCode Stats"/>
</div>

---

### 🐍 Contribution Activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://pdt001.vercel.app/snake/dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://pdt001.vercel.app/snake/light.svg">
    <img alt="github contribution grid snake animation" src="https://pdt001.vercel.app/snake/light.svg">
  </picture>
</div>
