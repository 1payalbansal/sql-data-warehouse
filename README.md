# Data Warehouse and Analytics Project

This project is a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. 

---
## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:

```
┌──────────┐     ┌──────────────┐     ┌──────────────┐     ┌──────────────┐     ┌─────────────────┐
│  Sources │───▶│    BRONZE    │────▶│    SILVER    │───▶│     GOLD     │─ ──▶│    Consumers    │
│ CRM / ERP│     │   Raw Data   │     │ Clean & Std  │     │Business-Ready│     │ BI / Analytics  │
└──────────┘     └──────────────┘     └──────────────┘     └──────────────┘     └─────────────────┘
```
---
## Visual_architeture

<img width="1278" height="718" alt="image" src="https://github.com/user-attachments/assets/20c44f82-381d-4d47-acb1-822e5b4e3675" />


The data warehouse is structured as a **SQL Server** database with three schema layers, each serving a distinct purpose in the data pipeline.

---
## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights. 

### Building the Data Warehouse

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

### BI: Analytics & Reporting 

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.  

