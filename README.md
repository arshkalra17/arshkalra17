# Hi, I'm Arsh 

I build **backend systems and AI-powered applications** that go beyond model demos — with APIs, databases, asynchronous processing, orchestration, authentication, evaluation, and observability.

**Currently building RAG and agentic AI systems with a focus on reliability, evaluation, and clean system design.**

---

## What I Work With

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,typescript,js,fastapi,flask,react,pytorch,tensorflow,postgresql,mongodb,redis,docker,aws,linux,git" />
</p>

---

## What I'm Building

### [SupportFlow](https://github.com/arshkalra17/SupportFlow---AI-Ticket-Automation)
AI customer-support backend where **the model only proposes and the backend decides**. Every tool call the LLM suggests passes four gates before anything changes: schema validation, ownership authorization, deterministic business rules, and execution under a row lock.

- **Orchestration:** LangGraph, with human-in-the-loop approval (`interrupt()` resumed from a Postgres checkpoint) for refunds over $1,000
- **RAG:** PostgreSQL + pgvector, section chunking, cross-encoder reranking, cited answers
- **LLMs:** Groq (gpt-oss-120b / 20b) as primary, Gemini as fallback, with a circuit breaker
- **Safety:** JWT auth, idempotency keys, an action guard that blocks state changes made in answer to questions, Redis rate limiting and token budgets
- **Async:** Redis job queue with retries and a dead-letter list
- **Observability:** OpenTelemetry traces viewed in Jaeger
- **Evaluation:** 167-case golden dataset with 0 forbidden-tool calls, plus 1,400+ automated tests

<p align="center">
  <img src="https://raw.githubusercontent.com/arshkalra17/SupportFlow---AI-Ticket-Automation/main/docs/images/request-flow.png" width="480" alt="SupportFlow request flow" />
</p>

> **LLM proposes. Backend decides.**

### [QueryLens](https://github.com/arshkalra17/QueryLens--AI-Data-Analyst)
Natural-language data analyst: ask a question, get verified SQL and an answer.

- **RAG + text-to-SQL:** embeddings retrieve schema context; the model writes SQL, the backend executes it
- **Safe execution:** DuckDB sandbox with a query timeout and a self-repair loop for failed queries
- **Evaluation:** 80-case execution-accuracy benchmark, with tuned and blind held-out results reported separately

---

## Other Projects

- 🏗️ **StructScan** — structural damage detection with YOLOv8, OpenCV, Flask and PyTorch
- 🎮 **Game Engine** — a renderer built from scratch, mostly for fun

---

## Engineering Interests

**Backend**
- API design
- Database systems
- Authentication & authorization
- Distributed / asynchronous systems
- Concurrency & idempotency
- Observability
- System design

**AI / ML**
- LLM applications
- Agentic workflows
- RAG
- Computer vision
- Model evaluation
- AI + backend integration

---

## GitHub Galaxy 🌌

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=arshkalra17&theme=tokyonight" />
</p>

---

## Contact me @
- 📫 **arshkalra17@gmail.com**


<p align="right">
  <img src="https://komarev.com/ghpvc/?username=arshkalra17&color=green&style=flat-square&label=PROFILE+VIEWS" />
</p>
