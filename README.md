## Ulises González

**Co-founder @ [Rizoma](https://rizo.ma)** | Executive-education faculty | AI Product Builder | Data & Organizational Systems Consultant

I build AI-enabled products, learning platforms, analytics systems, and organizational tools that turn complexity into usable capabilities. My work sits at the intersection of data, product delivery, executive education, and organizational change.

- `20+ years` across analytics, consulting, product delivery, and executive education
- Advanced practitioner in `Claude Code`, `Codex`, `MCP servers`, structured outputs, and agentic workflows
- Focused on results: diagnostics platforms, AI-assisted SaaS, learning products, dashboards, and internal tooling
- Self-hosted AI infrastructure on `NVIDIA DGX Spark` (Blackwell GB10) — local LLMs, RAG, and image/video generation

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![NVIDIA](https://img.shields.io/badge/DGX_Spark-76B900?style=flat&logo=nvidia&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat&logo=next.js&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-412991?style=flat&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-D97757?style=flat)

---

### Current Work

| Project | What it does | Stack |
|---------|--------------|-------|
| [**cs-agents-istmenas**](https://github.com/gonzalezulises/cs-agents-istmenas) | Multi-agent customer-service orchestration demo: specialized agents with guardrails and handoffs over the OpenAI Agents SDK + ChatKit, with a localized customer view and an English agent view. | `Python` `OpenAI Agents SDK` `ChatKit` `Next.js` |
| [**opsflow**](https://github.com/gonzalezulises/opsflow) | AI-assisted operations-improvement platform: diagnostics, value-stream mapping, risk & prioritization with auditable follow-through. [Live](https://opsflow-gold.vercel.app) | `Next.js` `TypeScript` `Supabase` `Drizzle` `OpenAI` |
| [**climalab**](https://github.com/gonzalezulises/climalab) | Multi-tenant SaaS for organizational-climate measurement: survey ops, branded reporting, ONA, and AI-backed insights. [Live](https://climalab.vercel.app) | `Next.js 16` `TypeScript` `Supabase` `pg_net` `OpenAI` |
| **planwise-ai** `private` | SaaS for automatic architectural-plan review: multi-model consensus (GPT-5 + Gemini 2.5), traceable arbitration, and a parametric normative catalog. | `React` `Supabase` `Edge Functions` `Deno` `OpenAI` `Gemini` |
| **entrevistas-360** `private` | B2B 360-feedback platform: anonymized aggregation with k-anonymity, AI synthesis, and an end-to-end tested vertical slice. | `Next.js 16` `Prisma` `Zod` `Vitest` |
| **web-intelligence-agent** `private` | Internal web-intelligence platform: monitors URLs, classifies changes, and alerts through an agentic layer over an opaque sensor. | `Python` `FastAPI` `SQLAlchemy` `Pydantic` `Claude` |
| **sim-decisiones** `private` | Corporate war-game engine: pure-TS multinomial-logit simulator for organizational decisions with competition and learning effects. | `Next.js` `TypeScript` `Vitest` `Playwright` |
| **dgx-spark-cerebro** `private` | Self-hosted AI node (Blackwell GB10, 128 GB): Gemma 4 MoE on vLLM (~49 tok/s) + FLUX + Qwen NIM, served through Open WebUI over Tailscale. | `Shell` `vLLM` `NVIDIA NIM` `CUDA 13` |

### AI Engineering

I use `Claude Code`, `Codex`, and custom `MCP` tooling as leverage for shipping end-to-end systems rather than demos. The emphasis is on outcomes: faster iteration, better architecture, stronger automation, and more useful products — increasingly backed by **self-hosted models** on local DGX infrastructure for privacy and cost control.

### AI, Agents & RAG Systems

| Project | Description | Stack |
|---------|-------------|-------|
| [**cs-agents-istmenas**](https://github.com/gonzalezulises/cs-agents-istmenas) | Multi-agent orchestration demo over the OpenAI Agents SDK + ChatKit: triage, specialized agents, guardrails, and handoffs, with a localized customer view. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![OpenAI](https://img.shields.io/badge/-OpenAI_Agents_SDK-412991?style=flat&logo=openai&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) |
| **web-intelligence-agent** `private` | Internal web-intelligence platform with an agentic layer over an opaque `changedetection.io` sensor; Pydantic Protocols, Alembic, hybrid path documented in ADR-0001. | ![Python](https://img.shields.io/badge/-Python_3.13-3776AB?style=flat&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/-SQLAlchemy-D71F00?style=flat) ![Claude](https://img.shields.io/badge/-Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white) |
| **cerebro-ds** `private` | Data-Science-focused RAG system: 100+ books, knowledge graph, multi-agent workflows, and DGX Spark deployment with Milvus + vLLM. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![NVIDIA](https://img.shields.io/badge/-DGX_Spark-76B900?style=flat&logo=nvidia&logoColor=white) |
| [**semantic-scholar-mcp**](https://github.com/gonzalezulises/semantic-scholar-mcp) | MCP server for the Semantic Scholar API: academic search, citations, and recommendations for Claude Code / Chat. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![MCP](https://img.shields.io/badge/-MCP-D97757?style=flat) ![Claude](https://img.shields.io/badge/-Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white) |
| **vision-mcp-server** `private` | MCP server for image analysis with multimodal models, running locally or on DGX infrastructure. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![Hugging Face](https://img.shields.io/badge/-Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black) |
| **bamboohr-claude-mcp** `private` | HR-ops integration via MCP (reuses `evrimalacan/mcp-bamboohr`); setup, troubleshooting, and people-analytics use cases. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![MCP](https://img.shields.io/badge/-MCP-D97757?style=flat) |
| **revit-mcp-skill** `private` | Claude Code skill for Revit MCP integration: installs, configures, and manages the Autodesk Revit connection via MCP. | ![PowerShell](https://img.shields.io/badge/-PowerShell-5391FE?style=flat&logo=powershell&logoColor=white) ![MCP](https://img.shields.io/badge/-MCP-D97757?style=flat) |
| **whatsapp-bot-rag** `private` | WhatsApp Business bot with a RAG pipeline for Q&A over a corporate knowledge base. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat&logo=openai&logoColor=white) |
| **claude-code-setup** `private` | Production-grade Claude Code configuration: MCP servers, curated skills, and security/architecture/quality rules. | ![Claude](https://img.shields.io/badge/-Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white) ![MCP](https://img.shields.io/badge/-MCP-D97757?style=flat) ![Shell](https://img.shields.io/badge/-Shell-121011?style=flat&logo=gnu-bash&logoColor=white) |
| **dotfiles** `private` | Advanced Claude Code setup with hooks, headless audits, custom commands, and context for agentic workflows. | ![Shell](https://img.shields.io/badge/-Shell-121011?style=flat&logo=gnu-bash&logoColor=white) ![Claude](https://img.shields.io/badge/-Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white) |
| **local-ai-enterprise** `private` | Plug-and-play local AI solution for enterprises — LM Studio + RAG + Apple Silicon, with privacy and cost focus. | ![Apple](https://img.shields.io/badge/-Apple_Silicon-000?style=flat&logo=apple&logoColor=white) ![LM_Studio](https://img.shields.io/badge/-LM_Studio-000?style=flat) ![RAG](https://img.shields.io/badge/-RAG-412991?style=flat) |

### Self-hosted AI Infrastructure (DGX Spark)

| Project | Description | Stack |
|---------|-------------|-------|
| **dgx-spark-cerebro** `private` | DGX Spark (GB10, 128 GB) node "Cerebro" — state, contracts, and runbooks. Serves Gemma 4 MoE on vLLM (~49 tok/s) via Open WebUI, plus on-demand FLUX, over Tailscale. | ![Shell](https://img.shields.io/badge/-Shell-121011?style=flat&logo=gnu-bash&logoColor=white) ![vLLM](https://img.shields.io/badge/-vLLM-FF6B6B?style=flat) ![NVIDIA](https://img.shields.io/badge/-DGX_Spark-76B900?style=flat&logo=nvidia&logoColor=white) |
| **dgx-spark-ai-stack** `private` | Full self-hosted AI stack on DGX Spark: Gemma 4 31B (vLLM) + FLUX Schnell image generation, served behind auth. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![vLLM](https://img.shields.io/badge/-vLLM-FF6B6B?style=flat) ![CUDA](https://img.shields.io/badge/-CUDA_13-76B900?style=flat&logo=nvidia&logoColor=white) |
| **dgx-spark-qwen-nim** `private` | Self-hosted Qwen3-32B (NVFP4) on DGX Spark via NVIDIA NIM, bearer-auth + Cloudflare tunnel. | ![NVIDIA](https://img.shields.io/badge/-NIM-76B900?style=flat&logo=nvidia&logoColor=white) ![Shell](https://img.shields.io/badge/-Shell-121011?style=flat&logo=gnu-bash&logoColor=white) |
| [**dgx-spark-playbooks**](https://github.com/gonzalezulises/dgx-spark-playbooks) | Playbooks for configuring AI/ML workloads on NVIDIA DGX Spark with Blackwell architecture. | ![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) ![NVIDIA](https://img.shields.io/badge/-DGX_Spark-76B900?style=flat&logo=nvidia&logoColor=white) |
| **n8n-configuraciones** `private` | n8n configurations, deployment plan, and ops notes (DGX Spark + MCP in Claude Code). | ![n8n](https://img.shields.io/badge/-n8n-EA4B71?style=flat&logo=n8n&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |

### People & Organizational Analytics

| Project | Description | Stack |
|---------|-------------|-------|
| [**climalab**](https://github.com/gonzalezulises/climalab) | Multi-tenant SaaS for organizational climate in SMBs: instrumentation, branded reporting, ONA, and AI support. [Live](https://climalab.vercel.app) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) |
| **clima-api** `private` | REST API for organizational-climate analysis with clustering and predictive models. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) |
| [**pulseorg**](https://github.com/gonzalezulises/pulseorg) | Organizational visualization platform with force-directed graphs, word clouds, and team-dynamics analysis. [Live](https://pulseorg.vercel.app) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![D3](https://img.shields.io/badge/-D3.js-F9A03C?style=flat&logo=d3.js&logoColor=white) |
| **VoC** `private` | Voice-of-Customer analysis with NLP and clustering. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) ![NLTK](https://img.shields.io/badge/-NLTK-154F5B?style=flat) |
| **entrevistas-360** `private` | B2B 360-feedback platform: anonymized aggregation with k-anonymity, AI synthesis, and an end-to-end tested vertical slice. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Prisma](https://img.shields.io/badge/-Prisma-2D3748?style=flat&logo=prisma&logoColor=white) ![Zod](https://img.shields.io/badge/-Zod-3068B7?style=flat&logo=zod&logoColor=white) |
| **organizational-climate-study** `private` | End-to-end organizational-climate study (banking): longitudinal cuts and an executive report. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Recharts](https://img.shields.io/badge/-Recharts-22B5BF?style=flat) |
| [**panama-puente**](https://github.com/gonzalezulises/panama-puente) | Graph ML applied to organizational climate (banking) — paper-style writeup for Panamá Puente Digital 2026. [Live](https://panama-puente.vercel.app) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![NetworkX](https://img.shields.io/badge/-NetworkX-4C8CBF?style=flat) ![PyTorch](https://img.shields.io/badge/-PyTorch_Geometric-EE4C2C?style=flat&logo=pytorch&logoColor=white) |
| **hr-analytics** `private` | People-analytics dashboard wired to a live HRIS + spreadsheets, deployed on Cloud Run behind IAP with a cron-driven data refresh. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Google Cloud](https://img.shields.io/badge/-Cloud_Run-4285F4?style=flat&logo=google-cloud&logoColor=white) |
| **plan-estrategico** `private` | Strategic-initiatives dashboard (industrial group): intake, AI-assisted scoring, and executive prioritization. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat&logo=openai&logoColor=white) |

### Consulting, PMO & Process Management

| Project | Description | Stack |
|---------|-------------|-------|
| [**opsflow**](https://github.com/gonzalezulises/opsflow) | Intelligent operations-optimization platform: diagnostics, VSM, risks, prioritization, and AI-assisted follow-through. [Live](https://opsflow-gold.vercel.app) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) ![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat&logo=openai&logoColor=white) |
| **pcf-evaluator** `private` | Web system for evaluating organizational processes against the APQC PCF framework: maturity scoring (0–5), PDF reports, and process maps. 1,921 elements + 3,910 metrics. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![Auth.js](https://img.shields.io/badge/-Auth.js-000?style=flat) |
| **pmo-scorecard** `private` | PMO scorecard: dynamic studio-level health from a live PSA, with a weighted index (timeline, profitability, activity, satisfaction) and configurable thresholds. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) |
| **pm-dashboard** `private` | Project-management dashboard with EVM (S-curve, SPI/CPI), BIM clashes, and QA/QC — spreadsheet → snapshot pipeline. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Recharts](https://img.shields.io/badge/-Recharts-22B5BF?style=flat) |
| **ar-collections-ml** `private` | Accounts-receivable collections dashboard with ML: clustering, Monte Carlo, and default-risk scoring over a PSA API → Supabase pipeline. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) |
| **newbiz-pricing** `private` | New-business pricing tool: 3,000+ quotes analyzed, fee-per-m² estimation and clustering over a PSA → Supabase → Next.js pipeline. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) |
| **it-budget-dashboard** `private` | IT budget vs. spend dashboard with overrun tracking, charts, and Excel ingestion. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Recharts](https://img.shields.io/badge/-Recharts-22B5BF?style=flat) |
| **mentorhub** `private` | Mentoring-operations platform with sessions, objectives, AI-assisted debriefs, and PDF report generation. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Prisma](https://img.shields.io/badge/-Prisma-2D3748?style=flat&logo=prisma&logoColor=white) ![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat&logo=openai&logoColor=white) |
| **planwise-ai** `private` | SaaS for automatic architectural-plan review: multi-model consensus (GPT-5 + Gemini 2.5), traceable arbitration, and a parametric normative catalog. | ![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) ![Deno](https://img.shields.io/badge/-Deno-000?style=flat&logo=deno&logoColor=white) ![Gemini](https://img.shields.io/badge/-Gemini_2.5-4285F4?style=flat&logo=googlegemini&logoColor=white) |
| **wellness-assessment** `private` | Health-assessment SaaS that parses CSV, Excel, and body-composition files, computes 14 sub-scores across 5 dimensions, and cuts evaluation time from 45 minutes to under 10. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) |
| **it-demand-flow** `private` | Interactive IT demand-flow visualization with four coordinated dashboards and sequential/parallel animations. | ![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black) ![React Flow](https://img.shields.io/badge/-React_Flow-FF0072?style=flat) ![Tailwind](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat&logo=tailwind-css&logoColor=white) |
| **process-diagnostics** `private` | Process diagnostics for an architecture firm — instrumentation, maps, and improvement plan. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) |
| **ops-diagnostics** `private` | Operational diagnostics and improvement proposal (real estate), with quantitative analysis and an executive report. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white) |

### Surveys & Assessments (schema-as-code)

Anonymous surveys and assessments built from JSON specs against the Tally API — conditional logic, multi-section flows, and reproducible deployment.

| Project | Description | Stack |
|---------|-------------|-------|
| [**encuesta-sap**](https://github.com/gonzalezulises/encuesta-sap) | Enterprise-IT management survey integrated with the Tally API. | ![Tally](https://img.shields.io/badge/-Tally-000?style=flat) |
| **po-assessment** `private` | Product Owner assessment (banking) — anonymous pre-workshop Tally form (v3, 18 questions). | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Tally](https://img.shields.io/badge/-Tally-000?style=flat) |
| **strategic-conversations-survey** `private` | Two-part Tally survey kit for an executive strategic-conversations program. Schema-as-code via JSON spec. | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Tally](https://img.shields.io/badge/-Tally-000?style=flat) |
| **marketing-ai-diagnostic** `private` | Tally diagnostic to surface AI needs in marketing teams (8 questions), tied to a training program. | ![Tally](https://img.shields.io/badge/-Tally-000?style=flat) |
| **vsm-survey** `private` | Pre-workshop profiling survey for an operating-model / value-stream update (6 sections, 27 questions, conditional logic via API). | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Tally](https://img.shields.io/badge/-Tally-000?style=flat) |
| **survey-governance** `private` | Governance repo for reusable Tally surveys (diagnostic / post-workshop / impact) — definitions, deployment, and response analysis. | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Tally](https://img.shields.io/badge/-Tally-000?style=flat) |

### Educational Platforms & Simulators

| Project | Description | Stack |
|---------|-------------|-------|
| [**curso-claude-console**](https://github.com/gonzalezulises/curso-claude-console) | Technical megacourse — zero to Claude Code architect. Covers Messages API, Workbench, MCP, Skills, Managed Agents, Claude Code CLI/SDK, and Admin API. | ![Vue](https://img.shields.io/badge/-Vue-4FC08D?style=flat&logo=vue.js&logoColor=white) ![Claude](https://img.shields.io/badge/-Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white) ![MCP](https://img.shields.io/badge/-MCP-D97757?style=flat) |
| [**claude-cert-simulator**](https://github.com/gonzalezulises/claude-cert-simulator) | Certification simulator for Claude Certified Architect – Foundations, with questions, timer, and scoring. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) |
| [**ml-simulator**](https://github.com/gonzalezulises/ml-simulator) | Interactive Machine Learning simulator with 15 simulations, theory, and quizzes. [Live](https://gonzalezulises.github.io/ml-simulator/) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) |
| [**ml-exam**](https://github.com/gonzalezulises/ml-exam) | Machine Learning exam simulator. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) |
| [**ruta-ai-engineer**](https://github.com/gonzalezulises/ruta-ai-engineer) | Professional path for AI Software Engineer — high-quality alternative training, zero cost, 12–18 months. [Live](https://stitch-mcp-guide.vercel.app) | ![Astro](https://img.shields.io/badge/-Astro-BC52EE?style=flat&logo=astro&logoColor=white) ![Tailwind](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat&logo=tailwind-css&logoColor=white) |
| [**academia-rizoma**](https://github.com/gonzalezulises/academia-rizoma) | Rizoma Academy — educational platform for Data Analytics, Python, and SQL courses. [Live](https://academia-rizoma.vercel.app) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) ![Vercel](https://img.shields.io/badge/-Vercel-000?style=flat&logo=vercel&logoColor=white) |
| [**plataforma-aprendizaje**](https://github.com/gonzalezulises/plataforma-aprendizaje) | Active-learning platform with live code execution, assessment, and pedagogical AI assistance powered by RAG. [Demo](https://frontend-one-sigma-58.vercel.app) | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat&logo=openai&logoColor=white) |
| [**edu-platform**](https://github.com/gonzalezulises/edu-platform) | Educational platform with authentication, course management, and progress tracking. [Live](https://edu-platform-gray.vercel.app) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) |
| [**certigen**](https://github.com/gonzalezulises/certigen) | Certificate generation and validation system with QR codes. [Live](https://certigen-sandy.vercel.app) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Vercel](https://img.shields.io/badge/-Vercel-000?style=flat&logo=vercel&logoColor=white) |
| [**kst-course-engine**](https://github.com/gonzalezulises/kst-course-engine) | Course engine based on Knowledge Space Theory, with formal structures for adaptive learning. CLI + REST API. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![NetworkX](https://img.shields.io/badge/-NetworkX-4C8CBF?style=flat) |
| **iag-101** `private` | Generative-AI fundamentals course (8h, 4C × Bloom): Next.js platform with simulators, quizzes, and generated `.pptx` slides. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![shadcn/ui](https://img.shields.io/badge/-shadcn/ui-000?style=flat&logo=shadcnui&logoColor=white) |
| **sim-decisiones** `private` | Corporate war-game — pure-TS multinomial-logit engine for organizational-decision simulation with competition and learning effects. Vitest + Playwright. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat&logo=playwright&logoColor=white) |
| **live-quiz-realtime** `private` | Live Kahoot-style quiz for a data-storytelling course: 15 questions, projector + mobile flow via QR. Built on Supabase Realtime (Broadcast + Presence), zero tables. | ![HTML](https://img.shields.io/badge/-HTML-E34F26?style=flat&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Supabase](https://img.shields.io/badge/-Supabase_Realtime-3FCF8E?style=flat&logo=supabase&logoColor=white) |
| **vsm-classroom** `private` | Virtual classroom for an operating-model + value-stream-mapping program: staged content, markdown lessons, optional diagnostic. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Tailwind](https://img.shields.io/badge/-Tailwind_v4-06B6D4?style=flat&logo=tailwind-css&logoColor=white) |
| **guia-cowork** `private` | Interactive workshop guide for Claude Cowork · Rizo.ma — mind map, plugin anatomy, patterns, setup, compare, exercises, maturity. [Live](https://guia-cowork.vercel.app) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Tailwind](https://img.shields.io/badge/-Tailwind_v4-06B6D4?style=flat&logo=tailwind-css&logoColor=white) |

### Enterprise Enablement Programs & Decks

Multi-session AI-enablement programs for banking, fintech, and industrial clients — built on a shared `deck-stage.js` web-component runtime for visual continuity across hubs, decks, and hands-on exercises.

| Program | Description | Stack |
|---------|-------------|-------|
| **vibe-coding program** `private` | Multi-track AI vibe-coding & Claude Code enablement for a regional banking group: hub + 3 workshop decks + pre-work (200+ slides, 30+ hands-on exercises). | ![HTML](https://img.shields.io/badge/-HTML-E34F26?style=flat&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| **ia-workshop (3 sessions)** `private` | AI-for-banking workshop, 3 full live sessions: productivity & workspace, data science, and multimodality — hub + per-session sites. | ![HTML](https://img.shields.io/badge/-HTML-E34F26?style=flat&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| **business-agility** `private` | Business Agility learning platform (banking): 3 modules × 24h — dashboard, diagnostics, knowledge map, slides, consultant bot. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![Tailwind](https://img.shields.io/badge/-Tailwind_v4-06B6D4?style=flat&logo=tailwind-css&logoColor=white) |
| **gemini-enterprise-deck** `private` | "Remote Lab" training deck for Gemini in the enterprise (fintech), 27 slides. | ![HTML](https://img.shields.io/badge/-HTML-E34F26?style=flat&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| **claude-cowork-0-a-100** `private` | "Claude Cowork, 0 to 100" — 37-slide workshop deck on `deck-stage.js`. | ![HTML](https://img.shields.io/badge/-HTML-E34F26?style=flat&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| **suelta-el-control** `private` | "Let go of control, not alignment" — interactive leadership deck with a 2×2 zones map, a 1–7 dial, and a decision card. | ![HTML](https://img.shields.io/badge/-HTML-E34F26?style=flat&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |

### Talks & Presentations

| Project | Description | Stack |
|---------|-------------|-------|
| **webinar-ia-agentes** `private` | Corporate-university webinar — "Specializing in AI agents": agent types, evaluation, 2026 providers, and a live RAG demo, with an embedded multi-agent demo. | ![HTML](https://img.shields.io/badge/-HTML-E34F26?style=flat&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| [**keynote-ia-expotech2026**](https://github.com/gonzalezulises/keynote-ia-expotech2026) | Keynote on AI in logistics for EXPO TECH 2026, Panama. 30 dark-mode slides. [Live](https://keynote-ia-expotech2026.vercel.app) | ![HTML](https://img.shields.io/badge/-HTML-E34F26?style=flat&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| [**gestion-agil-2026-ia-agentica**](https://github.com/gonzalezulises/gestion-agil-2026-ia-agentica) | Talk on agile project management in 2026 with agentic AI. [Live](https://gestion-agil-2026-ia-agentica.vercel.app) | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| [**webinar-ia-nicaragua**](https://github.com/gonzalezulises/webinar-ia-nicaragua) | Webinar on AI for banking, finance, and insurance. [Live](https://webinar-ia-nicaragua.vercel.app) | ![HTML](https://img.shields.io/badge/-HTML-E34F26?style=flat&logo=html5&logoColor=white) |
| [**bni-roi-presentacion**](https://github.com/gonzalezulises/bni-roi-presentacion) | Compound relational ROI simulator for business networking. | ![HTML](https://img.shields.io/badge/-HTML-E34F26?style=flat&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| **capsula-bni-mundial-2026** `private` | "World Cup 2026" educational capsule — 7-slide static deck on `deck-stage.js`. | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| **webinar-ia-prompting** `private` | Corporate-university webinar: AI · Prompt Engineering — single-page site. | ![HTML](https://img.shields.io/badge/-HTML-E34F26?style=flat&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |

### Data Science & Machine Learning

| Project | Description | Stack |
|---------|-------------|-------|
| [**HIM**](https://github.com/gonzalezulises/HIM) | Environmental data management and analysis, with predictive models for hydrology and energy. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) |
| [**airbnb-pricing-ml**](https://github.com/gonzalezulises/airbnb-pricing-ml) | ML model for Airbnb price prediction. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) |
| [**CreditCardFraudPrediction**](https://github.com/gonzalezulises/CreditCardFraudPrediction) | Credit-card fraud detection with classification models. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) |
| [**ml-research-insights**](https://github.com/gonzalezulises/ml-research-insights) | Analysis of the ML Global Impact Report 2025: country trends, tools, and academic contributions. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Plotly](https://img.shields.io/badge/-Plotly-3F4F75?style=flat&logo=plotly&logoColor=white) |
| [**Practica_Final_NPL**](https://github.com/gonzalezulises/Practica_Final_NPL) | Final NLP project with applied natural-language processing. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![SpaCy](https://img.shields.io/badge/-SpaCy-09A3D5?style=flat&logo=spacy&logoColor=white) |
| [**DeepLearningWork**](https://github.com/gonzalezulises/DeepLearningWork) | Deep-learning experiments and projects. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white) |
| [**exploratory-data-analysis-pm25**](https://github.com/gonzalezulises/exploratory-data-analysis-pm25) | Exploratory analysis of PM2.5 emissions using the EPA National Emissions Inventory (1999–2008). | ![R](https://img.shields.io/badge/-R-276DC3?style=flat&logo=r&logoColor=white) |

### Academic Courses (Teaching Materials)

| Project | Description | Stack |
|---------|-------------|-------|
| [**bourbaki-ciencia-de-datos**](https://github.com/gonzalezulises/bourbaki-ciencia-de-datos) | Full Data Science track (49 weeks) covering probability, inference, regression, ML, and time series. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) |
| [**formacion-docente-bi-faces**](https://github.com/gonzalezulises/formacion-docente-bi-faces) | Faculty-development program in Data Science and BI. [Live](https://formacion-docente-bi-faces.vercel.app) | ![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) |
| [**data-analytics-course**](https://github.com/gonzalezulises/data-analytics-course) | Complete Data Analytics course with Python: 8 modules, 69 interactive exercises, 4 Colab notebooks. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Plotly](https://img.shields.io/badge/-Plotly-3F4F75?style=flat&logo=plotly&logoColor=white) ![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) |
| [**101_Data_Analytics_Rizoma**](https://github.com/gonzalezulises/101_Data_Analytics_Rizoma) · [**201-Ciencia_de_Datos_Rizoma**](https://github.com/gonzalezulises/201-Ciencia_de_Datos_Rizoma) | Introductory and intermediate Data Science courses for Rizoma Academy. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) ![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) |

### Web, Landing Pages & Design Systems

| Project | Description | Stack |
|---------|-------------|-------|
| **rizo-web** `private` | Rizoma website (Astro + Tailwind). | ![Astro](https://img.shields.io/badge/-Astro-BC52EE?style=flat&logo=astro&logoColor=white) ![Tailwind](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat&logo=tailwind-css&logoColor=white) |
| [**rizoma-ui**](https://github.com/gonzalezulises/rizoma-ui) | Centralized Rizoma design system with shared tokens, components, and styles. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) |
| **dojo** `private` | High-impact landing page for a martial-arts dojo (i18n ES/EN/JA, Astro monorepo). | ![Astro](https://img.shields.io/badge/-Astro-BC52EE?style=flat&logo=astro&logoColor=white) ![Tailwind](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat&logo=tailwind-css&logoColor=white) |
| [**gonzalez-gonzalez-web**](https://github.com/gonzalezulises/gonzalez-gonzalez-web) | Corporate website for an accounting & audit firm. [Live](https://gonzalez-gonzalez-web.vercel.app) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) |
| [**mas-control-mas-caos**](https://github.com/gonzalezulises/mas-control-mas-caos) | Landing page for the book "Más control, más caos". [Live](https://mas-control-mas-caos.vercel.app) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Vercel](https://img.shields.io/badge/-Vercel-000?style=flat&logo=vercel&logoColor=white) |
| **gerencia-funcional** `private` | Manuscript of the book "Más control, más caos": 263 pages, 20 chapters, 7 appendices. | ![Markdown](https://img.shields.io/badge/-Markdown-000?style=flat&logo=markdown&logoColor=white) ![LaTeX](https://img.shields.io/badge/-LaTeX-008080?style=flat&logo=latex&logoColor=white) |
| [**opsflow-demo**](https://github.com/gonzalezulises/opsflow-demo) | Interactive demo: how Rizoma optimizes operations with applied data science. [Live](https://opsflow-demo.vercel.app) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) |
| [**dama-panama**](https://github.com/gonzalezulises/dama-panama) | Official DAMA Panama website with study-group registration, admin panel, rate limiting, CAPTCHA, and email confirmation. [Live](https://dama-panama.vercel.app) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) |

---

### Tech Stack

**AI Engineering & Infrastructure:**
![Claude Code](https://img.shields.io/badge/-Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/-MCP_(Model_Context_Protocol)-D97757?style=flat)
![Codex](https://img.shields.io/badge/-Codex-412991?style=flat&logo=openai&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/-Gemini_2.5-4285F4?style=flat&logo=googlegemini&logoColor=white)
![NVIDIA DGX](https://img.shields.io/badge/-DGX_Spark_(Blackwell)-76B900?style=flat&logo=nvidia&logoColor=white)
![vLLM](https://img.shields.io/badge/-vLLM-FF6B6B?style=flat)
![NVIDIA NIM](https://img.shields.io/badge/-NVIDIA_NIM-76B900?style=flat&logo=nvidia&logoColor=white)
![Milvus](https://img.shields.io/badge/-Milvus-00A1EA?style=flat)
![Hugging Face](https://img.shields.io/badge/-Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![ComfyUI](https://img.shields.io/badge/-ComfyUI-000?style=flat)
![n8n](https://img.shields.io/badge/-n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![CUDA](https://img.shields.io/badge/-CUDA_13-76B900?style=flat&logo=nvidia&logoColor=white)

**Python & Data Science:**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Polars](https://img.shields.io/badge/-Polars-CD792C?style=flat&logo=polars&logoColor=white)
![SciPy](https://img.shields.io/badge/-SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat)
![Plotly](https://img.shields.io/badge/-Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)

**Machine Learning & Deep Learning:**
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat&logo=keras&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![NLTK](https://img.shields.io/badge/-NLTK-154F5B?style=flat)
![SpaCy](https://img.shields.io/badge/-SpaCy-09A3D5?style=flat&logo=spacy&logoColor=white)
![XGBoost](https://img.shields.io/badge/-XGBoost-337AB7?style=flat)

**TypeScript & Web:**
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js&logoColor=white)
![Astro](https://img.shields.io/badge/-Astro-BC52EE?style=flat&logo=astro&logoColor=white)
![Tailwind](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat&logo=tailwind-css&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/-shadcn/ui-000?style=flat&logo=shadcnui&logoColor=white)
![D3.js](https://img.shields.io/badge/-D3.js-F9A03C?style=flat&logo=d3.js&logoColor=white)
![Prisma](https://img.shields.io/badge/-Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Drizzle](https://img.shields.io/badge/-Drizzle_ORM-C5F74F?style=flat&logo=drizzle&logoColor=black)
![Vitest](https://img.shields.io/badge/-Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Zod](https://img.shields.io/badge/-Zod-3068B7?style=flat&logo=zod&logoColor=white)

**SQL, Cloud & Infrastructure:**
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![BigQuery](https://img.shields.io/badge/-BigQuery-669DF6?style=flat&logo=google-bigquery&logoColor=white)
![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![Neon](https://img.shields.io/badge/-Neon-00E699?style=flat&logo=neon&logoColor=black)
![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Google Cloud](https://img.shields.io/badge/-Google_Cloud-4285F4?style=flat&logo=google-cloud&logoColor=white)
![Vercel](https://img.shields.io/badge/-Vercel-000?style=flat&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/-Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)
![Tailscale](https://img.shields.io/badge/-Tailscale-000?style=flat&logo=tailscale&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/-Pydantic-E92063?style=flat&logo=pydantic&logoColor=white)

**BI & Visualization:**
![Power BI](https://img.shields.io/badge/-Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/-Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Looker](https://img.shields.io/badge/-Looker-4285F4?style=flat&logo=looker&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat&logo=r&logoColor=white)
![Shiny](https://img.shields.io/badge/-Shiny-276DC3?style=flat&logo=r&logoColor=white)

---

**Education:** MIT Professional Education (AI & ML) | ADEN (Master Big Data) | IESA (MBA) | UNITEC (Mechanical Engineering)

**Certifications:** PMP | PMI-ACP | PSM II | PSPO III | ICF ACC | Six Sigma Black Belt | DevOps Leader

**Focus areas:** AI products & agents | Organizational analytics | Process & PMO | Executive education

---

gonzalez.ulises@gmail.com | [rizo.ma](https://rizo.ma) | [LinkedIn](https://linkedin.com/in/ulisesgonzalez) | [@gonzalezulises](https://twitter.com/gonzalezulises)
