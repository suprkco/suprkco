# Kilian Codaccioni

EPF engineering graduate in digital technology and data, and ESSEC graduate.
Focused on applied generative AI, data systems and business transformation.
Seeking generative AI and data consulting opportunities in New York.

[LinkedIn](https://www.linkedin.com/in/codaccioni-kilian/) · [GitHub](https://github.com/suprkco)

## Start here

Four focused prototypes: inspectable evidence, constrained tools, human review and typed decisions. Each includes runnable examples, tests, CI and explicit limitations.

| Project | What to inspect | Validation and scope |
| --- | --- | --- |
| **[EU AI Act Evidence Explorer](https://github.com/suprkco/rag-eu-ai-act)** | Terminal interface + FastAPI, source citations, BM25 baseline, optional Ollama/pgvector adapters | 20/20 development questions hit the expected article in the top 5 chunks; not a held-out legal QA benchmark |
| **[MCP SQL Analytics](https://github.com/suprkco/mcp-sql-analytics)** | Real MCP stdio server, read-only SQLite policy, bounded queries | 24 tests, including protocol integration and denied writes; synthetic retail data |
| **[Market Scout Agents](https://github.com/suprkco/market-scout-agents)** | LangGraph specialist roles, evidence checks and persistent human review | 9 workflow tests; default fixture mode, optional model calls |
| **[Jev SERP Opportunity Lab](https://github.com/suprkco/jev-serp-opportunity-lab)** | Typed intent judgments, explicit uncertainty routing, terminal reports | 13 contract/policy tests; Jev live performance not yet measured |

**[Read the Jev terminal transcript](https://suprkco.github.io/jev-serp-opportunity-lab/)** — clearly labeled synthetic inputs and simulated responses, no API key required.

## Stack used in this portfolio

Python · SQL · FastAPI · Pydantic · Next.js / TypeScript · MCP · LangGraph · PostgreSQL / pgvector · SQLite · Docker · pytest · Playwright · GitHub Actions

## Engineering approach

- Keep source provenance and make results reproducible.
- Enforce tool permissions in code and the database, not in prompts alone.
- Separate deterministic tests from model-quality evaluations.
- Make review and failure paths visible.

The projects are AI-assisted portfolio prototypes, not client engagements or production deployments. Model integrations and unmeasured results are identified in each README. The RAG project includes an attributed comparison harness for [HKUDS/LightRAG](https://github.com/HKUDS/LightRAG); upstream research and code remain credited to their authors.

## Earlier work

[Python country-data comparison](https://github.com/suprkco/Comparaison-des-indemnit-s-de-VIE-par-pays) · [Trading simulation](https://github.com/suprkco/Trading-strategies-analysis-regret-minimization) · [Java RentManager](https://github.com/suprkco/Projet_RentManager)
