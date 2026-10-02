# Hi, I'm Manav Garg

B.Tech Computer Science (AI) student in Sonipat, India. I build backend-heavy systems — a
workflow engine that survives `kill -9`, ML systems that report how often they are wrong, API
tooling — and I write down what each project does and does not prove.

**How I work:** I build with AI coding assistants (Claude Code) and say so in every
repository's README. What I hold the projects to is evidence: tests that run in CI, committed
results, and a "known limitations" section instead of adjectives. I'm learning the internals
underneath as I go.

## Selected projects

| Project | What it is |
|---|---|
| [**Indicant**](https://github.com/manav363/indicant) | A prediction system for NSE equities that reports how often it is wrong: calibrated probabilities, purged and embargoed cross-validation, and a permutation test on every screen. Its current edge is not statistically distinguishable from chance, and it says so. |
| [**Ledger**](https://github.com/manav363/Ledger) | A visual workflow engine whose entire execution layer is PostgreSQL: an append-only event log, `FOR UPDATE SKIP LOCKED` job claiming, crash recovery. A demo `kill -9`s a worker mid-run and the workflow resumes. TypeScript, React. |
| [**APIBlueprint**](https://github.com/manav363/apiblueprint) | A contract-first API design studio: model endpoints in a web UI, store them in PostgreSQL, generate OpenAPI 3.0.3, serve mock endpoints. FastAPI, React, CI with dependency audits. |
| [**SentiScope**](https://github.com/manav363/sentiment-dashboard) | Sentiment analysis for text or an article URL: FastAPI, a pretrained RoBERTa model, React. The URL scraper is SSRF-hardened, including redirect hops, and covered by tests. |
| [**LLM Fine-Tune**](https://github.com/manav363/llm-finetune) | A LoRA / QLoRA fine-tuning pipeline with swappable MLX and CUDA backends, GGUF export, serving, and a statistical base-vs-tuned evaluation. The committed result is "no measurable difference", reported as such. |
| [**Agent Orchestra**](https://github.com/manav363/multi-agent-system) | A multi-agent orchestration engine for local LLMs, written in Rust, with a live terminal UI. |

More: [Intraday Trading AI (NSE)](https://github.com/manav363/intraday-trading-ai-india), a
four-service research platform that publishes the statistical evidence alongside each signal;
[SyncPulse](https://github.com/manav363/inventory-system), a browser-only dashboard that flags products oversold across sales channels; and
[Warden](https://github.com/manav363/warden), an agentless vulnerability scanner that is in
progress (a Rust discovery sensor with a fail-closed scope guard so far).

## Technologies in these projects

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-DEA584?style=flat-square&logo=rust&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

## Contact

[LinkedIn](https://www.linkedin.com/in/manav-garg-ai)
