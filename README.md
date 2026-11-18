# Awesome-AI-Agent-Observability-Code-Monitoring

## Top AI Agent Observability & Code Monitoring Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on OpenTelemetry Agent Tracing, Coding Agent Session Monitors, LLM Cost/Token Telemetry, Trajectory Debugging & Evaluation*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Agent Observability & Code Monitoring**. These tools capture span-level traces across multi-step agent runs, monitor autonomous coding agents (`Claude Code`, `Codex`, `Cursor`, `OpenHands`) in real time, track token spend and latency, and evaluate trajectory reliability in production.



**Examples** include LangSmith, Arize Phoenix, Helicone, HoneyHive, Braintrust, Traceloop, OpenLIT, Lunary, Galileo, Weights & Biases Weave, and hoangsonww/Claude-Code-Agent-Monitor (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for local coding-agent dashboards, OpenTelemetry LLM auto-instrumentation, self-hosted trace collectors, prompt/dataset debugging, and CI/CD trajectory evaluations — ideal for AI engineers, DevOps/LLMOps architects, and developers monitoring autonomous coding workflows.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Company Valuation / Revenue | Starting Paid Tier Price | Free Tier Limits / Trial | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[LangSmith (LangChain)](https://langchain.com)** | **$3.0B valuation** (Series C) / ~$16M ARR | **$39 / user / month** (Plus Plan; includes 10,000 traces/mo, additional at $2.50/1k) | **Developer Free Plan**: 5,000 traces/mo, 1 seat, 14-day data retention | All-in-one cloud observability, debugging, testing, and evaluation platform engineered for tracing complex LLM chains and stateful LangGraph agent runs. |
| **[Weights & Biases Weave](https://wandb.ai)** | **$1.4B–$1.7B acquisition** by CoreWeave / ~$50M ARR | **$60 / month** (Pro Plan; up to 10 seats, 100 GB storage) | **Free Plan**: Up to 5 model seats, ~1 GB/mo Weave trace ingestion, 5 GB storage | Cloud developer toolkit from W&B for logging, tracing, visualizing, and evaluating LLM calls, tool executions, and multi-agent workflows. |
| **[Arize AX / Arize Phoenix Cloud](https://arize.com)** | **$915M acquisition** by Dynatrace (raised $131M) | **$50 / month** (AX Pro; 50,000 spans/mo, 10 GB ingestion, 30-day retention) | **Free Plan**: 25,000 spans/mo, 1 GB ingestion, 15-day data retention, 1 space | Enterprise AI observability and LLM evaluation platform delivering deep OpenTelemetry span tracing, drift detection, and root-cause diagnostics for agents. |
| **[Braintrust](https://braintrust.dev)** | **$800M valuation** (Series B) | **$249 / month** (Pro Plan; includes 5 GB processed data, 50k scores/mo, $100 model credits) | **Starter Free Plan**: 1 GB processed data/mo, 10,000 scores/mo, 14-day retention, $10 model credits/mo | Enterprise AI evaluation, prompt playground, and logging platform designed to score multi-step agent trajectories and prevent quality regressions. |
| **[Galileo](https://rungalileo.io)** | **$100M–$250M estimated valuation** ($68M raised) / ~$5M ARR | **$100 / month** (billed annually, or $150/mo billed monthly; Pro Plan includes 50,000 traces/mo) | **Free Plan**: 5,000 traces/mo, single-user access, unlimited custom evaluations | Enterprise AI evaluation and observability platform featuring real-time hallucination guardrails, agentic trajectory metrics, and automated error clustering. |
| **[Traceloop](https://traceloop.com)** | **$70M acquisition** by ServiceNow ($6.6M raised) | **Custom annual enterprise contract** (starts ~$15,000/yr via AWS/cloud marketplace) | **Free Plan**: 50,000 spans/mo, up to 5 seats, 24-hour data retention | Managed OpenTelemetry-native LLM observability and reliability platform built on OpenLLMetry for real-time agent tracing and hallucination detection. |
| **[HoneyHive](https://honeyhive.ai)** | **$7.4M funding raised** (Seed led by Insight Partners) | **Custom enterprise contract** (Sales-led; no intermediate self-serve tier) | **Developer Free Plan**: 10,000 events/mo, up to 5 users, 1 workspace, 30-day data retention | AI observability and evaluation suite built for compounding agent reliability via production trace curation, human feedback loops, and CI/CD regression checks. |
| **[Helicone](https://helicone.ai)** | **~$1M ARR** (YC-backed; acquisition by Mintlify) | **$79 / month** (Pro Plan; 1,000 logs/min, 1 month retention; includes 7-day free trial) | **Hobby Free Plan**: 10,000 requests/mo, 1 GB storage, 1 seat, 7-day data retention, 10 logs/min | Proxy-based LLM observability and AI gateway platform offering real-time request logging, token/cost analytics, caching, and rate-limit monitoring. |
| **[Lunary](https://lunary.ai)** | **Early-stage / Seed** (Xpreneurs backed) | **$20 / user / month** (Team Plan; includes 50,000 events/mo, 300 playground queries/mo) | **No free tier or trial on Cloud** (Requires $20/user/mo upfront; unlimited free usage if self-hosted via OSS) | Production LLM observability, prompt management, and user analytics platform tailored for multi-step AI agent workflows and B2B AI products. |
| **[OpenLIT Cloud](https://openlit.io)** | **Bootstrapped / Community open-source** | **Custom enterprise contract** (Managed cloud platform waitlist / Private beta) | **Waitlist only for Cloud** (Unlimited free usage with no trace caps or seat limits via self-hosted Apache 2.0 OSS) | Hosted OpenTelemetry-native observability and GPU/LLM monitoring platform tracking token consumption, vector database latency, and agent execution spans. |





## Open-Source GitHub Projects



- **[hoangsonww/Claude-Code-Agent-Monitor](https://github.com)**  

  Open-source real-time monitoring dashboard and telemetry tracker built specifically for inspecting Claude Code agent sessions, sub-agent tool calls, file edits, token burn, and execution timelines.



- **[Langfuse](https://github.com)**  

  Leading open-source LLM engineering platform for full-stack agent tracing, nested span visualization, prompt versioning, session replays, and automated evaluations.



- **[Arize Phoenix (`Arize-ai/phoenix`)](https://github.com)**  

  Open-source (`ELv2`) OpenTelemetry-based AI observability and evaluation tool featuring interactive trace waterfall views, RAG/tool-call diagnostics, and notebook integration.



- **[OpenLIT (`openlit/openlit`)](https://github.com)**  

  Open-source (`Apache-2.0`) OpenTelemetry-native AI engineering platform providing zero-code instrumentation for 50+ LLM providers, agent frameworks, vector DBs, and GPU metrics.



- **[OpenLLMetry (`traceloop/openllmetry`)](https://github.com)**  

  Open-source (`Apache-2.0`) set of extensions built on standard OpenTelemetry to capture and export non-intrusive traces and metrics from any LLM or agent runtime.



- **[OpenInference (`Arize-ai/openinference`)](https://github.com)**  

  Open-source (`Apache-2.0`) set of OpenTelemetry instrumentation libraries and semantic conventions for tracing AI agents across Python, TypeScript, and Java.



- **[Helicone (`Helicone/helicone`)](https://github.com)**  

  Open-source (`Apache-2.0`) AI gateway and observability proxy enabling self-hosted request logging, cost tracking, latency monitoring, and semantic caching.



- **[Lunary (`lunary-ai/lunary`)](https://github.com)**  

  Self-hostable open-source (`Apache-2.0`) toolkit for LLM observability, agent run visualization, prompt templates, cost dashboards, and PII masking.



- **[Opik (`comet-ml/opik`)](https://github.com)**  

  Open-source (`Apache-2.0`) end-to-end LLM evaluation and tracing platform from Comet built for logging high-volume agent traces and running LLM-as-a-judge checks.



- **[Weights & Biases Weave (`wandb/weave`)](https://github.com)**  

  Open-source (`Apache-2.0`) lightweight Python/TypeScript toolkit for tracking inputs, outputs, nested tool calls, and evaluation scores across agent applications.



- **[Agenta (`Agenta-AI/agenta`)](https://github.com)**  

  Open-source (`MIT`) LLMOps platform focused on collaborative prompt engineering, custom agent workflow playgrounds, and human/automated trajectory evaluation.



- **[AgentOps SDK (`AgentOps-AI/agentops`)](https://github.com)**  

  Open-source (`MIT`) Python SDK for instrumenting AI agents with session replays, tool-usage metrics, token cost accounting, and framework integrations.



- **[Logfire (`pydantic/logfire`)](https://github.com)**  

  OpenTelemetry-native observability platform and open-source SDKs from the Pydantic team offering first-class instrumentation for Pydantic AI, OpenAI, and Python agents.



- **[LangWatch (`langwatch/langwatch`)](https://github.com)**  

  Open-source (`Fair-code` / self-hostable) LLM Ops and agent monitoring platform featuring real-time evaluation guardrails, OpenTelemetry support, and visual trace debugging.



- **[TensorZero (`tensorzero/tensorzero`)](https://github.com)**  

  Open-source (`Apache-2.0`) industrial-grade LLM gateway, observability, and experimentation engine written in Rust for high-throughput agent telemetry.



- **[ccusage (`ryoppippi/ccusage`)](https://github.com)**  

  Fast open-source (`MIT`) CLI analyzer for tracking local Claude Code JSONL session logs, daily token consumption, cache hit rates, and model spend.



- **[Claude Code Hooks Observability (`disler/claude-code-hooks-multi-agent-observability`)](https://github.com)**  

  Open-source real-time monitoring system using Claude Code lifecycle hooks (`PreToolUse`, `PostToolUse`, `SubagentStop`) to stream multi-agent coding activity to a live web dashboard.



- **[Inspect AI (`UKGovernmentBEIS/inspect_ai`)](https://github.com)**  

  Open-source (`MIT`) framework from UK AISI for evaluating and inspecting complex coding and tool-use agent trajectories with full transcript viewers.



### Additional Strong Open-Source Options



- **[SigNoz](https://github.com)** and **[Grafana Tempo + Prometheus](https://github.com)** for open-source OpenTelemetry backends storing and querying high-cardinality agent traces alongside infrastructure metrics.

- **[Jaeger](https://github.com)** and **[Zipkin](https://github.com)** for lightweight, battle-tested distributed tracing UIs compatible with OpenLLMetry and OpenInference spans.

- **[Promptfoo](https://github.com)** and **[DeepEval](https://github.com)** for CI/CD agent regression testing, red-teaming, and automated tool-correctness scoring.

- **[MLflow Tracing (`mlflow/mlflow`)](https://github.com)** for open-source end-to-end experiment tracking and OpenTelemetry-compatible GenAI/agent span visualization.

- **[claude-code-otel / OpenTelemetry Collector](https://github.com)** for exporting native `CLAUDE_CODE_ENABLE_TELEMETRY=1` metrics and logs directly into self-hosted observability stacks.



**Frameworks for building custom systems**: Combine **hoangsonww/Claude-Code-Agent-Monitor** (coding agent telemetry) with **OpenLLMetry / OpenInference** (OpenTelemetry instrumentation), **Langfuse** or **Arize Phoenix** (trace & session UI), and **Grafana / SigNoz** for end-to-end open-source AI agent observability and code monitoring.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer
