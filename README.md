# Miloš Javorský

**QA Automation & AI Engineering**

I come from QA automation and now focus on testing and securing LLM/AI systems: evaluation, red-teaming, RAG safety and self-healing E2E tests. I like test suites that run offline, gate merges in CI, and are honest about what they don't cover yet.

## Featured projects

- **[ai-qa-factory](https://github.com/MilJav11/ai-qa-factory)**: local, human-in-the-loop workspace that generates Playwright tests, diagnoses failures and proposes locator repairs, which are applied only after explicit approval. Python, Streamlit, Playwright/TypeScript, OpenRouter; CI on Python 3.10–3.12.
- **[rag-security-sandbox](https://github.com/MilJav11/rag-security-sandbox)**: RAG app and pytest fuzzer for prompt injection, data poisoning and prompt leaking, with regex + LLM-as-a-judge guardrails. FastAPI, ChromaDB, Groq. Offline test suite in CI; known security gaps are documented as `xfail(strict=True)` tests.
- **[llm-api-benchmark](https://github.com/MilJav11/llm-api-benchmark)**: pytest framework benchmarking local LLMs (via Ollama) on latency, instruction following, LLM-as-a-judge, red-team prompts and RAG hallucinations. Test data in JSON, HTML reports, offline suite in CI.
- **[playwright-python-e2e-framework](https://github.com/MilJav11/playwright-python-e2e-framework)**: BDD E2E suite (pytest-bdd, Page Object Model) with a credential-free demo suite gating CI and a manual live-email suite. Python, Playwright, GitHub Actions.
- **[triglav-harness](https://github.com/MilJav11/triglav-harness)**: experimental public preview of a local Python coding controller.
- **[repo-guard](https://github.com/MilJav11/repo-guard)**: fast local git guardrail against accidental secret leaks in AI-generated code. Python.

## How I work

I build with AI coding agents: Claude Code as the lead, Mistral (via Vibe CLI / OpenCode) for smaller tasks. A human stays in the loop:

- agents work on branches, never directly on `main`
- git hooks block pushes and changes to `main`
- every change goes through a reviewed pull request with green CI

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

Also: pytest-bdd, ChromaDB, LLM APIs (OpenRouter, Groq).

## Contact

[LinkedIn](https://www.linkedin.com/in/javorsk%C3%BD/)
