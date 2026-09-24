# Data Warehouse & Analytics Project

This repository contains a hands-on implementation of an end-to-end **Data Warehouse and Analytics solution using SQL Server**.
The solution demonstrates how data from operational **ERP and CRM systems** can be ingested, transformed, integrated, modelled and prepared for analytical use.
The implementation follows a **Medallion Architecture**, separating raw source data from transformed data and business-ready analytical data.

## Data Architecture
🥉 Bronze Layer — Raw
Source data ingestion
Source-aligned tables
Raw data preservation

🥈 Silver Layer — Transformed
Data cleansing
Standardisation
Transformation
Data integration
Data quality

🥇 Gold Layer — Business Ready
Dimensional modelling
Fact and dimension tables
Star schema
Analytical datasets

---

### Technical Scope
SQL
T-SQL
Joins
Aggregations
CTEs
Subqueries
Window functions
CASE
Date functions
NULL handling
Data validation
Data Engineering
ETL / ELT
Data ingestion
Data transformation
Data integration
Data quality
Medallion Architecture
Data Modelling
Fact & dimension tables
Star schema
Table grain
Primary & foreign keys
Analytical data structures

---

#### Business Scenario

Operational data from ERP and CRM systems is integrated into a central warehouse to support:

Customer analysis
Product performance
Sales analysis
Trend analysis
Business reporting

---

##### Data Quality

Validation includes:
Duplicates
Missing and invalid values
Data types
Referential integrity
Row counts
Join behaviour
Source-to-target reconciliation
Table grain

---

###### Repository Structure

sql_datawarehouse_project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project

---

###### Technologies
SQL Server
SSMS
T-SQL
GitHub
Draw.io
CSV
Medallion Architecture
Dimensional Modelling

---

###### About Me 

I am an IT professional with experience across major incident management, change governance, service resilience, reporting and data-focused initiatives.
