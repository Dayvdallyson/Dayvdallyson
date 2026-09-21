<div align="center">

# Dayvd Costa

**Tech Lead & Backend Software Engineer**

Distributed Systems · Event-Driven Architecture · Python · LLMs & Agentic Systems

<br>

Building scalable, event-driven backend platforms for fintech — and extending them with production-grade RAG and multi-agent systems.

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dayvd-allyson-273a41232/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dayvdallyson21@gmail.com)
[![Location](https://img.shields.io/badge/Rio_de_Janeiro,_BR-Remote-2A2F45?style=for-the-badge)](#)

</div>

---

## ✨ About Me

* 🏗️ Backend engineer with **5+ years shipping production systems end-to-end** — cloud-native, event-driven backends through to multi-agent LLM systems
* 📈 Grew at **Dotless** from Software Engineer to **Tech Lead**, now leading engineering on an AI-powered fintech product
* 💳 Own architecture decisions on an **AI-powered financial-advisory SaaS**, integrating Open Finance (Pluggy) for secure, real-time bank-data ingestion
* ⚡ Design **Kafka + Redis + PostgreSQL** pipelines that process financial transactions at scale
* 🤖 Shipped **three multi-agent systems to production this year** — orchestration, tool calling, RAG, observability
* 🎯 Care about the parts most AI demos skip: retrieval quality, cost/latency trade-offs, observability, and knowing when *not* to reach for an LLM

---

## 🤖 AI Systems I've Shipped

<table>
<tr>
<td width="33%" valign="top">

### 🎧 Multi-Agent Customer Support

Supervisor, Order, Refund, and Knowledge agents resolving customer requests end-to-end — stock lookups, policy RAG, payment API calls, refunds, and human escalation.

`FastAPI` `LangGraph` `pgvector`
`Redis` `Kafka` `AWS`

</td>
<td width="33%" valign="top">

### 🔍 Research & Reporting Pipeline

Planner → specialist agents (web research, data analysis, competitor) → Critic → Writer, turning open questions into evidence-backed reports with per-claim source and confidence tracking.

`Python` `LangGraph` `RAG`
`SQL tools` `AWS`

</td>
<td width="33%" valign="top">

### 🚨 Incident-Response Agent

Diagnoses production incidents from metrics/logs/traces, forms and tests hypotheses, executes fixes with human-in-the-loop approval on high-risk actions.

**Diagnosed a Redis pool-exhaustion incident, cutting error rate 31.8% → 0.7%.**

`Python` `Kafka` `Redis`
`PostgreSQL` `RAG` `AWS`

</td>
</tr>
</table>

---

## 💻 Core Tech Stack

### Backend & Distributed Systems
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)

Event-driven microservices, Celery background tasks, REST API design (pagination, rate limiting, auth), Swagger/OpenAPI, automated testing, SOLID.

### Data & Messaging
![Postgres](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

PostgreSQL + pgvector (relational modeling, vector search, indexing, performance tuning), high-throughput event streaming with Kafka, caching/queues/sessions with Redis.

### AI / LLM Engineering
![Anthropic](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)

Anthropic (Claude) & OpenAI APIs, tool/function calling, structured outputs, RAG (chunking, retrieval, re-ranking), multi-agent orchestration with LangGraph, prompt engineering, model evaluation & benchmarking, Whisper.

### Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

AWS (SQS, SNS, Lambda, RDS, S3, ECS, EKS, IAM), Docker/Docker Compose, CI/CD via GitHub Actions, Linux.

### Financial Systems & Integrations
Open Finance / Pluggy, Stripe, DocuSign, SendGrid, Google OAuth — transaction processing and financial-data ingestion pipelines.

### Frontend (when the product needs it)
![Next.js](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

React/Next.js, Vite, TanStack Query, TypeScript, Tailwind, Radix.

---

## 🧭 Experience

### Dotless — Tech Lead *(previously Software Engineer)*
`2021 – Present` · Remote · AI-powered financial-advisory SaaS

Grew within the company from Software Engineer to Tech Lead: now own architecture decisions, align requirements with stakeholders, and guide the team through delivery.

* Designed and shipped **RAG pipelines and an AI chatbot automation** on the Anthropic (Claude) and OpenAI APIs, grounding advisory workflows in clients' real financial data
* Integrated **Pluggy (Open Finance)** for secure bank-account connection and automated financial-data ingestion; built the platform full-stack (React/Vite/TanStack Query, Node.js/Express, PostgreSQL/Drizzle ORM)
* Championed **testing and engineering best practices** across the platform — automated unit/integration suites, code review, CI/CD — while designing REST APIs and running Docker-containerized services with Redis caching and Kafka-based event streaming
* Built the **three multi-agent AI systems** described above, extending the platform's automation and customer-support capabilities

### Realtor — Backend Software Engineer
`2020 – 2021` · Real-estate brokerage platform

* Built full-stack features (Django, Python, PostgreSQL), containerized with Docker; clean, testable code following SOLID
* Improved frontend performance and accessibility with React / Next.js, TypeScript, Tailwind

---

## 🎓 Education & Languages

**B.Sc. in Computer Science** · 2022 – 2025

🇧🇷 Portuguese (native) · 🇺🇸 English (highly proficient)

---

<div align="center">

### ✍️ Dev Quote

> ### *"You can't learn everything, but you have to convince yourself that you can learn anything."*
>
> **— John Carmack**

</div>

---
