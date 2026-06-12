## Phil McKechnie

**Business Intelligence Analyst and Data Engineer — Melbourne, Australia**

15+ years across operations, supply chain and analytics. The last 5 years in dedicated BI / Operations Analyst roles working with SQL, Tableau, Power BI and stakeholder reporting. Currently building a data engineering portfolio with dbt, Snowflake, Airflow, Python and AWS-native lakehouse work (S3, Glue, Athena, Step Functions, Iceberg) — covering ETL pipelines, dimensional modelling, data warehouse and lakehouse architectures. Comfortable across both analytics delivery and the data platform underneath it.

### Focused Projects

Tightly scoped, single-theme builds — each goes deep on one core skill.

- **[analytics-tsql-adf-project](https://github.com/Pheluciam/analytics-tsql-adf-project)** — T-SQL depth on real Jira issue data. Jira REST API → Azure Data Factory (paginated raw JSON, no flattening) → Azure SQL → T-SQL star schema (OPENJSON shred, MERGE upserts, stored procedures, presentation views) → 3-page Power BI dashboard with 25 documented DAX measures.
- **[operations-analytics-dbt-tableau-project](https://github.com/Pheluciam/operations-analytics-dbt-tableau-project)** — dbt testing + macros depth on the AdventureWorks distribution slice. PostgreSQL → dbt (custom generic tests, dbt-utils + dbt-expectations, reusable macro, incremental model, snapshot — 155 tests green) → [live three-dashboard Tableau Public workbook](https://public.tableau.com/views/adventureworks_operations/OutboundSalesCustomer?:display_count=n&:origin=viz_share_link).

### End-to-End Platform Projects

Larger architecture builds across cloud warehouse, lakehouse and orchestration stacks.

- **[financial-analytics-lakehouse-project](https://github.com/Pheluciam/financial-analytics-lakehouse-project)** — AWS-native data lakehouse on SEC EDGAR XBRL fundamentals for the S&P 100. Direct-to-S3 raw → dbt-athena on Apache Iceberg → AWS Step Functions orchestration → 6-page Power BI analytical report with univariate revenue forecasting.
- **[retail-demand-forecasting-project](https://github.com/Pheluciam/retail-demand-forecasting-project)** — production-grade retail demand-planning pipeline. M5 Forecasting (Kaggle/Walmart) → Azure SQL → Python extract → Snowflake → Airflow (Docker) → dbt (Kimball star) → Snowflake Cortex forecast → 5-page Power BI dashboard.
- **[cdc-nt-gtfs-project](https://github.com/Pheluciam/cdc-nt-gtfs-project)** — two NT GTFS feeds (Darwin + Alice Springs) → Python ingestion → PostgreSQL → dbt (Kimball star) → 4-page Power BI dashboard. Multi-feed surrogate keys resolving cross-feed ID collisions; Kimball modelling foundation.

### Earlier Learning

- **[pheluciam.github.io](https://pheluciam.github.io)** — 2023 self-directed learning portfolio. Background only; see the projects above for current work.

### Stack

- **SQL & modelling:** PostgreSQL, T-SQL, Snowflake, dbt, dbt-athena, dimensional modelling, Data Vault 2.0
- **Pipelines:** Airflow, Azure Data Factory, AWS Step Functions, Python (pandas), Docker
- **BI & reporting:** Power BI, Tableau (live Tableau Public workbook)
- **Cloud / lakehouse:** AWS (S3, Glue, Athena, Step Functions, Lake Formation), Azure (Data Factory, Azure SQL), Apache Iceberg

### Background

NEC Australia (BI Analyst & Programmer, Sept 2023 – Mar 2026). Prior 15+ years across operations and supply chain analytics — Harding's Hardware, Alex Makes Meals, Spartan School Supplies.

Open to roles in Melbourne's north-eastern, eastern and south-eastern suburbs.
