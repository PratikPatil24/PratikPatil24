<div align="center">

# Pratik Patil

### 🧠 Lead AI Engineer — I build the platform layer under AI products

**Agent orchestration** &nbsp;·&nbsp; **Knowledge base retrieval** &nbsp;·&nbsp; **Distributed systems at scale**

<br>

![Role](https://img.shields.io/badge/Lead%20AI%20Engineer-HighLevel-FF4D1C?style=for-the-badge&labelColor=0A0A0C)
![Location](https://img.shields.io/badge/Pune-India%20%C2%B7%20UTC%2B5%3A30-8A8A98?style=for-the-badge&labelColor=0A0A0C)
![Focus](https://img.shields.io/badge/Focus-Retrieval%20%26%20Agent%20Orchestration-3DDC84?style=for-the-badge&labelColor=0A0A0C)

</div>

---

## ⚡ Production numbers

<div align="center">

![KB retrieval](https://img.shields.io/badge/KB%20Retrieval-1M%2Fday-FF4D1C?style=for-the-badge&labelColor=0A0A0C)
![Documents](https://img.shields.io/badge/Documents%20Indexed-95M-FF4D1C?style=for-the-badge&labelColor=0A0A0C)
![Source types](https://img.shields.io/badge/KB%20Source%20Types-4-FF4D1C?style=for-the-badge&labelColor=0A0A0C)
![Latency](https://img.shields.io/badge/p95%20Latency-10s%20%E2%86%92%200.5s-FF4D1C?style=for-the-badge&labelColor=0A0A0C)

![Infra saved](https://img.shields.io/badge/Infra%20Saved-%24130k%2Fyr-FF4D1C?style=for-the-badge&labelColor=0A0A0C)
![Assistant users](https://img.shields.io/badge/Assistant%20Users-1.5%20lakh%2B-FF4D1C?style=for-the-badge&labelColor=0A0A0C)
![Behaviour change](https://img.shields.io/badge/Agent%20Behaviour%20Change-days%20%E2%86%92%20minutes-FF4D1C?style=for-the-badge&labelColor=0A0A0C)

</div>

> Every number above is measured, in production, and I can walk you through how.

---

## 🤖 Agent orchestration

**I architected a configurable agentic AI platform in 2023, when the managed ones you can buy today did not exist yet.**

- 🎛️ **Behaviour as configuration.** Prompts, LLM models, tools and profiles supplied through **APIs and message queues** instead of compiled in — changing an agent went from a **release cycle to minutes**, and stayed reviewable while it did.
- 🧩 **A 7-tool layer**, granted *per profile*: **RAG**, **API**, **Database**, **ClickHouse**, **Python** (sandboxed compute), **Events**, and **Transfer-to-human** — a production assistant is judged as much on when it declines as on when it answers.
- 📡 **Agents that do, not just talk.** Once an agent can emit an event it stops being a chat box and becomes a participant in the existing event-driven architecture.
- 👥 **1.5 lakh+ users** (150,000+) served across **WhatsApp**, an embeddable **SDK** and **Zendesk** — one engine, one config surface, **zero forks** between sales and operations.
- 🛡️ **Regulated domain.** Tool grants bound the blast radius of every capability — the whole safety argument is *what an agent is not allowed to do*.
- 🧑‍💼 **Tech-led a 3–4 engineer pod** and **hired the AI team end to end** — JDs, system-design and coding rounds, design docs, design reviews.

---

## 🔍 Retrieval at scale

**I own the AI Knowledge Base at HighLevel — a service, not a search box. It takes whatever a customer already has and turns it into answers every conversational and voice bot on the platform reads from.**

**What a knowledge base can be made of**

| Source | Modes | Ceiling per KB |
| :-- | :-- | :-- |
| 💬 **FAQs** | Authored question/answer pairs | — |
| 🌐 **Websites** | **Exact** (one URL) · **Path** (a subtree) · **Domain** (whole host) | **7,000 URLs** |
| 📊 **Tables** | CSV · Google Sheets | **50,000 rows** |
| 📄 **Files** | Markdown · PDF · Word/Docs | **~40 files** |

Every source is parsed, chunked and embedded into **one retrieval model**, so nothing downstream needs to know whether an answer came from a PDF or row 4,812 of a spreadsheet.

- 🚀 **1M retrieval calls/day** across **95M documents** at **sub-second p95**.
- ⏱️ **10s → 0.5s.** Led the migration of **54M+ documents** from MongoDB to OpenSearch — the change that moved retrieval from a ten-second p85 to a sub-second p95.
- 💸 **~$130k/yr** off the infra bill from that same migration. Faster *and* cheaper.
- 🕸️ **A crawl scheduler with a floor and a ceiling.** Peak budget of **2,000 URLs per mode**; every tenant gets a **50-slot floor** so small accounts are never starved, and a **40% ceiling** so no one takes the crawler hostage. **200k+ requests/day**, fairly shared.
- 🦆 **200 MB CSVs, never loaded into memory.** Signed URLs → **GCS** → **DuckDB** → **Parquet** streaming, so peak memory is a function of the query rather than the file — no separate fleet sized for the worst spreadsheet anyone uploads.
- 📈 **Retrieval-quality instrumentation**, built with product and customer-success teams — so "is retrieval actually better?" is answered with numbers rather than opinions.
- ⚙️ **Standardised logging and tuned HPA.** Consistent structure and correlation so an incident is one query, not an archaeology expedition; autoscaler thresholds matched to the real load shape rather than a peak that rarely arrives.

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
| 🔍 **[A knowledge base service](https://pratikpatil24.github.io/work/ai-knowledge-base)** | FAQs, websites, tables and files → 95M documents, 10s p85 to sub-second p95 | **1M calls**/day |
| 🧮 **[Policy documents into structured data](https://pratikpatil24.github.io/work/policy-data-extraction)** | Multi-tenant extraction and reconciliation that fail loudly, not silently | **2,000+ policies**/day |
| ⛓️ **[Four products on public chains](https://pratikpatil24.github.io/work/onchain-insurance)** | Led end to end at CakeSoft — marketplace, exchange, mass payments, games | **4 products** led |

---

## 🌱 Currently

- 🔬 Retrieval-quality instrumentation, and agent tool design that bounds blast radius
- 🕸️ Ingest throughput — a slot-scheduled crawler at **200k+ requests/day** across tenants
- 🧪 LangGraph orchestration and the eval harness that makes it shippable
- 💬 **Always up for a conversation** about retrieval, agent orchestration, or getting an LLM prototype to something you can actually run in production

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
