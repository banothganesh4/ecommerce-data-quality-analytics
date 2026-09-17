# ecommerce-data-quality-analytics
End-to-end e-commerce data quality and customer analytics project using MySQL, Python, and Power BI.
# E-commerce Data Quality & Customer Analytics

## Project Overview

This project focuses on analyzing e-commerce transaction data and improving data reliability through SQL, Python, and Power BI.

The project follows an end-to-end analytics workflow:

**Data storage → Data cleaning → Data validation → SQL analysis → Power BI dashboard → Business insights**

## Business Problem

E-commerce datasets may contain missing customer information, incomplete product descriptions, invalid quantities, incorrect prices, and cancelled transactions.

The objective of this project is to identify these issues, validate the data, and create meaningful customer and revenue insights for business decision-making.

## Project Objectives

* Identify missing and invalid data.
* Validate customer, invoice, quantity, and price fields.
* Analyze customer purchasing behavior.
* Calculate revenue and customer performance.
* Identify top customers and customer distribution by country.
* Build an interactive Power BI dashboard.
* Present data-quality issues using clear KPIs and visualizations.

## Tools & Technologies

* **MySQL:** Database creation, SQL queries, and data-quality checks
* **Python:** Data cleaning, validation, and exploratory analysis
* **Power BI:** Data modeling, DAX measures, KPIs, and interactive dashboards
* **Excel/CSV:** Initial data source and data preparation

## Project Workflow

### 1. Data Preparation

The raw e-commerce transaction dataset was loaded into MySQL and Python for inspection and preparation.

### 2. Data Quality Checks

The project checks for:

* Missing Customer IDs
* Missing product descriptions
* Invalid or negative quantities
* Invalid unit prices
* Cancelled invoices
* Duplicate or inconsistent records

### 3. SQL Analysis

SQL was used to:

* Explore transaction records
* Calculate revenue
* Identify missing values
* Analyze customers and invoices
* Summarize data-quality issues

### 4. Python Analysis

Python was used for:

* Data inspection
* Missing-value analysis
* Data validation
* Data cleaning
* Exploratory data analysis

### 5. Power BI Dashboard

The Power BI report contains customer analytics and data-quality monitoring.

The dashboard includes:

* Total revenue
* Total customers
* Average revenue per customer
* Top customers by revenue
* Customers by country
* Data-quality issue breakdown
* Data-quality percentages
* Data-quality summary indicators

## Data Quality Summary

The data-quality analysis includes checks for missing, invalid, and inconsistent records.

> Note: Some quality checks may overlap because one transaction can have more than one issue. Therefore, issue counts should not automatically be added together as unique problematic records.

## Key Skills Demonstrated

* SQL querying
* Data cleaning
* Data validation
* Exploratory data analysis
* Data modeling
* Power Query
* DAX
* KPI development
* Dashboard design
* Business intelligence
* Customer analytics
* Data-quality monitoring

## Repository Structure

ecommerce-data-quality-analytics/
│
├── PowerBI/
│   └── Ecommerce_Data_Quality_Project.pbix
│
├── SQL/
│   └── data_quality_project.sql
│
├── Python/
│   └── data_cleaning_validation.ipynb
│
├── Dashboard/
│   └── Ecommerce_Data_Quality_Dashboard.pdf
│
├── Images/
│   ├── dashboard_overview.png
│   ├── customer_intelligence.png
│   ├── python_data_cleaning.png
│   └── sql_analysis.png
│
└── README.md
## Dashboard Preview

### Power BI Dashboard Overview

![Dashboard Overview](Images/dashboard_overview.png)

### Customer Intelligence & Data Quality

![Customer Intelligence](Images/customer_intelligence.png)

### Python Data Cleaning

![Python Data Cleaning](Images/python_data_cleaning.png)

### SQL Analysis

![SQL Analysis](Images/sql_analysis.png)

## Author

**Banoth Ganesh**

MSc Data Analytics for Business
KEDGE Business School, France

Skills: SQL | Python | Power BI | Data Analytics | Business Intelligence
