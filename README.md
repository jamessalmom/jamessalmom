# Tiago Coutinho

## Senior Systems Analyst | Python, Flask, SQL, BI, and Data Integration

I work at the intersection of business needs and engineering. Over the past nine years, I have worked across the full lifecycle of corporate systems, from requirements and data modeling to implementation, deployment, and production support.

My experience includes high-stakes environments such as instant payments (PIX) and digital health. I enjoy turning complex processes into software that is reliable, measurable, and easy to evolve.

I also use AI-assisted tools such as Claude Code and OpenAI Codex as part of my daily engineering workflow. I use them to accelerate implementation, documentation, and code review while keeping architecture, quality, and technical decisions grounded in sound engineering practice.

## What I work with

| Area | Focus |
|---|---|
| Backend | Python, Flask, PyQt5, REST APIs, JWT and session authentication, AD/LDAP integration, and role-based access control |
| Data | Advanced SQL, window functions, CTEs, procedures, dimensional modeling, and multi-database integration |
| BI and analytics | Power BI, DAX, Power Query, RLS, Flask dashboards, Chart.js, Streamlit, Plotly Dash, Metabase, and Tableau |
| Integrations | TOTVS, SAP, Omie, JSON/XML processing, retry and backoff strategies, structured logging, and PIX/SPI/DICT workflows |
| Cloud and delivery | AWS, Azure Data Factory, Docker, Linux, CI/CD, Gunicorn, and WSGI deployments |

## Current focus

I am currently building a BI and commercial analytics platform in Flask, covering everything from data modeling to production deployment. In parallel, I help sustain a high-availability PIX integration in a fintech environment.

My engineering approach is centered on clear boundaries, explicit data flows, predictable failure handling, and code that is easy to test and review. I believe good software should make business rules easier to understand, not hide them behind unnecessary complexity.

## Selected projects

These repositories are small, focused implementations of patterns that appear in real production systems. Each project includes tests with `pytest` and continuous integration checks with `ruff`.

| Project | Description |
|---|---|
| [pix-webhook-toolkit](https://github.com/jamessalmom/pix-webhook-toolkit) | A webhook receiver with HMAC verification and a resilient outbound client that supports retry, backoff, and idempotency. |
| [flask-rbac-kit](https://github.com/jamessalmom/flask-rbac-kit) | A reusable RBAC foundation for Blueprint-based Flask applications, with permission catalogs, audit trails, and local or LDAP authentication. |
| [multi-erp-etl](https://github.com/jamessalmom/multi-erp-etl) | A resilient ETL component that normalizes JSON and XML exports from different ERP systems into a consistent canonical schema. |
| [sql-kpi-toolkit](https://github.com/jamessalmom/sql-kpi-toolkit) | A collection of Jinja2-templated SQL queries for Pareto analysis, year-over-year variation, and goal-attainment KPIs. |
| [star-schema-builder](https://github.com/jamessalmom/star-schema-builder) | A utility that classifies flat-table columns and generates Kimball-style fact and dimension definitions. |
| [flask-chartjs-dashboard](https://github.com/jamessalmom/flask-chartjs-dashboard) | A server-side aggregated executive dashboard built with Flask and Chart.js, without the overhead of a single-page application. |
| [resilient-api-client](https://github.com/jamessalmom/resilient-api-client) | A `requests` wrapper with circuit-breaker behavior for unreliable partner and ERP APIs. |
| [powerbi-dax-toolkit](https://github.com/jamessalmom/powerbi-dax-toolkit) | A DAX naming and readability linter accompanied by practical examples for YTD, YoY, Pareto analysis, and RLS. |
| [crm-funnel-analytics](https://github.com/jamessalmom/crm-funnel-analytics) | A sales analytics toolkit for funnel analysis, consultant rankings, and corrections that preserve the original CRM data. |
| [incident-runbook-cli](https://github.com/jamessalmom/incident-runbook-cli) | A command-line tool that turns YAML incident runbooks into Markdown and flags transaction outliers with z-score analysis. |
| [ai-docstring-assistant](https://github.com/jamessalmom/ai-docstring-assistant) | A focused assistant that finds undocumented functions and classes, then prepares review-ready prompts for an LLM to draft docstrings. |

## A little more about my work

I am interested in Python and Flask architecture, BI platforms, data integration, payment systems, and practical applications of AI in software engineering. The projects above are where I experiment with these ideas in a compact, testable, and openly documented form.

Thanks for stopping by. Feel free to explore the repositories.
