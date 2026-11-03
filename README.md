<h1 align="center">Enes Taner</h1>

<p align="center">
  <b>AI Engineer · LLM applications, RAG &amp; multi-agent systems</b><br>
  İstanbul, Türkiye · working remotely since 2024
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/enes-taner-312268155/">LinkedIn</a> ·
  <a href="https://github.com/enestanerr/Amber">Amber</a>
</p>

I build production LLM systems (RAG pipelines, multi-agent architectures, intelligent document processing) and the tooling that makes agents cheaper and more predictable to run. I lead project delivery for the AI department at **Intellity** and stay hands-on as a developer on every project.

-  Building **[Amber](https://github.com/enestanerr/Amber)** in public: a compiler that turns repeated Claude Code runs into tested Python programs.
-  Focus: agent reliability (guardrails, drift detection, human-in-the-loop), structured outputs, LLM cost and latency.
-  Turkish (native) · English (B2)
-  Always happy to talk about agents, RAG and LLM tooling. Reach me on [LinkedIn](https://www.linkedin.com/in/enes-taner-312268155/).

## Featured open source

| Project | What it does | Stack |
|:--|:--|:--|
| **[Amber](https://github.com/enestanerr/Amber)** | Compiles repeated agent runs into readable, tested Python programs: plain code for the mechanical steps, a small `llm()` call where judgment is needed, and guards that hand the task back to the agent when inputs drift. 5.9–12.9× fewer tokens per run on its benchmark workflows. | Python · Claude Agent SDK · MCP |
| **[Simpaper](https://github.com/enestanerr/Simpaper)** | A free, local-first office suite for Windows with an Office-style ribbon (documents, spreadsheets, presentations and PDF) built on the unmodified LibreOffice engine. 1,000+ automated tests. *Early development.* | TypeScript · Electron |
| **[LocalFlow](https://github.com/enestanerr/LocalFlow)** | Batch image workflows in the browser (resize, crop, convert, rename) that run entirely on-device, with reusable JSON recipes. | TypeScript · Next.js |
| **[Prompt&nbsp;Pad](https://github.com/enestanerr/Prompt-Pad)** | A Windows notebook for LLM prompts; screenshots pasted with `Ctrl+V` are saved losslessly next to each prompt. | JavaScript · Electron |

## Selected production work

<sub>Private codebases built for clients and employers.</sub>

- **Agentic e-commerce decisioning platform** (lead architect): 17+1 autonomous agents for customer-behaviour analysis and automated decisions, including RFM segmentation, LTV, churn, dynamic bundling and win-back. Every decision passes a guardrail veto and an arbiter before it reaches a single-writer decision log. Python/FastAPI, PostgreSQL, Temporal.io, vLLM, Next.js.
- **Multi-user local RAG service**: parallel ingestion and querying on FastAPI + Ray, embedding retrieval with CrossEncoder reranking, answers grounded in database records.
- **Intelligent document processing**: schema-driven (Pydantic) extraction from heterogeneous documents with generative models, offline-capable.
- **Email intelligence**: tasks and assignments extracted from email with generative AI and NER, served as structured JSON.
- **AI-powered OKR & performance platform**: Go REST API with a dual-mode AI module (local or hosted LLM) for performance prediction from 50+ features, risk analysis and KPI suggestions.
- **Multi-agent content pipeline**: ingestion → drafting → fact verification and compliance checks → editing → SEO, orchestrated in Next.js/TypeScript.

## Tech stack

- **Languages:** Python · TypeScript / JavaScript · Go · SQL
- **LLMs & agents:** OpenAI and Claude APIs · Claude Agent SDK · MCP · LangChain · tool calling · structured outputs (Pydantic) · multi-agent orchestration · guardrails and human-in-the-loop
- **RAG & NLP:** embedding pipelines · vector search · CrossEncoder reranking · NER · Hugging Face Transformers · sentence-transformers · vLLM
- **Backend & data:** FastAPI · Ray · Temporal.io · PostgreSQL · MSSQL · Prisma · GORM · event-driven architecture
- **Frontend & desktop:** React · Next.js · Electron
- **DevOps:** Docker · GitHub Actions · Linux

## Background

- **Intellity Artificial Intelligence Solutions:** AI Project Manager & Developer, AI Department (2025–present) · AI Developer (2024–2025)
- **N Creative Design Studios:** Web & AI Developer (2025)
- **İstanbul Medipol University:** B.Sc. Management Information Systems, English-medium (2019–2023)
