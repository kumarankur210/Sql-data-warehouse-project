# SQL Data Warehouse & Analytics Project

Welcome to my **SQL Data Warehouse & Analytics Project**.

This project is focused on building a practical data warehouse using **SQL Server**, starting from raw business data and transforming it into clean, analysis-ready information.

The project covers the complete flow from **data ingestion and transformation to data modeling and analytical reporting**.

---

## 📌 Project Overview

The goal of this project is to design a simple and scalable data warehouse that combines data from different business systems and prepares it for analysis.

The project demonstrates:

- Data ingestion from source files
- Data cleaning and transformation
- Data warehouse development
- Data modeling
- SQL-based data analysis
- Business-oriented reporting

---

## 🏗️ Data Architecture

The project follows a **Medallion Architecture** consisting of three main layers:

### 🥉 Bronze Layer
The Bronze layer stores the data in its original/raw form.

- Data is loaded from source files
- Minimal or no transformation is performed
- Used as the initial landing area
- Maintains the original structure of the source data

### 🥈 Silver Layer
The Silver layer contains cleaned and standardized data.

Typical transformations include:

- Removing duplicate records
- Handling missing values
- Standardizing formats
- Data type corrections
- Creating derived columns
- Data validation and cleansing

### 🥇 Gold Layer
The Gold layer contains business-ready data designed for analysis.

This layer includes:

- Business logic
- Aggregations
- Analytical views
- Fact and dimension structures
- Star-schema based models where required

---

## 📂 Data Sources

The project uses data from two business systems:

- **CRM** – Customer-related information
- **ERP** – Business and operational information

The source data is provided in **CSV format**.

---

## 🛠️ Technologies Used

- **SQL Server** – Data warehouse and SQL development
- **SQL** – Data transformation and analysis
- **Git & GitHub** – Version control and project documentation
- **Power BI** – Data visualization and reporting

---

## 🔄 ETL Process

The overall data flow is:

```text
Source Systems
     ↓
CSV Files
     ↓
Bronze Layer
     ↓
Silver Layer
     ↓
Gold Layer
     ↓
Analytics & Reporting
