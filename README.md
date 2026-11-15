# 🏗️ Data Warehouse ETL Project | Medallion Architecture

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![T-SQL](https://img.shields.io/badge/T--SQL-4479A1?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-Medallion-gold?style=for-the-badge)

## 📌 Project Overview

This project demonstrates the development of a Data Warehouse using **Medallion Architecture** and an ETL (Extract, Transform, Load) approach.

The objective is to build a structured data pipeline that organizes raw data, applies data cleaning and transformation processes, and prepares business-ready data for analytical purposes.

The project follows three architectural layers:

- 🥉 **Bronze Layer:** Stores raw data from source systems.
- 🥈 **Silver Layer:** Cleans, validates, and standardizes data.
- 🥇 **Gold Layer:** Organizes transformed data into business-ready structures for reporting and analysis.

---

## 1. 🧩 Components

The project consists of the following major components:

### 🗄️ Data Sources
- Source datasets containing business information.
- Raw data ingestion into the data warehouse.
- Preservation of source data for further processing.

### 🥉 Bronze Layer – Raw Data
- Loads data from source files into the warehouse.
- Maintains raw data with minimal transformations.
- Acts as the initial storage layer of the ETL pipeline.

### 🥈 Silver Layer – Data Transformation
- Removes duplicate records.
- Handles NULL and missing values.
- Standardizes inconsistent data.
- Performs data type conversions.
- Applies data validation and business rules.

### 🥇 Gold Layer – Business-Ready Data
- Organizes cleaned data for analytical consumption.
- Structures data into dimensions and facts where applicable.
- Supports business reporting and analytical queries.

### 📚 Documentation
- Stores project-related documentation.
- Organizes supporting project resources and technical references.

---

## 2. 🎯 Problem Statement

Organizations often maintain business data across multiple source systems and files.

This creates several challenges:

- Inconsistent data formats across different sources.
- Duplicate and missing records.
- Data quality and validation issues.
- Difficulty integrating information from multiple sources.
- Limited availability of structured data for business reporting.

Without a properly designed data warehouse, analyzing business information becomes difficult and time-consuming.

**The goal of this project is to develop a centralized data warehouse that transforms raw source data into clean, structured, and reliable information using an organized ETL pipeline.**

---

## 3. 💡 Solution

The project implements a Medallion Architecture to process data through three progressive layers.

### 🔄 ETL Workflow

**Extract → Transform → Load → Analyze**

| Layer | Process | Objective |
|---|---|---|
| 🥉 Bronze | Data ingestion | Store raw source data |
| 🥈 Silver | Data cleaning and transformation | Improve data quality and consistency |
| 🥇 Gold | Data modeling and organization | Prepare business-ready data |

### 🥉 Bronze Layer

The Bronze layer acts as the landing zone for incoming data.

Key activities:
- Extract data from source datasets.
- Load raw records into Bronze tables.
- Preserve original source information.
- Maintain a foundation for downstream transformations.

### 🥈 Silver Layer

The Silver layer focuses on improving data quality.

Key activities:
- Identify and handle duplicate records.
- Standardize text values.
- Validate and convert data types.
- Handle NULL values.
- Apply transformation and validation rules.

### 🥇 Gold Layer

The Gold layer provides structured data for business consumption.

Key activities:
- Create analytical data structures.
- Organize data into fact and dimension tables where applicable.
- Establish relationships between business entities.
- Prepare data for reporting and analysis.

---

## 4. 📁 Folder Structure

The repository is organized into the following main directories:

```text
datawarehouse_ETL_Project/
│
├── 📂 datasets/
│   └── Source datasets used in the project
│
├── 📂 docs/
│   └── Project documentation and supporting resources
│
├── 📂 scripts/
│   └── SQL scripts for database development
│
├── 📄 LICENSE
│
└── 📄 README.md
```

### Folder Description

| Folder/File | Purpose |
|---|---|
| `datasets/` | Contains source data used for ETL processing. |
| `docs/` | Contains project documentation and supporting resources. |
| `scripts/` | Contains SQL scripts for database creation, data loading, and transformations. |
| `LICENSE` | Defines the project's licensing terms. |
| `README.md` | Provides project documentation and an overview. |

---

## 5. 🏆 Project Outcomes

Through this project, the following practical concepts and skills are demonstrated:

- Understanding of Data Warehouse architecture.
- Implementation of Medallion Architecture.
- Understanding of end-to-end ETL workflows.
- Data ingestion and raw data management.
- SQL-based data cleaning and transformation.
- Data validation and quality management.
- Understanding of fact and dimension modeling.
- Organizing data for analytical consumption.
- Maintaining structured and reusable SQL scripts.
- Using GitHub for project version control and documentation.

### 🚀 Key Takeaway

This project demonstrates how raw business data can be transformed into structured, reliable, and analysis-ready information through a layered Data Warehouse architecture.

---

## 👩‍💻 Author

**Farhin Afroz**

GitHub: [@farhin1999-design](https://github.com/farhin1999-design)

**Project Repository:** [Data Warehouse ETL Project](https://github.com/farhin1999-design/datawarehouse_ETL_Project)

---

⭐ If you find this project useful, feel free to explore the repository and its implementation.