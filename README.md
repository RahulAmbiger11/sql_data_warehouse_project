# 📊 Data Warehouse and Analytics Project

A complete, end-to-end data warehousing and analytics solution designed to consolidate disparate business data, build clean data pipelines, and deliver actionable reporting. This portfolio project showcases practical data engineering and analytics workflows using industry-standard practices.

## 📐 Data Architecture

The project processes data through three distinct architectural layers to ensure quality and performance:

<img width="1263" height="748" alt="Project Arechitecture (Mendallion_" src="https://github.com/user-attachments/assets/1419735f-a7e4-4039-99a3-96597d3d016b" />


1. **🟫 Bronze Layer (Raw):** Ingests raw CSV source files directly into SQL Server without modifications.
2. **⬜ Silver Layer (Cleaned):** Handles data cleansing, deduplication, formatting, and structural normalization.
3. **🟨 Gold Layer (Analytical):** Houses business-ready data modeled into a Star Schema optimized for BI tools and reporting.

---

## 🔍 Project Overview

This project focuses on transforming raw transactional data into a business-ready analytical platform. The workflow covers:

* **Data Architecture:** Structuring data using a multi-layer Medallion Architecture.
* **ETL Pipelines:** Extracting raw files, cleaning anomalies, and loading structured tables.
* **Data Modeling:** Developing a relational Star Schema with optimized facts and dimensions.
* **Analytics & Reporting:** Writing analytical SQL queries to extract business metrics and trends.

🎯 This repository is an excellent resource for professionals to have knowledge and expertise in:

- SQL Development
- Data Architect
- Data Engineering  
- ETL Pipeline Developer  
- Data Modeling  
- Data Analytics

## 🛠️ Important Links & Tools:

- **[Datasets](https://github.com/RahulAmbiger11/sql_data_warehouse_project/tree/main/datasets):** Access to the project dataset (csv files).

- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight server for hosting your SQL database.

- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16):** GUI for managing and interacting with databases.

- **[Git Repository](https://github.com/):** Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.

- **[DrawIO](https://www.drawio.com/):** Design data architecture, models, flows, and diagrams.

- **[Notion](https://www.notion.com/):** For Project Planning and Execution

- **[Notion Project Steps](https://www.notion.so/SQL-Data-Warehouse-Project-3596f8ee57588068ba90da2ba56fbbc5?source=copy_link):** Access to All Project Phases and Tasks.

---


## 🚀 Project Requirements & Scope

### 🛠️ Data Engineering (Building the Warehouse)
* **Data Sources:** Consolidate data from two separate business systems (ERP and CRM) provided via CSV files.
* **Data Quality:** Clear out formatting errors, handle missing values, and standardize keys.
* **Integration:** Merge the cleaned datasets into a unified, query-ready data model.
* **Strategy:** Focus entirely on the latest state of data (historization/SCD is out of scope).

### 📈 Data Analysis (BI & Reporting)
* **Objective:** Write optimized SQL queries to analyze key business domains:
  * **Customer Behavior:** Order frequencies, spending habits, and segmentation.
  * **Product Performance:** Top-selling items, category revenue, and inventory trends.
  * **Sales Trends:** Revenue growth patterns across days, months, and quarters.

---

## 📂 Repository Structure

```text
data_warehouse_project/
│
├── datasets/               # Raw ERP and CRM source files (CSV format)
│
├── docs/                   # Architecture plans and documentation
│   ├── etl.drawio          # ETL methodology and processing logic
│   ├── data_architecture   # Visual overview of data layers
│   ├── data_catalog.md     # Field descriptions, data types, and metadata
│   ├── data_flow.drawio    # Lineage mapping from source to destination
│   ├── data_models.drawio  # Star Schema entity-relationship diagram (ERD)
│   └── naming-conventions  # Standardization rules for columns and tables
│
├── scripts/                # Organized SQL scripts
│   ├── bronze/             # Truncate and load raw source data
│   ├── silver/             # Cleansing, cast data types, and transformation
│   └── gold/               # Dimension and fact table views
│
├── tests/                  # Data quality and testing validation scripts
│
├── README.md               # Project documentation
└── .gitignore              # Files excluded from version control
```

---

## 🌟 About Me

Hi there! I'm **Rahul Ambiger**, an IT professional and Data Engineer. I focus on building clean, efficient data solutions and sharing practical data engineering insights.

Feel free to connect with me:

<p id="badges">
  <a href="https://www.linkedin.com/in/rahul-ambiger/" target="_blank">
    <img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</p>


