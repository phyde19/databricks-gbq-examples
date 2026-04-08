# BigQuery on Databricks — New User Onboarding

## Context

Onboarding session for BI team members who will read and write BigQuery from Databricks notebooks. This covers the two supported integration paths:

- **Python client** (`google-cloud-bigquery`) — metadata, queries, DDL, small data loads
- **Spark BigQuery connector** — distributed DataFrame reads/writes via the Storage APIs

## Notebook

- [`bigquery-read-write-patterns.ipynb`](./bigquery-read-write-patterns.ipynb) — self-contained walkthrough of the most common patterns

## Prerequisites

- Notebook must run on a **BigQuery-enabled compute cluster** (the compute profile handles ADC/WIF auth automatically)
- No credential code is required in the notebook
- Project: `idd-dscoe-nonprod-1`, Dataset: `p17851h` — configurable at the top of the notebook
