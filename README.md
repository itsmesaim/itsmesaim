<h1 align="center">Saim Shabbir Kaskar</h1>

<p align="center">
  Full-Stack &amp; AI Engineer &nbsp;·&nbsp; Dublin, Ireland &nbsp;·&nbsp; Eligible to work in Ireland (Stamp 1G)
</p>

<p align="center">
  <a href="https://saimjs.com">Portfolio</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/saim-kaskar-34a6a4206">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:saimkaskar1@gmail.com">Email</a> &nbsp;·&nbsp;
  <a href="https://jobradar.saimjs.com">JobRadar AI</a>
</p>

---

```typescript
const saim: Developer = {
  name:       "Saim Shabbir Kaskar",
  base:       "Dublin, Ireland",
  education:  [
    "MSc Computing — Griffith College Dublin (2025)",
    "BEng Computer Engineering, Honours in AI & ML — CGPA 8.2",
  ],
  experience: "4 years · 15+ shipped production applications",
  flagship:   "JobRadar AI — agentic job search platform, live in production",
  aiStack:    ["LangChain", "LangGraph", "LangSmith", "Anthropic API", "OpenAI SDK"],
  dailyTools: ["Claude Code", "Cursor", "React", "TypeScript", "FastAPI"],
  contact:    "saimkaskar1@gmail.com",
};
```

I build full-stack products end to end — scoping, frontend, backend, deployment, and ongoing support. Four years of freelance work, 15+ production applications shipped for paying clients. Current focus: LLM/agentic systems and real-time web. New technology to production in 4–5 weeks.

---

## Flagship Projects

### JobRadar AI — Agentic Job Search Platform
**Live:** [jobradar.saimjs.com](https://jobradar.saimjs.com) · [Source](https://github.com/itsmesaim/jobRadarAI)

> Crawls live job postings, rates each one against your CV using an LLM, and tracks applications through a Kanban pipeline — all running on a VPS I manage myself.

| Layer | Detail |
|---|---|
| Backend | FastAPI + Python, async throughout |
| Frontend | React + TypeScript |
| AI | LangChain structured outputs (Pydantic), LangSmith tracing on every call |
| LLM Routing | Provider-agnostic: swap Ollama / OpenAI / xAI via a single env var |
| Performance | Embedding pre-filter (cosine similarity) eliminates LLM calls for irrelevant jobs; `asyncio.Semaphore` + `asyncio.gather` parallelises remaining ratings — 500+ jobs rated in seconds |
| Rating Logic | Two-stage disqualifier: structural mismatches (IC vs management, domain-as-core) separated from gradable skill gaps |
| Access | Freemium with daily quota reset, admin overrides, APScheduler automated crawl cycles |
| Infrastructure | VPS · Nginx · pm2 · SSL · GitHub webhook CI/CD |

---

### MeetX — Real-Time Video Platform
**Live:** [meetx.saimjs.com](https://meetx.saimjs.com) · [Source](https://github.com/itsmesaim/meetX)

> Full-stack video calling and screen-sharing platform, built solo end to end.

| Layer | Stack |
|---|---|
| Video | WebRTC peer connections + LiveKit SFU (bandwidth stays flat as rooms scale) |
| Signalling | Custom WebSocket layer for peer connection setup |
| Backend | Spring Boot (Java) — auth, sessions, REST |
| Frontend | React + TypeScript SPA, Jest unit tests |
| In Progress | LangChain/LangSmith: automatic transcription, AI session summaries, in-session Q&A chatbot with streaming responses |

---

### Automated Threat Detection for 6G Networks — MSc Dissertation
[Source](https://github.com/itsmesaim/AI-firewall)

Dual-layer ML classification backend with a human-in-the-loop retraining pipeline. Operator review decisions feed back as labelled training data so the model improves continuously post-deployment. React dashboard streams live threat events via WebSockets. Network simulation built in NS-3 (C++), modelled on published academic papers.

---

### Information Retrieval System
[Source](https://github.com/itsmesaim/RetrievalSystem)

Document retrieval engine built from scratch: TF-IDF matrix construction, inverted index, cosine similarity ranking. NLP preprocessing pipeline with NLTK and spaCy. No retrieval-library shortcuts — the same vector foundations underpinning modern RAG pipelines. Built as the capstone of a dedicated BEng Information Retrieval subject.

---

### More Projects

| Project | What it is |
|---|---|
| [LearnOS](https://github.com/itsmesaim/learning-dd) | Next.js 16 App Router + React 19 + Supabase + Framer Motion learning dashboard. Server Components fetch data (credentials never leave the server); Client Components handle animations. Parallel `Promise.all()` queries with Row Level Security. |
| [CipherHealth](https://github.com/itsmesaim) | Angular + Ethereum/Ganache/Web3.js blockchain hospital management system. Every record change is an immutable on-chain transaction. |
| [FastAPI Backend Suite](https://github.com/itsmesaim) | Three production REST APIs (F1 platform, financial management, task management). JWT auth, OpenAPI/Swagger, full CRUD. |
| [PONG-MERN](https://pong.saimjs.com) | Real-time multiplayer game. React + Node.js + Socket.IO. 60Hz server-authoritative physics loop, room-based matchmaking, reconnect handling, global leaderboard. |
| [AeroFlow](https://github.com/itsmesaim/AeroFlow) | Airport management system. Node.js + MongoDB + Socket.IO. Four-role JWT auth, QR boarding passes, MongoDB aggregation analytics. |
| B2B Industrial Platform | GraphQL + Express + MongoDB + Cloudinary backend, React + MUI admin panel, JWT + MFA (Google Authenticator) + RBAC three-layer security. Freelance, Middle East client. |

---

## Tech Stack

**Frontend**
React · Next.js · TypeScript · JavaScript (ES6+) · Tailwind CSS · shadcn/ui · React Query · Zustand · Angular · Framer Motion · Vite · Webpack

**Backend**
Node.js · Express · FastAPI · Spring Boot · Python · Java · Go

**AI & LLM**
LangChain · LangGraph · LangSmith · Anthropic API · OpenAI SDK · Pydantic structured outputs · provider-agnostic LLM routing · prompt engineering · LLM observability · async Python (asyncio)

**ML & NLP**
scikit-learn · NLTK · spaCy · TF-IDF · Vector Space Models · cosine similarity · ML model training & evaluation · pandas · numpy

**Databases**
MongoDB · MySQL · PostgreSQL · SQLite · Supabase (Postgres + RLS) · Firestore · Pinecone (vector DB)

**Real-Time**
WebRTC · LiveKit SFU · WebSockets · Socket.IO

**Cloud & DevOps**
AWS (EC2, S3) · Azure (ML pipeline deployment) · Docker · Docker Compose · GitHub Actions · webhook-based CI/CD · Nginx · VPS · pm2 · SSL · Vercel

**Security**
JWT · RBAC · MFA (Google Authenticator) · Row Level Security · GDPR awareness

**Other**
Figma · Jest · React Testing Library · GraphQL · Blockchain (Ethereum · Ganache · Web3.js) · WordPress · Shopify · Claude Code · Cursor

---

## Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=itsmesaim&show_icons=true&hide_border=true&count_private=true&theme=dark" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=itsmesaim&layout=compact&hide_border=true&langs_count=8&theme=dark" height="165" />
</p>

---

<p align="center">4 years · 15+ shipped products · building things that work</p>
