# Hi, I'm Abdirahman 👋

**Analytics engineer in Toronto.** I build the full data stack, from raw ingestion to tested dbt models to dashboards people actually use. I care about clean grain, honest metrics, and pipelines that can be re-run safely.

[Portfolio](https://abdirahmanali.dev) · [Email](mailto:abdirahman2ali@gmail.com)

---

## What I'm working on

- **Financial due diligence platform:** SEC EDGAR filings into Databricks, scored company health metrics in dbt, peer benchmarks by GICS sector, served through Omni.
- **AI-assisted automations:** small Python tools that use Claude to score and route data, then send a digest.
- Always tightening the portfolio itself: CI, idempotent loads, and models that pass their tests.

## Featured projects

| Project | What it does | Stack |
|---|---|---|
| [analytics-portfolio](https://github.com/abdirahman2ali/analytics-portfolio) | Monorepo of end-to-end pipelines (NBA, Toronto parking, financial due diligence). Python ingestion, one shared dbt project, Omni for BI. | Python, dbt, Databricks, Omni |
| [lead-pipeline](https://github.com/abdirahman2ali/lead-pipeline) | Ingest, deduplicate, AI score with Claude, route to reps, alert on hot leads. | Python, Claude |
| [county-records-monitor](https://github.com/abdirahman2ali/county-records-monitor) | Weekly watch on Florida county records for distress filings, scored by Claude and emailed as an HTML digest. | Python, Claude |
| [job-search](https://github.com/abdirahman2ali/job-search) | Scores contract roles with Claude and emails a daily digest. | Python, Claude |
| [portfolio](https://github.com/abdirahman2ali/portfolio) | My personal site, hosted on GitHub Pages. | HTML, CSS |

## How I build

- **Layered models:** staging, intermediate, marts, with one schema per domain.
- **Idempotent ingestion:** MERGE-based upserts so a re-run never creates duplicates.
- **Tested before merge:** `ruff` and `pytest` run in CI on every ingestion PR, and I run `dbt test` on changed models before opening it.
- **Semantic layer in mind:** descriptions, keys, and relationships live in `schema.yml` so BI tools inherit them.

## Tools

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?logo=postgresql&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?logo=dbt&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-EF3E2E?logo=databricks&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?logo=snowflake&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Omni](https://img.shields.io/badge/Omni-BI-6C47FF)
![Looker](https://img.shields.io/badge/Looker-4285F4?logo=looker&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?logo=tableau&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

## Ask me about

dbt, dimensional modeling, Databricks, moving from Looker to Omni, and wiring LLMs into data pipelines without making them the source of truth.

## Open to

Analytics engineering and BI contract work. The fastest way to reach me is email.
