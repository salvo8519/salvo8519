### Salvatore Miseo

AI developer. I bring AI into how companies actually work, and take it to
production: agentic pipelines, RAG systems, AI gateways and integrations with
ERP, WMS and TMS.

I start from the process. As a functional analyst I redesigned business
processes for digital in more than 20 client projects. Before that, I spent a
decade in finance and real estate: credit analysis for SMEs, risk and
valuation of a property portfolio worth around 5 billion euro, investment
analysis, business plans for complex developments. That background shapes how
I build software: results must be exact, traceable and worth what they cost.

#### What I work on

- **Agentic pipelines in production** - a multi-tenant platform that reconciles
  supplier invoices, orders and proofs of delivery against ERP costs, with LLMs
  as the decision engine and a human in the loop.
- **Enterprise integrations** - APIs and connectors towards ERP, WMS and TMS,
  built on versioned data contracts, layers and adapters.
- **Document AI** - agentic extraction from complex documents; research for a
  project funded by the iNEST programme (PNRR) on AI for document management.

I work spec-driven and contract-first, in sprints.

#### Private projects

**AI workflow orchestration platform** - in progress, moving towards
maturity. Automation workflows served as enterprise-grade APIs: a workflow
enters a registry and becomes an authenticated endpoint, with grants,
multi-level quotas, durable executions and retries. Contracts on input,
output and lifecycle; usage metered in units of work for billing; audit and
GDPR pseudonymisation; white-label per company. The automation engine is a
configuration choice, plugged in through adapters. Next: structured document
parsing, and personal-data anonymisation, which I plan to release as a
separate open-source service written in Rust.

**Enterprise help desk with RAG** - multi-tenant knowledge platform for
companies and departments, with role-based access, a knowledge base hub and
an AI help desk agent. FastAPI, React. Working MVP; next step is moving the
vector store to Qdrant.

**Enterprise authentication service** - designed together with its
security, architecture and GDPR analyses, including a record of processing
activities. FastAPI.

#### Open source

**[Fairmark](https://github.com/salvo8519/fairmark)** - Deterministic valuation
engine for analysts and AI agents. The model reads and writes, Fairmark does
the math: exact, reproducible, traceable. Rust core, Python SDK, MCP.
[Docs](https://salvo8519.github.io/fairmark/) ·
[PyPI](https://pypi.org/project/fairmark/) ·
[crates.io](https://crates.io/crates/fairmark-core)

**[Wayloop](https://github.com/salvo8519/wayloop)** - Spec-driven agentic loop
for whole software projects: from idea to merged code, in your issues, with
humans at the gates. Rust core. Pre-alpha.
[Docs](https://salvo8519.github.io/wayloop/)

#### Stack

Python (FastAPI, asyncio) · Rust · PostgreSQL · Redis · Celery / RabbitMQ ·
Docker · LangGraph · LangChain · LiteLLM · Langfuse · Qdrant / pgvector · MCP

#### Background

Master in Real Estate Finance, SDA Bocconi – MIP Politecnico di Milano ·
Degree in Economics and Business Administration, University of Salerno

#### Contact

[LinkedIn](https://www.linkedin.com/in/salvatore-miseo-72881a134) ·
Salerno, Italy · Italian, English
