# Hi, I'm Tiago Coutinho

**Senior Systems Analyst** — technical bridge between business and engineering, focused on Python/Flask, SQL, BI, and data/system integration.

9+ years across the full lifecycle of corporate systems, requirements to production support, in high-stakes domains: instant payments (PIX) and digital health. I'm usually the person other engineers bring code decisions and reviews to, and lately that includes wiring AI coding agents (Claude Code, OpenAI Codex) into the day-to-day workflow rather than just talking about them.


---

### What I work with

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PyQt5](https://img.shields.io/badge/PyQt5-41CD52?style=flat-square&logo=qt&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

- **Backend** — Flask (modular Blueprint architecture), PyQt5 desktop apps, REST APIs, JWT/session/AD-LDAP auth, RBAC with audit trail
- **Data** — advanced SQL (window functions, CTEs, procedures), dimensional modeling (Star Schema/Kimball), multi-database integration
- **BI & Analytics** — Power BI (DAX, Power Query, RLS), server-side dashboards (Flask + Chart.js), Streamlit, Plotly Dash, Metabase, Tableau
- **Integration** — multi-ERP (TOTVS, SAP, Omie), JSON/XML parsing, resilience patterns (retry/backoff, structured logging), PIX/SPI/DICT
- **Cloud & DevOps** — AWS (EC2, S3, Lambda, Glue, Athena, Redshift), Azure Data Factory, CI/CD, Gunicorn/WSGI, Docker
- **AI-assisted engineering** — Claude Code and OpenAI Codex in the daily workflow for implementation, docs, and test generation/review

### Currently

Building a BI/commercial-analytics platform in Flask from the ground up, from data modeling to production deploy, at a national construction-equipment rental company, alongside sustaining a PIX payments integration in a high-availability fintech environment.

---

### Featured projects

A set of small, focused, from-scratch projects distilling patterns from real production work — payments integrations, BI dashboards, ETL across ERPs, RBAC, and AI-assisted engineering. Each one is fully tested (`pytest`) and linted (`ruff`) in CI.

| Project | What it is |
|---|---|
| [pix-webhook-toolkit](https://github.com/jamessalmom/pix-webhook-toolkit) | HMAC-verified webhook receiver + resilient outbound client (retry/backoff, idempotency) for instant-payment-style integrations |
| [flask-rbac-kit](https://github.com/jamessalmom/flask-rbac-kit) | RBAC for Blueprint-based Flask apps: permission catalog, `@requires_permission`, audit trail, hybrid local/LDAP auth |
| [multi-erp-etl](https://github.com/jamessalmom/multi-erp-etl) | Normalizes JSON/XML exports from heterogeneous ERPs into one canonical schema; bad rows don't sink the batch |
| [sql-kpi-toolkit](https://github.com/jamessalmom/sql-kpi-toolkit) | Jinja2-templated SQL for Pareto 80/20, YoY variation, and goal-attainment KPIs |
| [star-schema-builder](https://github.com/jamessalmom/star-schema-builder) | Classifies flat table columns into measures/dimensions and generates Kimball-style fact/dimension DDL |
| [flask-chartjs-dashboard](https://github.com/jamessalmom/flask-chartjs-dashboard) | Server-side-aggregated dark-mode executive dashboard (Flask + Chart.js, no SPA) |
| [resilient-api-client](https://github.com/jamessalmom/resilient-api-client) | `requests` wrapper with a circuit breaker for flaky partner/ERP APIs |
| [powerbi-dax-toolkit](https://github.com/jamessalmom/powerbi-dax-toolkit) | DAX naming/readability linter + a documented snippet library (YTD, YoY, Pareto, RLS) |
| [crm-funnel-analytics](https://github.com/jamessalmom/crm-funnel-analytics) | Sales funnel, consultant ranking, and an "override without overwrite" correction layer for CRM exports |
| [incident-runbook-cli](https://github.com/jamessalmom/incident-runbook-cli) | YAML-as-code incident runbooks rendered to Markdown, plus a z-score outlier flagger for transaction triage |
| [ai-docstring-assistant](https://github.com/jamessalmom/ai-docstring-assistant) | Scans a codebase for undocumented functions/classes and builds focused, review-ready prompts for an LLM to draft docstrings |

---

### GitHub stats

<img src="https://github-readme-stats.vercel.app/api?username=jamessalmom&show_icons=true&theme=default&hide_border=true&count_private=true" alt="Tiago's GitHub stats" height="165"/> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jamessalmom&layout=compact&hide_border=true&theme=default" alt="Top languages" height="165"/>

---

💬 Open to conversations about Python/Flask architecture, BI platforms, or bringing AI coding agents into an existing engineering workflow.
