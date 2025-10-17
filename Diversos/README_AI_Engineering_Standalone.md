
# README — ML/AI Engineering + Automation (stand‑alone, zero‑to‑pro, unlimited budget)

## Outcomes
- Ship one production assistant with tool use, structured JSON, evals, and guardrails.
- Ship one RAG app with citations and latency/cost budgets.
- Automate one cross‑app workflow that updates a CRM or knowledge base.

## Assumptions
- Budget is not a constraint. Prioritize speed, safety, and maintainability.
- Primary language: Python. Repo and infra are green‑field.

## Architecture (reference)
- **Cloud**: pick one primary (AWS or GCP). Single account/project + separate **dev / staging / prod**.
- **Compute**: containers (Docker) on Kubernetes; serverless for light jobs (Cloud Run/Lambda).
- **Data**: Postgres for app data; object storage (S3/GCS) for blobs; optional warehouse (BigQuery/Snowflake).
- **Vectors**: pgvector or a managed service (Pinecone/Weaviate). Start with pgvector unless scale proves otherwise.
- **Secrets**: AWS Secrets Manager or GCP Secret Manager. No secrets in code or CI logs.
- **LLM**: OpenAI Enterprise; **Responses API** with structured outputs and function calling. Zero‑retention mode on for sensitive data.
- **Observability**: logs + traces (OpenTelemetry), error tracking (Sentry), metrics (Datadog/Cloud Monitoring), LLM traces (LangSmith).
- **CI/CD**: GitHub Actions + branch protection; blue‑green or canary deploy.
- **Security**: SSO (Okta/Google), least‑privilege IAM, VPC egress allow‑list, input/output content filters, red‑team tests.
- **Design/UX**: Figma for UI; design tokens; a11y baseline (WCAG 2.2 AA).

## Tools (enterprise‑grade options)
- **Dev**: Cursor or VS Code + Copilot, Ruff/Black/mypy, pre‑commit, pytest, uv/poetry.
- **MLOps/LLMOps**: LangChain or LlamaIndex; LangGraph for agents; LangSmith for tracing and evals; Weights & Biases for experiments; MLflow model registry if needed.
- **Data**: Airbyte/Fivetran for EL; dbt for T; DuckDB for local analytics; Great Expectations for data tests.
- **Automation**: Zapier, Make, n8n, or Pipedream. Standardize on one.
- **Security**: Semgrep/CodeQL, Dependabot, SAST/DAST in CI; Vault optional.
- **Docs**: MkDocs + Material theme; diagrams with Mermaid; runbooks in repo.

## Learning path (16 weeks)
**Weeks 1–2 — Foundations**
- Python intro (choose one): CS50P, Python for Everybody, or Automate the Boring Stuff.
- SQL: Mode SQL School L1–L10.
- Statistics basics: Khan Academy; skim ISLR videos.
- Milestone: 1‑page PRD and SOP for a micro‑assistant. Setup repo and CI.

**Weeks 3–4 — OpenAI core**
- Read OpenAI docs; build a CLI that returns structured JSON and calls one tool.
- Add eval fixtures and golden outputs. Ship v0.

**Weeks 5–6 — RAG baseline**
- Implement retrieval with embeddings, chunking, and citations. Add faithfulness checks.
- Log traces in LangSmith. Ship private‑docs assistant.

**Weeks 7–8 — Orchestration**
- Move to LangGraph or LlamaIndex workflows. Add tool routing and fallback rules.
- Add regression tests and cost/latency budgets.

**Weeks 9–10 — Automation**
- Create one workflow that triggers your assistant from email/form and updates CRM/docs.
- Add rate limits, retries, and idempotency keys.

**Weeks 11–12 — Reliability + realtime**
- Explore Realtime API if voice/streaming matters. Add partial results and timeouts.
- Incident runbook, error budgets, and alerts.

**Weeks 13–14 — Security + privacy**
- Apply OWASP LLM Top‑10. Prompt‑injection tests, output handling, allow‑lists, PII redaction.
- Threat model, data‑flow diagram, and compliance notes.

**Weeks 15–16 — Capstones**
- Pick two: triage bot, research assistant, ops co‑pilot, newsletter engine. Demo with KPIs.

## Design curriculum (run alongside)
- Google UX Design Professional Certificate (Coursera).
- UCSD Interaction Design Specialization (Coursera).
- CalArts Graphic Design Specialization (Coursera).
- MIT OCW User Interface Design & Implementation.
- Figma Learn; Storytelling with Data; Duarte slide design.
- Milestones: Week 2 low‑fi wireframes; Week 6 usability tests (n=5); Week 10 interactive prototype; Week 16 data‑viz review.

## Courses (primary)
- CS50P; Python for Everybody; Automate the Boring Stuff.
- Mode SQL School.
- DeepLearning.AI: RAG, Advanced RAG, LangChain, LlamaIndex, MLE for Production (MLOps).
- fast.ai Practical Deep Learning.
- OpenAI API + Responses API guides.

## AI‑assisted study loop (daily, 45 minutes)
1) Plan: 3‑line micro‑PRD. Ask the model to critique scope and risks.
2) Learn: one lesson → model produces 5 bullets + two analogies.
3) Practice: tiny artifact; request a rubric‑based critique and a “minimal diff” patch.
4) Retrieve: auto‑generate 10 flashcards; export to Anki.
5) Reflect: log blockers; ask for one drill and one next action.

## Evals and KPIs
- Task success ≥80% on held‑out set; faithfulness ≥0.8; jailbreak tests pass.
- p95 latency < target; cost per task tracked; error rate trending down.
- Security checks automated in CI; secrets scanned; SBOM produced.

## Runbooks (minimum)
- Incident response; rollback and feature flags; data deletion; rotation of keys; access reviews.

## License
Personal use. Fork and adapt.
