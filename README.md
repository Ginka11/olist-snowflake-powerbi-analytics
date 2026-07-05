# 🛒 Olist E-Commerce Analytics with Snowflake & Power BI

## 📖 Project Overview

This project demonstrates an end-to-end data analytics workflow using the **Olist Brazilian E-Commerce Dataset** from Kaggle.

The data was extracted from a SQLite database, transformed into CSV files using Python, loaded into Snowflake for cloud-based storage and SQL analysis, and visualized through interactive dashboards built in Power BI. The final report was published to Power BI Service.

---

## 🛠️ Tech Stack

- Python
- SQLite
- Snowflake
- SQL
- Power BI Desktop
- Power BI Service
- Git & GitHub

---

## 📂 Dataset

**Source:** Kaggle

The dataset contains information about:

- Customers
- Orders
- Order Items
- Products
- Sellers
- Payments
- Reviews
- Geolocation

---

## 🔄 Project Workflow

### 1. Data Preparation
- Downloaded the Olist dataset from Kaggle.
- Extracted all tables from the SQLite database using Python.
- Converted each table into CSV format.

### 2. Data Processing
- Split the large geolocation dataset into multiple CSV files using Python.
- Prepared the data for efficient loading into Snowflake.

### 3. Snowflake
- Created the database and tables.
- Loaded all CSV files into Snowflake.
- Validated imported data.

### 4. SQL Analysis
Performed data cleaning and business analysis using SQL, including:

- Joins
- Aggregate Functions
- GROUP BY & HAVING
- CASE
- COALESCE
- CTEs
- Subqueries
- Window Functions
- Views

### 5. Power BI
Built an interactive dashboard featuring:

- KPI Cards
- Monthly Revenue Trend
- Revenue by State
- Top Product Categories
- Review Analysis
- Interactive Map
- Navigation Buttons
- Mobile Layout

### 6. Power BI Service
- Published the report to Power BI Service.
- Configured the Snowflake data source connection.

---

## 📊 Dashboard Features

- Interactive filtering
- Business KPIs
- Revenue trend analysis
- Geographic analysis
- Product category insights
- Review score analysis
- Mobile-optimized dashboard

---

## 📷 Project Screenshots

### Dashboard
*(Add dashboard screenshot)*

### Snowflake
*(Add Snowflake worksheet screenshot)*

### SHOW TABLES
*(Add SHOW TABLES screenshot)*

### Power BI Data Source
*(Add Snowflake connection screenshot)*

### Mobile Layout
*(Add mobile layout screenshot)*

---

## 📁 Project Structure

```
Olist-Snowflake-PowerBI
│
├── Python
│   ├── sqlite_to_csv.py
│   └── split_geolocation.py
│
├── SQL
│   ├── data_cleaning.sql
│   ├── analysis.sql
│   └── views.sql
│
├── Dashboard
│   └── SnowflakeProject.pbix
│
├── Images
│
└── README.md
```

---

## 💼 Skills Demonstrated

- Data Cleaning
- Data Transformation
- SQL Analytics
- Cloud Data Warehousing
- Snowflake
- Python Automation
- Data Visualization
- Business Intelligence
- Power BI Dashboard Development
- Power BI Service Deployment

---

**Technologies:** SQL • Snowflake • Python • Power BI • Power BI Service
