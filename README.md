# 🏗️ Data Warehouse & ETL Project
### Building an End-to-End Data Warehouse Using Medallion Architecture

<p align="center">
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
  <img src="https://img.shields.io/badge/T--SQL-4479A1?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
  <img src="https://img.shields.io/badge/Data_Warehouse-Medallion_Architecture-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Version_Control-GitHub-181717?style=for-the-badge&logo=github" />
</p>

## 📖 Project Overview

This project focuses on designing and developing a Data Warehouse using **Medallion Architecture** and SQL-based ETL processes.

The project follows a layered approach to ingest, transform, clean, and organize data into structured datasets for business intelligence and analytical purposes.

The architecture consists of three layers:

- 🥉 **Bronze Layer:** Stores raw data from source systems.
- 🥈 **Silver Layer:** Cleans, validates, and standardizes the ingested data.
- 🥇 **Gold Layer:** Organizes transformed data into business-ready structures for reporting and analysis.

---

## 1. 🧩 Components

The project consists of the following components:

### 🗄️ Data Sources
- Source datasets containing business information.
- Raw data ingestion into the data warehouse.
- Source data preservation for downstream processing.

### 🥉 Bronze Layer – Raw Data
- Loads raw data from source files.
- Stores data in its original structure.
- Maintains a foundation for further transformations.

### 🥈 Silver Layer – Cleansed Data
- Handles duplicate records.
- Standardizes inconsistent values.
- Handles NULL and missing values.
- Performs data type validation and conversion.
- Applies data quality checks.

### 🥇 Gold Layer – Business-Ready Data
- Organizes transformed data.
- Supports analytical data modeling.
- Structures business information for reporting.
- Provides data for downstream analytical consumption.

### 📚 Documentation & SQL Scripts
- SQL scripts for database development and ETL processing.
- Project documentation and supporting resources.
- Organized datasets and project files.

---

## 2. 🎯 Problem Statement

Organizations often maintain business data across multiple sources and systems.

However, raw data may contain several issues:

- Inconsistent data formats.
- Duplicate records.
- Missing and NULL values.
- Data quality and validation issues.
- Difficulty integrating information from multiple sources.
- Lack of structured and reliable data for analytical reporting.

These challenges make it difficult for businesses to generate accurate insights and make informed decisions.

**The objective of this project is to develop a centralized Data Warehouse that processes raw data through structured ETL pipelines and transforms it into clean, consistent, and analysis-ready information.**

---

## 3. 💡 Solution

To address these challenges, this project implements **Medallion Architecture**, dividing the data processing workflow into three progressive layers.

### 🔄 ETL Architecture

```text
       📂 SOURCE DATA
              |
              ▼
       🥉 BRONZE LAYER
         Raw Data
              |
              ▼
       🥈 SILVER LAYER
   Cleansing & Transformation
              |
              ▼
        🥇 GOLD LAYER
    Business-Ready Data
              |
              ▼
       📊 ANALYTICS &
         REPORTING
```

### 🥉 Bronze Layer – Data Ingestion

The Bronze layer acts as the initial landing zone for source data.

**Key activities:**
- Extract data from source datasets.
- Load raw records into Bronze tables.
- Preserve source information.
- Maintain raw data for downstream processing.

### 🥈 Silver Layer – Data Transformation

The Silver layer focuses on improving data quality and consistency.

**Key activities:**
- Remove or handle duplicate records based on business rules.
- Standardize text values.
- Handle NULL values.
- Validate and convert data types.
- Apply data cleansing and transformation logic.

### 🥇 Gold Layer – Data Modeling

The Gold layer prepares the transformed data for business consumption.

**Key activities:**
- Organize data into analytical structures.
- Develop fact and dimension tables where applicable.
- Establish relationships between business entities.
- Prepare structured data for reporting and analysis.

---

## 4. 📁 Folder Structure

The repository follows this structure:

```text
datawarehouse_ETL_Project/
│
├── 📂 datasets/
│   └── Source datasets
│
├── 📂 docs/
│   └── Project documentation
│
├── 📂 scripts/
│   └── SQL scripts
│
├── 📄 LICENSE
│
└── 📄 README.md
```

### 📌 Folder Description

| Folder / File | Description |
|---|---|
| 📂 datasets | Contains source datasets used in the project. |
| 📂 docs | Stores project documentation and supporting resources. |
| 📂 scripts | Contains SQL scripts used for database development and ETL processing. |
| 📄 LICENSE | Contains project licensing information. |
| 📄 README.md | Provides project overview and technical documentation. |

---

## 5. 🏆 Project Outcomes

This project demonstrates practical understanding of the following concepts:

- ✅ Data Warehouse architecture and design.
- ✅ Medallion Architecture implementation.
- ✅ End-to-end ETL workflow.
- ✅ Raw data ingestion and management.
- ✅ SQL-based data cleaning and transformation.
- ✅ Data quality checks and validation.
- ✅ Understanding of fact and dimension modeling.
- ✅ Organizing data into analytical layers.
- ✅ Structured SQL development.
- ✅ GitHub repository management and documentation.

### 🚀 Key Takeaway

The project demonstrates how raw source data can be transformed into reliable, structured, and business-ready information using a layered Data Warehouse architecture.

It provides practical exposure to the fundamental concepts involved in building and maintaining an ETL-based Data Warehouse.

---

## 👩‍💻 Author

**Farhin Afroz**

🔗 **GitHub:** [farhin1999-design](https://github.com/farhin1999-design)

📂 **Project Repository:** [Data Warehouse ETL Project](https://github.com/farhin1999-design/datawarehouse_ETL_Project)

---

⭐ If you find this project useful, feel free to explore the repository!