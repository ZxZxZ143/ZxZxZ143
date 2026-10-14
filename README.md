# AI & Backend Engineering

**ZxZxZ143** · Building conversational AI, reliable APIs and data pipelines.

I connect models to application state, external systems and usable interfaces — with explicit contracts, tests and deployment paths.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/engineering-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/engineering-light.svg">
  <img alt="From signal to system — AI, services and data connected in one engineering pipeline." src="assets/engineering-light.svg" width="1200">
</picture>

[Featured work](#featured-engineering-work) · [Technical focus](#technical-focus) · [About](#about) · [All repositories](https://github.com/ZxZxZ143?tab=repositories)

## Featured Engineering Work

### 01 · [Veyra — Banking Voice Platform](https://github.com/ZxZxZ143/banking-voice-manager)

A conversational platform for Russian, Kazakh and mixed-language financial support across browser and phone channels.

`Python` `FastAPI` `OpenAI Agents SDK` `React` `SQLite`

- Isolated assistant state, structured routing and confirmation before accepting spoken identifiers.
- Shared speech and event pipelines connect advisory risk analysis to a supervisor dashboard.

[Architecture](https://github.com/ZxZxZ143/banking-voice-manager/blob/main/docs/ARCHITECTURE.md) · [Voice validation](https://github.com/ZxZxZ143/banking-voice-manager/blob/main/docs/VOICE_LATENCY_AND_CORRECTION_VALIDATION.md)

*Local demo with synthetic business data; Twilio/Vonage adapters have offline validation, with live PSTN verification pending.*

### 02 · [Canvas Student MCP](https://github.com/ZxZxZ143/canvas_mcp)

A personal, read-only integration that lets Codex retrieve coursework context and inspect authorized Canvas materials.

`Python` `MCP` `Pydantic` `HTTPX` `pytest`

- Domain, application and infrastructure boundaries separate coursework queries from the MCP adapter.
- Credential-free file downloads enforce origin, redirect, size and format policies; managed artifacts carry SHA-256 digests.

[File architecture](https://github.com/ZxZxZ143/canvas_mcp/blob/main/docs/secure-file-layer.md) · [Plugin guide](https://github.com/ZxZxZ143/canvas_mcp/blob/main/docs/personal-plugin.md)

*Windows-first local plugin with bounded outputs and synthetic contract/security tests.*

### 03 · [Vympel — Commerce & CRM](https://github.com/ZxZxZ143/vympel)

A commerce monorepo connects a multilingual storefront, protected CRM and shared backend services.

`Java` `Spring Boot` `Next.js` `PostgreSQL` `Redis` `S3`

- Rotating CRM sessions and transactional CMS revalidation jobs bridge security and content delivery.
- Independent application images, release gates and multi-architecture verification make releases inspectable.

[System map](https://github.com/ZxZxZ143/vympel/blob/main/docs/PROJECT_MAP.md) · [Deployment runbook](https://github.com/ZxZxZ143/vympel/blob/main/docs/deployment/DEPLOYMENT_RUNBOOK.md)

*Local stack and release evidence are documented; external production readiness remains gated.*

### 04 · [Contract Document Pipeline](https://github.com/vesta-12/contract_extractor_module)

A team project turns uploaded PDFs into extracted contract entities, annotated documents and downloadable results.

`Python` `FastAPI` `Tesseract` `PyMuPDF` `Docker`

- OCR, layout recovery, rule-based extraction and entity linking form an inspectable processing chain.
- My contribution connected the existing components to job orchestration, storage, HTTP endpoints and container packaging.

[Contribution](https://github.com/vesta-12/contract_extractor_module/commit/0ac4b588f3cc149464296d19fd4c650e398929c2) · [Pipeline](https://github.com/vesta-12/contract_extractor_module/blob/master/src/document_processing/pipeline.py)

### 05 · [Banking Data Warehouse](https://github.com/ZxZxZ143/dwh-building-scripts)

A banking-domain warehouse combines relational, CSV and JSON sources into analytical models.

`Python` `SQL` `Airflow` `dbt` `PostgreSQL`

- Watermark-based ingestion feeds bronze, silver and gold layers from five source families.
- Client 360 and daily metrics use explicit model dependencies and dbt data assertions.

[Architecture & setup](https://github.com/ZxZxZ143/dwh-building-scripts#architecture) · [Gold models](https://github.com/ZxZxZ143/dwh-building-scripts/tree/master/dbt/bank_dwh/models/gold)

### 06 · [Speech & Transcript Analytics](https://github.com/ZxZxZ143/transcribe)

A local ML application converts RU/KK recordings into quality-tagged transcripts and semantic clusters.

`Vosk` `BGE-M3` `scikit-learn` `FastAPI` `pandas`

- Language scoring and transcript cleanup preserve separate raw, cleaned and semantic representations.
- Embeddings, optional PCA and selectable clustering produce inspectable CSV outputs and timing diagnostics.

[Setup & limits](https://github.com/ZxZxZ143/transcribe#quick-start) · [Clustering](https://github.com/ZxZxZ143/transcribe/blob/main/clustering/cluster_transcripts.py)

## Technical Focus

| Area | Tools used in these projects |
| --- | --- |
| AI & ML | Structured LLM routing, MCP, speech recognition, embeddings, clustering |
| Backend & APIs | Python, Java, FastAPI, Spring Boot, REST, WebSockets |
| Data & Storage | PostgreSQL, SQLite, pandas, SQLAlchemy, dbt, S3-compatible storage |
| Infrastructure & Tools | Docker Compose, GitHub Actions, Nginx, Airflow, pytest, JUnit, Vitest |

## About

Fourth-year Digital Engineering student at **Narxoz University**, with ML & Data Engineering practice and team project experience. My current focus is connecting AI capabilities to dependable software boundaries.

More work: [CodeRealm's interactive programming RPG](https://github.com/ZxZxZ143/codeRealm) · [GameMatch team contributions](https://github.com/nastoikazhenshen/gamematch-backend/commits?author=ZxZxZ143).

## Connect

[GitHub · @ZxZxZ143](https://github.com/ZxZxZ143)
