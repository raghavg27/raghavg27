<h1 align="center">Raghav Gupta</h1>

<p align="center">
  <b>Quality engineering for AI systems.</b><br>
  Five years building test infrastructure for production software.<br>
  Now doing it for AI agents, where correctness is probabilistic and the old assertions don't hold.
</p>

<p align="center">
  <a href="mailto:raghavg2705@gmail.com"><img src="https://img.shields.io/badge/Email-raghavg2705%40gmail.com-000000?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://linkedin.com/in/raghavg27/"><img src="https://img.shields.io/badge/LinkedIn-raghavg27-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://build-with-raghav.vercel.app"><img src="https://img.shields.io/badge/Portfolio-build--with--raghav-7C3AED?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
</p>

> **Currently:** QA Engineer, AI Agent Evaluation at **Handshake AI** (contract) · Delhi, India · Remote
>
> **Open to:** full-time SWE / SDET / AI-evaluation roles — and freelance work on agent evals, test automation, and LLM CI. Reply time under 24h.

---

## What I do

**Evaluate AI agents.** I design end-to-end test scenarios for AI coding agents, each shipped as a reproducible Dockerised environment with a written spec, a reference implementation, and an automated verifier that defines objective pass/fail. Boundary, negative and exploratory techniques applied to agent failure modes — long-horizon planning, environment state handling, recovery from failed tool calls. Determinism enforced so a result measures the agent, not a defect in the harness.

**Build test infrastructure.** Regression suites on PyTest, Selenium, Playwright and Appium with the Page Object Model, wired into Jenkins and GitHub Actions over Docker and Kubernetes. Load and performance work in JMeter against high-throughput flows. Pipeline health surfaced to Grafana so failure trends and release readiness are visible without asking anyone.

**Ship the systems too.** Multi-agent RAG, LLM cost-regression tooling on PyPI, and a full-stack PWA whose money core is verified with property-based tests. The repos below are the evidence — all runnable, most with CI.

---

## Selected work

| Project | What it is | Why it's worth your click |
|---|---|---|
| **[squared-up](https://github.com/raghavg27/squared-up)** | Split expenses with friends, settle in one UPI tap. India-first Splitwise alternative. | 13.9k LOC. Django + DRF + Postgres behind a framework-free money core in integer paise — largest-remainder allocation, debt simplification, UPI intent — verified against spec vectors *and* Hypothesis property tests. Installable React/Vite PWA. `docker compose up` and it runs. |
| **[InferenceCI](https://github.com/raghavg27/InferenceCI)** — `costdiff` | Catches LLM cost regressions before they ship. Replays your scenarios on every PR, diffs token spend against `main`, fails the check when cost jumps. | **Live on PyPI** (`pip install inferenceci`). Token usage read natively from OpenAI and Anthropic SDKs via OpenTelemetry — no scraping, no estimation. IQR noise floor so real deltas aren't drowned in variance. Ships as a GitHub Action. |
| **[equity-crew](https://github.com/raghavg27/equity-crew)** | Five CrewAI agents producing an institutional-style equity research report for any listed ticker. | Fundamentals, neural news search, sector peer benchmarking, and technical indicators (RSI, MACD, Bollinger, SMA) written from scratch in pandas — no TA library. Output is a schema-validated BUY/HOLD/SELL with confidence, target price, reasons and risks, rendered to PDF. CI + Docker. |
| **[git-guide](https://github.com/raghavg27/git-guide)** | Multi-agent RAG over GitLab documentation. CrewAI + ChromaDB + Streamlit. | Async parallel retrieval, smart query routing, grounded and cited answers. Built to run at zero inference cost. |
| **[skill-doctor-pro](https://github.com/raghavg27/skill-doctor-pro)** | Auto-fixing linter, activation tester and CI gatekeeper for Claude Code and Codex skills. | Tiered `checks/` + `fixers/` architecture. Ships as a Dockerised GitHub Action — drop it in a workflow and bad skills stop merging. |
| **[steno](https://steno-ai.vercel.app)** | A writing standard that stops AI output reading like a language model. | Shipped and sold, not a demo. An instruction layer plus a Claude Skills file targeting the specific tells — inflated significance, participial padding, promotional tone, rule of three, uniform rhythm. |

---

## Experience

| | Role | When |
|---|---|---|
| **Handshake AI** | QA Engineer, AI Agent Evaluation *(contract)* | Mar 2026 – present |
| **Grey Orange** | Software Engineer – QA (SDET) | Sep 2025 – Dec 2025 |
| **Shway** | Software Engineer – QA | Jun 2023 – Sep 2025 |
| **Yellow.ai** | Customer Success Engineer | Jul 2021 – Jun 2023 |

Selected outcomes: cut manual test effort **60–70%** with automated regression suites for warehouse and robot workflows · reduced pipeline false positives **25%** through daily triage of nightly runs · cut backend defect leakage **40%** with end-to-end API contract testing · improved peak-load response times **30%** via JMeter load testing · reduced test maintenance **35%** with an in-house data-driven PyTest framework · **zero** critical production defects across multiple iOS/Android feature releases.

B.E. Computer Engineering, SRM Institute of Science and Technology, 2017–2021.

---

## Stack

**Languages & data** — Python · JavaScript · SQL · PostgreSQL · MongoDB · Bash

**Testing & evaluation** — PyTest · Playwright · Selenium · Appium · JUnit · JMeter · Postman · RestAssured · TestRail · Hypothesis (property-based) · agent evals

**AI** — CrewAI · multi-agent orchestration · RAG · ChromaDB · OpenAI & Anthropic SDKs · OpenTelemetry · OpenRouter

**Platform** — Docker · Kubernetes · Jenkins · GitHub Actions · Grafana · Linux · Django · DRF · React · Node.js

---

<p align="center">
  <b>Hiring, or need something tested?</b><br>
  <a href="mailto:raghavg2705@gmail.com">raghavg2705@gmail.com</a>
</p>
