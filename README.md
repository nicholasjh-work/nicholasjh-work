# Nicholas Hidalgo

I run data and search platform products at a publicly traded company (NASDAQ) in Boston. 10+ years across enterprise analytics, warehouse design, BI migrations, and more recently, building AI workflows on top of governed data.

My day job stack is Snowflake, Oracle, dbt, Power BI, Python, and SQL. The repos here go in a different direction: practical AI tooling for companies that don't have a 50-person data team but still need to ship.

## What I'm building

Most AI repos on GitHub are demos. Clean datasets, happy-path queries, no auth, no cost tracking, no governance. I've spent a decade inside messy enterprise systems, so I build for the mess.

**dbt-ai-patterns** -- dbt packages for AI-ready data pipelines. Semantic layer definitions for LLM consumption, PII detection macros, data contracts for AI features, Snowflake Cortex integration. Built for the 60,000+ teams already running dbt who want AI without a replatform.

**ai-data-quality-toolkit** -- Enterprise DQ frameworks applied to LLM outputs. Maps the six traditional dimensions (accuracy, completeness, consistency, timeliness, validity, uniqueness) to AI output validation. Python, dbt-style tests, ISO 5259 alignment. Most eval tools measure hallucination rates. This measures whether the output is actually fit for a business decision.

**ai-cost-guardian** -- FinOps for AI at startup scale. Per-feature cost attribution, spend anomaly detection, budget alerting, ROI templates. Python + SQL + dashboards. The thing everyone worries about but nobody instruments.

**enterprise-text-to-sql** -- NL-to-SQL for real schemas. Not academic benchmarks. Uses dbt docs for schema context, the Semantic Layer for disambiguation, cost estimation before execution, and row-level security awareness. GPT-4 solves 6% of enterprise SQL questions on Spider 2.0. That number is the whole motivation.

**ai-governance-starter** -- AI governance for companies that aren't Google. Policy templates, risk frameworks simplified from NIST AI RMF, audit trails, vendor scorecards. Microsoft built theirs for Fortune 500. This is for everyone else.

## Existing portfolio

**Subscription Financial Model** -- Churn and revenue on KKBox data. PostgreSQL, dbt, Supabase, Streamlit. Cohort retention at 30/60/90 days, churn scoring, LTV. Dark-theme dashboard designed in Figma.

**Governed RAG + Text-to-SQL** -- Business users query structured data in plain English with RBAC, audit logging, and governance guardrails. FastAPI, PostgreSQL, Qwen3-14B, Redis.

**Executive Financial KPI Dashboard** -- Power BI, DAX, Snowflake. Drill-through, exception flags, automated refresh. Built for the C-suite.

## Why this exists

88% of AI proofs-of-concept never make it to production. The failure point is almost never the model. It's data quality. Governance. Cost surprises. Operational gaps that enterprise data teams solved years ago but the AI community keeps rediscovering. I kept watching smart people hit the same walls, so I started building the missing pieces in the open.

## Stack

Data engineering, AI/ML, search, BI, cloud infrastructure, identity/security, product delivery, data governance, and analytics. Full breakdown below.

<details>
<summary>Full stack (11 categories)</summary>

**Data Engineering** -- SQL (advanced), Snowflake, Databricks, Oracle, PostgreSQL, MySQL, DuckDB, dbt, Azure Data Factory, Microsoft Fabric, dimensional/semantic data modeling, ETL/ELT pipeline design, metadata and lineage, master data management

**AI/ML Engineering** -- Python, pandas, NumPy, scikit-learn, LLMs, RAG pipelines, vector search (HNSW, IVF-PQ), cross-encoder rerankers, text-to-SQL, AI agents, drift detection (PSI, KS), eval metrics (recall@k, MRR, NDCG)

**Statistical & Experimental** -- A/B testing, experiment design, statistical testing, cohort analysis, retention modeling, forecasting, funnel analysis

**Product & Behavioral Analytics** -- product analytics, user engagement, feature adoption, retention analytics, RFM analysis

**Search** -- Elasticsearch, vector databases/ANN, hybrid search (BM25 + dense)

**APIs & Integration** -- FastAPI, REST/OpenAPI design, OAuth2/OIDC/SAML, webhooks, SDK integration, JSON Schema/XSD

**BI & Visualization** -- Power BI, DAX, Power Query, Tableau, OBIEE, Streamlit, Matplotlib, Plotly

**Cloud & Infrastructure** -- Azure, AWS, Docker, Redis, OpenTelemetry, Splunk, Datadog

**Identity & Security** -- SSO, RBAC, least-privilege design, IdP integration (Okta, Ping, Auth0), entitlement reviews, audit trails

**Product & Delivery** -- product roadmaps, requirements definition, prioritization, dependency management, release planning, UAT, phase-gate delivery, product discovery, backlog management, sprint planning, Agile/Scrum, SDLC governance

**Data Governance & Compliance** -- Data Management Office design, policy development, data stewardship, reference data governance, data lineage documentation, KPI governance, SOX/GLBA/DPPA/PII compliance, internal audit partnership, control documentation, risk controls, dual-approval workflows, fraud controls

</details>

## Background

MS Operations & Project Management + MBA from SNHU. BS Information Technology from Zulia State University. 26 certifications. Currently leading a team of senior and associate PMs with a multi-million dollar budget.

## Contact

analytics@nicholashidalgo.com | [LinkedIn](https://linkedin.com/in/nicholashidalgo)

<!--
**nicholasjh-work/nicholasjh-work** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
