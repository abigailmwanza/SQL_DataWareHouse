# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀 

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as best practices in data engineering and analytics.

---
## 🏗️ Data Architecture

![](https://github.com/abigailmwanza/SQL_DataWareHouse/blob/main/Docs/warehouse%20Arch.JPG)

Built on a Medallion Architecture with Bronze, Silver, and Gold layers:

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

# Overview

## Core components:
**ETL Pipeline:** Orchestrates data extraction, transformation, and loading from source systems.
**Data Modeling:** Constructs fact and dimension tables for efficient querying.
**Analytics:** Generates SQL-based insights for customer behavior, product performance, and sales trends.

Showcases expertise in:
1. SQL Development
2. Data Engineering
3. ETL Orchestration
4. Dimensional Modeling
5. Analytical Querying



🚀 Requirements

## Data Engineering
- Goal: Deploy a robust ETL pipeline on SQL Server for sales data integration and analytics.
- Sources: CSV datasets from ERP and CRM systems.
- Data Quality: Implements cleansing and validation processes.
- Integration: Merges sources into a unified star schema model.
- Scope: Processes latest dataset; no historization required.
- Docs: Provides comprehensive data model documentation.

## Analytics
Goal: Deliver SQL-driven insights on customer behavior, product metrics, and sales trends.




📂 Repository Structure

                  data-pipeline/
                  │
                  ├── datasets/                           # Raw ERP/CRM CSV datasets
                  ├── docs/                               # Documentation
                  │   ├── data_architecture.drawio        # Medallion Architecture diagram
                  │   ├── data_catalog.md                 # Dataset schema and metadata
                  │   ├── data_flow.drawio                # ETL pipeline flow
                  │   ├── data_models.drawio              # Star schema models
                  │   ├── naming-conventions.md           # Table/column naming standards
                  ├── scripts/                            # SQL scripts
                  │   ├── bronze/                         # Raw data ingestion scripts
                  │   ├── silver/                         # Data transformation scripts
                  │   ├── gold/                           # Analytical model scripts
                  ├── tests/                              # Data quality and validation scripts
                  ├── README.md                           # Project overview
                  ├── LICENSE                             # MIT License
                  ├── .gitignore                          # Git ignore configuration
                  └── requirements.txt                    # Project dependencies


🛡️ License

Licensed under the MIT License.



