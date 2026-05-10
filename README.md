<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Chinmay%20Karkamkar&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%7C%20Builder%20%7C%20Final-Year%20CS%20(Data%20Science)&descAlignY=58&descSize=18" width="100%"/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chinmay-karkamkar-a109b72b2/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ChinmayKarkamkar12)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:chinmaykarkamkar12@gmail.com)

</div>

---

## 👋 About Me

I'm a final-year **B.Tech CSE (Data Science)** student at **Dayananda Sagar University, Bengaluru** (CGPA: 8.51), building real-world AI systems that go beyond prototypes.

Previously an **AI Engineer Intern at OutMate** — where I designed and shipped 12 production AI features across a full-stack GTM platform: agentic tool-use loops, SSE streaming pipelines, RAG-based chatbots, LLM orchestration with topological scheduling, and real-time Redis pub-sub notifications.

I'm interested in **agentic AI**, multi-agent systems, and building automation that actually works in production.

- 🔭 **Currently:** Multi-agent AI system for agricultural supply chain optimization (LangGraph, 6-agent architecture)
- 🌱 **Exploring:** LLM orchestration, RAG pipelines, self-hosted automation (n8n, Ollama)
- 📍 **Location:** Bengaluru, India

---

## 🛠️ Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)

### AI / ML / Agents
![Claude API](https://img.shields.io/badge/Claude%20API-CC785C?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6B4FBB?style=for-the-badge&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

### Backend & Frontend
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

### Tools & Cloud
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

---

## 💼 Experience

### AI Engineer Intern — OutMate *(2024)*
> AI-powered GTM assistant for sales teams — Next.js 14 · FastAPI · Celery · Redis · Supabase · Claude API · OpenRouter

Designed and shipped **12 production AI features** end-to-end across the full stack:

**🤖 Automation Agent** — Claude tool-use API agent with 20+ JSON schema tool definitions. Navigation and filter injection run client-side (zero backend latency). Built a Zustand `submitSignal` pattern for form auto-submit without prop-drilling, and a filter undo stack for state rollback.

**🎯 Orchestrator** — LLM planner generates an `ExecutionPlan`; topological sort on `step.depends_on` resolves parallel groups; `asyncio.gather` executes groups concurrently; merger LLM synthesises all outputs. Full audit log persists plan, steps, credits, and duration per run.

**💬 Global Chatbot (RAG)** — RAG over 51KB feature docs; route-aware with 19-route feature registry injected per request; two-stage intent detection (keyword pre-filter → LLM classifier at temp=0.0); `_validate_links()` post-processor strips hallucinated URLs.

**⚡ Lead Copilot Panel** — 14 GTM AI actions (email drafting, objection handling, competitive battle cards, compliance audit, intent scoring). 2-stage SSE streaming with token batching (50ms flush) reduced React re-renders from ~700 to ~15. Redis cache keyed by `action:prospect_id:sha256(prompt)[:8]` for input-dependent cache isolation.

**📧 Email Optimizer** — 5-source parallel enrichment via `asyncio.gather` (Serper, Tavily, Explorium, LinkedIn, YouTube) with 15s per-source timeout isolation. Outputs personalised email + Day 3/7/14 follow-up sequence + reply probability score.

**🔔 Real-time Notifications** — Redis pub-sub → SSE; manual JWT validation on SSE endpoints (browser `EventSource` can't set auth headers); 25s heartbeat; `grouped_count` deduplication to prevent notification spam.

**📅 Scheduling** — Celery Beat for timezone-aware Daily Brief (±2-min window, idempotent `get_or_generate()`); Meeting Prep auto-triggers at T-30 via Google Calendar webhooks + Redis dedup key (2hr TTL).

---

## 🚀 Projects

### 🌾 Unysis AgentFarm *(Hackathon)*
> Multi-agent AI system for agricultural supply chain optimization in India

- 6-agent LangGraph architecture covering demand forecasting, logistics, pricing, and farmer advisory
- Handles real supply chain data across Karnataka and Maharashtra farm networks
- Stack: Python, LangGraph, LLM APIs, FastAPI

### 📈 Customer Lifetime Value Prediction
> End-to-end ML pipeline with production-grade tooling

- CLV prediction model with full MLOps setup — FastAPI + Docker, monitored via MLflow + Evidently AI
- Interactive Streamlit dashboard for business users
- [Repo →](https://github.com/ChinmayKarkamkar12/CLV-prediction)

### 🐦 Bird Audio Classification Pipeline
> Dual-domain academic research project

- Noise-aware bird audio classification using BirdNET and IBC53 dataset
- Produced two research papers (signal processing & transfer learning tracks)
- Stack: Python 3.11, TensorFlow 2.18, birdnet-analyzer, 48kHz mono WAV

---

## 🏆 Certifications

| Certification | Issuer |
|---|---|
| Microsoft Certified: Azure Data Fundamentals (DP-900) | Microsoft |
| Data Science Professional Certificate | IBM |
| Google Data Analytics Professional Certificate | Google / Coursera |
| MySQL Certification | Scaler |

---

## 📊 GitHub Stats

<div align="center">

![Chinmay's GitHub Stats](https://github-readme-stats.vercel.app/api?username=ChinmayKarkamkar12&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=7c5cbf&icon_color=7c5cbf&text_color=c9d1d9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ChinmayKarkamkar12&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=7c5cbf&text_color=c9d1d9)

![GitHub Streak](https://streak-stats.demolab.com/?user=ChinmayKarkamkar12&theme=tokyonight&hide_border=true&background=0d1117&ring=7c5cbf&fire=7c5cbf&currStreakLabel=c9d1d9)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>

*Open to AI/ML internships and full-time roles. Let's build something impactful.*

</div>
