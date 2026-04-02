# 🚀 End-to-End Data Warehouse & Analytics Project (SQL | Medallion Architecture)

## 📌 Project Summary

Built an end-to-end **Data Warehouse solution using SQL** based on the **Medallion Architecture (Bronze → Silver → Gold)**.

This project demonstrates how raw data is transformed into **clean, structured, and analytics-ready datasets** to generate meaningful business insights.

---

## 🏗️ Architecture Overview

### 🔷 Medallion Architecture (Bronze → Silver → Gold)

![Architecture Diagram](docs/architecture.png)

### ⭐ Data Model (Gold Layer - Star Schema)

![Data Model](docs/data_model.png)

---

## 🧱 Data Warehouse Layers

### 🥉 Bronze Layer (Raw Data)

* Stores raw data from source systems
* No transformations applied
* Supports auditing and debugging

### 🥈 Silver Layer (Cleaned Data)

* Removes duplicates and null values
* Standardizes formats and column names
* Applies basic business rules

### 🥇 Gold Layer (Business-Ready Data)

* Contains fact and dimension tables
* Uses Star Schema for analytics
* Optimized for reporting (Power BI / Tableau)

---

## ⭐ Data Model (Gold Layer)

Implemented a **Star Schema**:

* **dim_customer** → Customer details
* **dim_product** → Product information
* **fact_sales** → Sales transactions

👉 Designed for fast querying and reporting.

---

## 🔄 ETL Process (End-to-End)

### Step 1: Load Bronze

* Extract data from source systems
* Load into raw tables without modification

### Step 2: Transform to Silver

* Clean and validate data
* Remove duplicates
* Convert data types

### Step 3: Build Gold Layer

* Create fact and dimension tables
* Generate KPIs
* Prepare data for dashboards

---

## 📊 Business KPIs

* Total Sales
* Total Revenue
* Average Order Value
* Sales by Category
* Customer Retention
* Monthly Growth %

---

## 📈 Business Impact

* Improved data quality through cleaning and validation
* Enabled faster reporting using optimized schema
* Provided insights into customer behavior and sales trends
* Built scalable data pipeline for future use

---

## 🛠️ Tech Stack

* SQL (ETL & Data Transformation)
* SQL Server / MySQL
* Data Modeling (Star Schema)
* Power BI (for dashboards)

---

## 📂 Project Structure

sql-datawarehouse/
├── 01_bronze/
├── 02_silver/
├── 03_gold/
├── docs/
│   ├── architecture.png
│   ├── data_model.png
└── README.md

---

## 📊 Sample Output

* Interactive dashboards (Power BI)
* KPI reports
* Aggregated datasets for analytics

---

## 💡 Why This Project?

This project demonstrates my ability to:

* Build end-to-end data pipelines
* Design scalable data warehouse architecture
* Perform data cleaning and transformation
* Generate business insights from raw data

---

## 🚀 Future Enhancements

* Add incremental loading (CDC)
* Automate ETL using stored procedures
* Schedule pipelines using Airflow / SQL Agent
* Add Power BI dashboard link

---

## 👨‍💻 Author

**Rushi Nandan Reddy**
🔗 LinkedIn: https://linkedin.com/in/your-profile
📧 Email: [yourmail@gmail.com](mailto:yourmail@gmail.com)

---

✨ *Turning raw data into actionable insights.*

