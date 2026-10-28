# Kilian Codaccioni

Engineer (EPF, digital technology and data) and ESSEC graduate.
I build AI systems whose decisions can be checked: every output traced to its source, every result measured, every risky action gated.
Open to consulting and engineering roles in applied AI and data, in France or abroad.

[LinkedIn](https://www.linkedin.com/in/codaccioni-kilian/) · [GitHub](https://github.com/suprkco)

## Featured work

| Project | What I built | Results |
| --- | --- | --- |
| **[Bid/No-Bid défense](https://github.com/suprkco/bid-no-bid)** | A team of agents that decides GO or NO GO on defence tenders for an SME. Every decision is backed by verbatim-checked citations, each subagent runs under a cost cap, and nothing is sent without human approval | **30/30** correct verdicts on a hand-labelled benchmark (11 GO, 19 NO GO), 30/30 for the right reason |
| **[Online Regret Lab](https://github.com/suprkco/Trading-strategies-analysis-regret-minimization)** | A genetic algorithm evolves trading strategies on US indices; the frozen champions are combined online by Hedge and Fixed Share on seven markets they never saw, across five seeds | Hedge reliably beats the average champion on 3 of 7 markets and is never reliably worse. [Live](https://online-regret-lab.onrender.com/), recomputed as new data arrives |
| **[Market Scout Agents](https://github.com/suprkco/market-scout-agents)** | A LangGraph research workflow on a real local model, with exact-quote validation and persistent human review | **9/9** exact quotations; a semantic audit caught 3 contradictory implications that quote checks alone miss. [Case study](https://github.com/suprkco/market-scout-agents/blob/main/docs/case-study.md) · [Terminal replay](https://github.com/suprkco/market-scout-agents/blob/main/docs/demo.gif) |
| **[EU AI Act Evidence Explorer](https://github.com/suprkco/rag-eu-ai-act)** | Retrieval over the AI Act and GDPR with FastAPI, BM25 and optional pgvector; citations come from the sources, never from the model | **20/20** expected articles in the top 5, MRR@5 0.925, 8/8 on a fresh challenge set. [Live](https://rag-eu-ai-act.onrender.com/) |
| **[MCP SQL Analytics](https://github.com/suprkco/mcp-sql-analytics)** | An MCP server that gives an assistant read-only, bounded SQL, with guardrails enforced by the database itself | 24 tests, including protocol integration and denied writes |
| **[Jev SERP Opportunity Lab](https://github.com/suprkco/jev-serp-opportunity-lab)** | Typed search-intent triage that separates the model's judgement from the routing policy | 13 contract and policy tests. [Hosted simulation](https://suprkco.github.io/jev-serp-opportunity-lab/) |
| **[Adaptive Inference Network](https://github.com/suprkco/Blockchain-adaptive-inference-network)** | A trained MiniLM split across CPU workers, benchmarked against local inference and on-chain EVM receipts | 60 latency samples, equivalence checks and injected failures |

## Stack

Python · SQL · FastAPI · Pydantic · Next.js / TypeScript · MCP · LangGraph · Claude Agent SDK · PostgreSQL / pgvector · SQLite · Docker · pytest · Playwright · GitHub Actions

## How I work

- Keep source provenance and make results reproducible.
- Enforce tool permissions in code and the database, not in prompts alone.
- Separate deterministic tests from model-quality evaluations.
- Make review and failure paths visible.

## Earlier work

[Country-data comparison in Python](https://github.com/suprkco/Comparaison-des-indemnit-s-de-VIE-par-pays) · [RentManager in Java / Spring MVC](https://github.com/suprkco/Projet_RentManager) · [Maze solver in C](https://github.com/suprkco/Labyrinthe-backtraking-finder) · [Minimax tic-tac-toe](https://github.com/suprkco/TicTacToes_Minimax) · [Le compte est bon in C++](https://github.com/suprkco/CompteEstBon-R-cursif)
