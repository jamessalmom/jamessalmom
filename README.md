# Tiago Coutinho

## Senior Systems Analyst | Python, Flask, SQL, BI, and Data Integration

I work at the intersection of business needs and engineering. Over the past nine years, I have worked across the full lifecycle of corporate systems, from requirements and data modeling to implementation, deployment, and production support.

My experience includes high-stakes environments such as instant payments (PIX) and digital health. I enjoy turning complex processes into software that is reliable, measurable, and easy to evolve.

I also use AI-assisted tools such as Claude Code and OpenAI Codex as part of my daily engineering workflow. I use them to accelerate implementation, documentation, and code review while keeping architecture, quality, and technical decisions grounded in sound engineering practice.

## Technology stack

These are the tools I use most often across backend development, data work, analytics, testing, and delivery.

**Languages and core technologies**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=databricks&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white)

**Python frameworks and libraries**

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)

![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white) ![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white) ![Requests](https://img.shields.io/badge/Requests-2B5B84?style=for-the-badge&logo=python&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**Data, BI and delivery**

![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

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

## Pandas and regular expressions projects

I also maintain a set of practical projects focused on data preparation with Pandas and regular expressions. Each repository explores one focused problem, with Portuguese documentation, executable examples, and a clear explanation of the trade-offs behind the solution.

| Project | Focus |
|---|---|
| [pandas-regex-numeric-extraction](https://github.com/jamessalmom/pandas-regex-numeric-extraction) | Extracting numeric values from Brazilian-formatted text |
| [pandas-regex-email-validation](https://github.com/jamessalmom/pandas-regex-email-validation) | Validating email addresses with regular expressions |
| [pandas-regex-document-cleaning](https://github.com/jamessalmom/pandas-regex-document-cleaning) | Cleaning and classifying CPF and CNPJ values |
| [pandas-regex-address-parser](https://github.com/jamessalmom/pandas-regex-address-parser) | Splitting addresses into structured columns |
| [pandas-regex-hashtag-extraction](https://github.com/jamessalmom/pandas-regex-hashtag-extraction) | Extracting multiple hashtags with `str.findall` |
| [pandas-regex-date-normalization](https://github.com/jamessalmom/pandas-regex-date-normalization) | Normalizing dates with regex preprocessing and `to_datetime` |
| [pandas-regex-phone-normalization](https://github.com/jamessalmom/pandas-regex-phone-normalization) | Standardizing Brazilian phone numbers with a compiled regex |

## Analytics platform patterns

These repositories preserve the evolution of a small analytics platform across four annual snapshots. They bring together Pandas utilities, Flask routes, and reusable dashboard components, using synthetic data to demonstrate architecture and delivery patterns without exposing business information.

| Snapshot | Focus |
|---|---|
| [analytics-platform-patterns-2022](https://github.com/jamessalmom/analytics-platform-patterns-2022) | Foundational data, backend, and dashboard patterns |
| [analytics-platform-patterns-2023](https://github.com/jamessalmom/analytics-platform-patterns-2023) | Reusable analytics workflows and application components |
| [analytics-platform-patterns-2024](https://github.com/jamessalmom/analytics-platform-patterns-2024) | Data quality, Flask services, and dashboard integration |
| [analytics-platform-patterns-2025](https://github.com/jamessalmom/analytics-platform-patterns-2025) | Integrated patterns for an evolving analytics platform |

## A little more about my work

I am interested in Python and Flask architecture, BI platforms, data integration, payment systems, and practical applications of AI in software engineering. The projects above are where I experiment with these ideas in a compact, testable, and openly documented form.

Thanks for stopping by. Feel free to explore the repositories.
