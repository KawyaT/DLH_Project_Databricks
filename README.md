# Hybrid Data Lakehouse Architecture for Enterprise Analytics
### Using Databricks | Delta Lake | Apache Spark | Unity Catalog

## Project Overview
This project implements a Hybrid Data Lakehouse Architecture simulating
a real-world enterprise banking environment processing 100TB of data.

## Architecture
- **Bronze Layer** — Raw ingestion from 5 banking data sources
- **Silver Layer** — Cleansed data with PII masking and validation
- **Gold Layer**   — Business KPIs (transactions, fraud, revenue, customers)

## Tech Stack
| Component      | Technology                    |
|---------------|-------------------------------|
| Platform       | Databricks Free Edition       |
| Storage        | Delta Lake (Unity Catalog)    |
| Processing     | Apache Spark (PySpark)        |
| Governance     | Unity Catalog RBAC + Masking  |
| Dashboard      | Databricks SQL + Power BI     |
| Data Volume    | 28,000 synthetic rows (demo)  |

## Data Sources
1. Banking Transactions (10,000 rows)
2. Customer Information (2,000 rows) — PII masked
3. ATM Logs (5,000 rows)
4. Mobile Banking Logs (8,000 rows)
5. CRM Data (3,000 rows)

## Key KPIs
- Daily Transaction Volume & Success Rate
- Fraud Detection Rate by Channel
- Customer Growth by Segment
- Monthly Revenue Analysis

## How to Run
1. Sign up at community.cloud.databricks.com
2. Run notebooks in order: 01 → 02 → 03 → 04 → 05
3. Open Databricks SQL to view Gold dashboards

## Author
Data Science Undergraduate Final Year Project
