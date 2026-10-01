# Kilian Codaccioni

EPF engineering graduate in digital technology and data, and ESSEC graduate.
Focused on applied generative AI, data systems and business transformation.
Seeking junior consulting opportunities in applied AI and data, open to international roles.

[LinkedIn](https://www.linkedin.com/in/codaccioni-kilian/) · [GitHub](https://github.com/suprkco)

## Start here

Start with **Market Scout**: a real local language model, dated public-source briefs, a paired single-call comparison, and published failure cases. The other prototypes demonstrate constrained tools, retrieval and typed decisions.

| Project | What to inspect | Validation and scope |
| --- | --- | --- |
| **[Market Scout Agents](https://github.com/suprkco/market-scout-agents)** | Terminal workflow, LangGraph roles, exact-quote checks and persistent human review | Qwen2.5-0.5B on 6 public-source cases: 9/9 exact quotes; AI-assisted inspection found 3 contradictory implications. Critic adds latency without demonstrated accuracy gain |
| **[EU AI Act Evidence Explorer](https://github.com/suprkco/rag-eu-ai-act)** | Terminal + FastAPI, BM25, optional pgvector, real local generation experiment | New challenge: 8/8 article hits, 0/4 near-domain retrieval abstentions; publishes model hallucinations despite valid citation IDs |
| **[MCP SQL Analytics](https://github.com/suprkco/mcp-sql-analytics)** | Real MCP stdio server, read-only SQLite policy, bounded queries | 24 tests, including protocol integration and denied writes; synthetic retail data |
| **[Jev SERP Opportunity Lab](https://github.com/suprkco/jev-serp-opportunity-lab)** | Typed intent judgments, explicit uncertainty routing, terminal reports | 13 contract/policy tests; Jev live performance not yet measured |

**[Market Scout case study](https://github.com/suprkco/market-scout-agents/blob/main/docs/case-study.md)** · **[Three-minute terminal replay](https://github.com/suprkco/market-scout-agents/blob/main/docs/demo.gif)**

[Jev terminal transcript](https://suprkco.github.io/jev-serp-opportunity-lab/): synthetic inputs and simulated responses, no API key required.

## Stack used in this portfolio

Python · SQL · FastAPI · Pydantic · Next.js / TypeScript · MCP · LangGraph · PostgreSQL / pgvector · SQLite · Docker · pytest · Playwright · GitHub Actions

## Engineering approach

- Keep source provenance and make results reproducible.
- Enforce tool permissions in code and the database, not in prompts alone.
- Separate deterministic tests from model-quality evaluations.
- Make review and failure paths visible.

The projects are AI-assisted portfolio prototypes, not client engagements or production deployments. Model integrations and unmeasured results are identified in each README. The RAG project includes an attributed comparison harness for [HKUDS/LightRAG](https://github.com/HKUDS/LightRAG); upstream research and code remain credited to their authors.

## Online learning

[Online Regret Lab](https://github.com/suprkco/Trading-strategies-analysis-regret-minimization): terminal-first Hedge experiments, explicit external regret, four causal experts and 80 reproducible synthetic runs. Includes 18 tests; no real-market profitability claim.

## Distributed compute experiment

[Adaptive Inference Network](https://github.com/suprkco/Blockchain-adaptive-inference-network): trained MiniLM embeddings split across two CPU workers, compared with local inference and local EVM receipts. Publishes 60 latency samples, equivalence checks, injected failures and a research white paper; no trustless-inference or multi-machine performance claim.

## Earlier work

[Python country-data comparison](https://github.com/suprkco/Comparaison-des-indemnit-s-de-VIE-par-pays) · [Online Regret Lab](https://github.com/suprkco/Trading-strategies-analysis-regret-minimization) · [Java RentManager](https://github.com/suprkco/Projet_RentManager)
