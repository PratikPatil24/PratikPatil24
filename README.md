<div align="center">

# Pratik Patil

### 🧠 Lead AI Engineer — I build the platform layer under AI products

**Agent orchestration** &nbsp;·&nbsp; **Knowledge base retrieval** &nbsp;·&nbsp; **Distributed systems at scale**

<br>

![Role](https://img.shields.io/badge/Lead%20AI%20Engineer-HighLevel-FF4D1C?style=for-the-badge&labelColor=0A0A0C)
![Location](https://img.shields.io/badge/Pune-India%20%C2%B7%20UTC%2B5%3A30-8A8A98?style=for-the-badge&labelColor=0A0A0C)
![Open to](https://img.shields.io/badge/Open%20to-Lead%20%2F%20Staff%20AI%20Platform-3DDC84?style=for-the-badge&labelColor=0A0A0C)

</div>

---

## ⚡ Production numbers

<div align="center">

![KB retrieval](https://img.shields.io/badge/KB%20Retrieval-1M%2Fday-FF4D1C?style=for-the-badge&labelColor=0A0A0C)
![Documents](https://img.shields.io/badge/Documents%20Indexed-95M-FF4D1C?style=for-the-badge&labelColor=0A0A0C)
![Latency](https://img.shields.io/badge/p95%20Latency-10s%20%E2%86%92%200.5s-FF4D1C?style=for-the-badge&labelColor=0A0A0C)

![Infra saved](https://img.shields.io/badge/Infra%20Saved-%24130k%2Fyr-FF4D1C?style=for-the-badge&labelColor=0A0A0C)
![Assistant users](https://img.shields.io/badge/Assistant%20Users-1.5%20lakh%2B-FF4D1C?style=for-the-badge&labelColor=0A0A0C)
![Behaviour change](https://img.shields.io/badge/Agent%20Behaviour%20Change-days%20%E2%86%92%20minutes-FF4D1C?style=for-the-badge&labelColor=0A0A0C)

</div>

> Every number above is measured, in production, and I can walk you through how.

---

## 🤖 Agent orchestration

**I architected a configurable agentic AI platform — before agent platforms were a product category.**

- 🎛️ **Behaviour as configuration.** Prompts, LLM models, tools and profiles supplied through **APIs and message queues** instead of compiled in — changing an agent went from a **release cycle to minutes**, and stayed reviewable while it did.
- 🧩 **A 7-tool layer**, granted *per profile*: **RAG**, **API**, **Database**, **ClickHouse**, **Python** (sandboxed compute), **Events**, and **Transfer-to-human** — a production assistant is judged as much on when it declines as on when it answers.
- 📡 **Agents that do, not just talk.** Once an agent can emit an event it stops being a chat box and becomes a participant in the existing event-driven architecture.
- 👥 **1.5 lakh+ users** (150,000+) served across **WhatsApp**, an embeddable **SDK** and **Zendesk** — one engine, one config surface, **zero forks** between sales and operations.
- 🛡️ **Regulated domain.** Tool grants bound the blast radius of every capability — the whole safety argument is *what an agent is not allowed to do*.
- 🧑‍💼 **Tech-led a 3–4 engineer pod** and **hired the AI team end to end** — JDs, system-design and coding rounds, design docs, design reviews.

---

## 🔍 Retrieval at scale

**I own the AI Knowledge Base at HighLevel — the retrieval layer behind every conversational and voice bot on the platform.**

- 🚀 **1M retrieval calls/day** across **95M documents** at **sub-second p95**.
- ⏱️ **10s → 0.5s.** Led a **54M-document** migration from MongoDB to OpenSearch on live traffic — dual-write, then a per-tenant read cutover so any blast radius was one account, not the platform.
- 💸 **~$130k/yr** off the infra bill from that same migration. Faster *and* cheaper.
- 🕸️ **200k+ crawl requests/day.** Slot-based, account-level scheduling for a Playwright crawler, with back-pressure — a pathological site slows down its own tenant and nobody else's.
- 🦆 **DuckDB over GCS streaming** for 250 MB / 100k-row tables, so peak memory is a function of the query, not the file.
- 📈 **Retrieval-quality instrumentation** built *before* the cutover — which is the only reason the migration could be signed off on numbers instead of opinions.

---

## 🧰 Stack

**AI & orchestration**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square)
![Azure OpenAI](https://img.shields.io/badge/Azure%20OpenAI-0078D4?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-444?style=flat-square)
![Vector search](https://img.shields.io/badge/Vector%20search-444?style=flat-square)
![LLM evals](https://img.shields.io/badge/LLM%20evals-444?style=flat-square)
![Agent tooling](https://img.shields.io/badge/Agent%20tooling-444?style=flat-square)

**Languages & services**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

**Data & search**

![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)

**Platform**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square)

---

## 📌 Selected work

| | What it was | The number |
| :-- | :-- | :-- |
| 🤖 **[Agent orchestration as configuration](https://pratikpatil24.github.io/work/configurable-agent-platform)** | A profile-driven agent platform with a 7-tool layer, built before that was a category | **days → minutes** to change behaviour |
| 🔍 **[Retrieval at a million calls a day](https://pratikpatil24.github.io/work/ai-knowledge-base)** | 95M documents, rebuilt from a 10s p85 to a sub-second p95 | **~$130k/yr** saved |
| 🧮 **[Policy documents into structured data](https://pratikpatil24.github.io/work/policy-data-extraction)** | Multi-tenant extraction and reconciliation that fail loudly, not silently | **2,000+ policies**/day |
| ⛓️ **[Four products on public chains](https://pratikpatil24.github.io/work/onchain-insurance)** | Led end to end at CakeSoft — marketplace, exchange, mass payments, games | **4 products** led |

---

## 🌱 Currently

- 🔬 Retrieval-quality instrumentation, and agent tool design that bounds blast radius
- 🕸️ Ingest throughput — a slot-scheduled crawler at **200k+ requests/day** across tenants
- 🧪 LangGraph orchestration and the eval harness that makes it shippable
- 💬 **Open to Lead / Staff AI platform roles** — remote, or hybrid in Pune

---

## 🏆 Along the way

🥇 **Winner, Smart India Hackathon 2020** — first prize on the Bajaj Finserv problem statement, from **130+ national submissions**
🏅 **Best Innovation Award**, Smart India Hackathon 2018
🎓 **B.E. Computer Engineering**, PICT Pune — **CGPA 9.19**
👑 **Chairman, PICT ACM Student Chapter** — recognised **Best ACM Student Chapter in India, 2018**

---

<div align="center">

### 🤝 Let's talk about something hard

[![Portfolio](https://img.shields.io/badge/Portfolio-pratikpatil24.github.io-FF4D1C?style=for-the-badge&labelColor=0A0A0C)](https://pratikpatil24.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&labelColor=0A0A0C)](https://www.linkedin.com/in/pratikpatil24/)
[![Email](https://img.shields.io/badge/Email-patilgpratik%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0A0A0C)](mailto:patilgpratik@gmail.com)

<sub>Usually replies within a day</sub>

</div>
