# 👋 Hey, I'm Ashok Chowdary

**Data Engineer (Fintech)** building production-grade data platforms, dbt/Snowflake pipelines, and real-time streaming systems for US financial-services clients.

- 📍 Based in **Montgomery, Alabama, USA**
- 🎓 **MS Computer Science**, Auburn University at Montgomery (Dec 2026)
- 🧾 **US Work Authorization** — no sponsorship required, available immediately
- 🎯 Target roles: **Data Engineer · Analytics Engineer · Data Platform Engineer**

---

## 👨‍💻 About Me

Data Engineer with **5+ years** of experience building cloud data platforms for US **fintech and financial-services** clients.[file:1] I’ve worked on a **$50B mortgage-servicing data platform**, scaling data from **2TB → 15TB** and optimizing warehouse and SQL performance end to end.[file:1]

I enjoy designing **dbt/Snowflake** models, **Airflow** pipelines, and **observability** patterns (Monte Carlo, Great Expectations) that make data reliable, fast, and cost-efficient.[file:1] My recent work includes zero-downtime **Redshift → Snowflake** migrations and real-time loan/stock pipelines.

**Quick profile**

- Name: Ashok Chowdary  
- Role: Data Engineer  
- Location: Montgomery, Alabama, USA  
- Education: MS CS — Auburn University at Montgomery (Dec 2026)[file:1]  
- Work Auth: US work authorization — **no sponsorship required**[file:1]  
- Specialty: dbt · Snowflake · BigQuery · Airflow · Spark · Terraform · Power BI  
- Contact: [ashokchowdary776@gmail.com](mailto:ashokchowdary776@gmail.com)  
- LinkedIn: [linkedin.com/in/ashok-s1](https://www.linkedin.com/in/ashok-s1)  
- Portfolio: [github.com/Ashok98765vvs](https://github.com/Ashok98765vvs)

---

## 🏆 Key Impact

| Area                | Impact                                                                 |
|---------------------|------------------------------------------------------------------------|
| Cost Reduction      | **35%** lower Snowflake/BigQuery compute via dbt model & warehouse tuning[file:1] |
| Query Performance   | **45%** faster avg query runtimes via SQL + materialization optimization[file:1] |
| Data Reliability    | **60%** fewer data incidents with Monte Carlo + Great Expectations[file:1] |
| Platform Scale      | **$50B+** mortgage-servicing data platform (**2TB → 15TB**) on Snowflake & BigQuery[file:1] |
| Pipeline Automation | 6-hour manual reporting process → **5-minute** automated pipeline     |
| Migration           | Zero-downtime **Redshift → Snowflake** migration (150+ downstream reports)[file:1] |

---

## 🛠 Tech Stack

**Cloud & Warehouses**

- Snowflake · BigQuery · Redshift · Databricks · Azure Synapse  
- AWS · GCP · Azure

**Transformation & Orchestration**

- dbt (Core & Cloud) · Apache Airflow · Fivetran · Stitch  
- Power Query · ADF

**Data & Analytics**

- Apache Spark (PySpark) · Kafka · Delta Lake  
- Power BI (PL-300) · DAX · Monte Carlo · Great Expectations

**Languages & DevOps**

- Python · SQL  
- Terraform · GitHub Actions · Docker · CI/CD

**Certifications**

- Google Cloud Professional Data Engineer  
- dbt Analytics Engineering  
- Microsoft Power BI Data Analyst (PL-300)  
- Databricks Certified Data Engineer  
- AWS Solutions Architect

---

## 💼 Fintech Case Studies

### 1️⃣ Mortgage Servicing Data Platform – Snowflake & BigQuery

**Context:** US mortgage servicer managing **$50B+** in loan portfolios needed a scalable, compliant analytics platform.[file:1]

- Owned and optimized core data infra on **Snowflake + BigQuery**, scaling from **2TB → 15TB** across loan servicing, payments, and customer analytics domains.[file:1]  
- Designed **multi-tenant SaaS** data architecture for 3 business units with tenant-level RBAC, schema isolation, and SOC 2/HIPAA-aligned controls.[file:1]  
- Built **200+ dbt models** (Core & Cloud) with incremental materializations and tests, cutting warehouse compute costs by **35%**.[file:1]  
- Implemented end-to-end observability using **Monte Carlo + Great Expectations + Slack/PagerDuty**, reducing data incidents by **60%**.[file:1]

**Result:** Reliable, compliant analytics platform powering regulatory, investor, and executive reporting with significantly lower compute spend.

---

### 2️⃣ Real-Time Loan Risk & Collections Pipeline – Kafka + Databricks + Delta Lake

**Context:** Fintech lender needed near real-time visibility into loan performance, delinquencies, and risk scores.

- Designed a **real-time stock/loan streaming pipeline** with Kafka → Databricks → Delta Lake (bronze/silver/gold) → dbt models → Power BI dashboards.  
- Built PySpark jobs to cleanse, join, and aggregate streaming events into **gold tables** for delinquency, prepayment, and cohort analysis.  
- Implemented data-quality checks on streaming tables (nulls, thresholds, schema drift) and alerts to Slack for anomalies.  
- Delivered Power BI dashboards for risk and collections teams with sub-minute latency views.

**Result:** Enabled faster decision-making on high-risk accounts and improved visibility into loan portfolio performance.

> Example repo: [Real-Time Stock Streaming Pipeline](https://github.com/Ashok98765vvs/end-to-end-lakehouse-pipeline)

---

## 🚀 Featured Projects

### 🔷 1. dbt + Snowflake End-to-End Pipeline

Public API → Python ingestion → Snowflake → dbt incremental models → data quality tests → GitHub Actions CI/CD

- Designed incremental dbt models and tests for core fact/dim tables, achieving ~**40% faster** runs and reduced compute.  
- Automated a **6-hour** manual reporting workflow into a **5-minute** scheduled pipeline.  
- Maintained **100% data-quality test** pass rate (unique, not null, referential integrity).

[Repo](https://github.com/Ashok98765vvs/dbt-snowflake-pipeline)

---

### 🔷 2. Airflow ETL → BigQuery (GCP)

REST API → Airflow DAG → GCS → BigQuery → dbt → Great Expectations gate

- Orchestrated daily ingest of **1M+ rows** using Airflow, GCS staging, and partitioned BigQuery tables.  
- Implemented retries and email alerting to avoid silent failures in scheduled ETL.  
- Added Great Expectations checks on BigQuery tables before downstream models.

[Repo](https://github.com/Ashok98765vvs/airflow-etl-bigquery)

---

### 🔷 3. Redshift → Snowflake Migration (Zero Downtime)

- Authored migration playbook: schema export, S3 staging, COPY INTO patterns, and data validation.  
- Achieved **4.7x faster** query performance and ~**65% lower** storage cost post-migration.  
- Implemented row-count + MD5 checksum validation scripts for table-level integrity.

[Repo](https://github.com/Ashok98765vvs/redshift-to-snowflake-migration)

---

### 🔷 4. Snowflake Data Infra — Terraform + GitHub Actions

- Codified Snowflake warehouses, RBAC roles, databases, and schemas using **Terraform**.  
- Wired CI/CD so every PR runs `terraform plan` and merges trigger `terraform apply`.  
- Provisioned **8+ warehouses** and full RBAC hierarchy in under 5 minutes with zero manual configuration.

[Repo](https://github.com/Ashok98765vvs/data-infra-terraform)

---

## 🔶 More Projects

| Project                           | Stack                                        | Outcome                                      |
|-----------------------------------|----------------------------------------------|----------------------------------------------|
| Real-Time Stock Streaming Pipeline| Kafka · Databricks · Delta Lake · dbt · Power BI | Real-time stock analytics lakehouse on Azure |
| Azure Real-Time Data Quality      | PySpark · Delta Lake · Azure Synapse · ADF   | Streaming data-quality checks on bronze/silver tables |
| Auto Apply Engine                 | Python · AI · Automation                     | Automates job applications based on filters  |
| AI Job Search Engine              | Python · ML · NLP                            | Ranks job postings based on candidate fit    |

---

## 📊 GitHub Activity

I actively commit to:

- **fintech-realtime-loan-pipeline**  
- **dbt-snowflake-pipeline**  
- **airflow-etl-bigquery**  
- **python-mortgage-data-pipelines**  
- **data-infra-terraform**

I use GitHub to mirror real project patterns from my professional work: incremental dbt models, observability, CI/CD, and IaC.

---

## 📬 Let's Connect

💼 Open to **Data Engineer / Analytics Engineer / Data Platform Engineer** roles (full-time or contract) in the US — **available immediately, no sponsorship needed**.

If you find my projects useful, please ⭐ them — it helps recruiters and hiring managers discover my work.
