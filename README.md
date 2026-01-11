# 📊 AdventureWorks Sales Analytics Dashboard

## 📌 Project Overview

This Power BI project delivers a comprehensive business intelligence solution for AdventureWorks, a global manufacturing company specializing in cycling equipment and accessories. The dashboard enables management to track key performance indicators, compare regional performance, analyze product trends, and identify high-value customers.

---

## 🎯 Business Objectives

The management team required a robust analytics platform to:

* Track critical KPIs such as **sales, revenue, profit, and returns**
* Compare performance across different regions
* Analyze product-level trends and category performance
* Identify and segment high-value customers
* Monitor monthly trends and forecast future performance

---

## 📂 Dataset Description

The project utilizes multiple CSV files containing:
* AdventureWorks Calendar Lookup
* AdventureWorks Customer Lookup
* AdventureWorks Product Categories Lookup
* AdventureWorks Product Lookup
* AdventureWorks Product Subcategories Lookup
* AdventureWorks Returns Data
* AdventureWorks Sales Data 2020
* AdventureWorks Sales Data 2021
* AdventureWorks Sales Data 2022
* AdventureWorks Territory Lookup
(All these files are in Data folder)

---

## 🛠️ Tools & Technologies Used

* **Power BI Desktop:** Primary development platform
* **Power Query:** Data transformation and ETL
* **DAX:** Calculations and measures
* **Data Modeling:** Established a snowflake schema to connect disparate data sources.
* **Excel/CSV:** Source data format

---

## 📊 Data Preparation & Modeling

### 1. Data Connection

* Connected to raw CSV files using **Power Query**

### 2. Data Transformation

* Cleaned and standardized data formats
* Assigned appropriate data types to each column
* Created **derived columns** from existing data to enhance analytical insights

### 3. Data Modeling

* Designed a **Snowflake schema** with fact and dimension tables
* Established **one-to-many relationships** between tables
* Implemented an optimized data model with proper **cardinality and performance considerations**

### 4. DAX Calculations
* To support advanced analytics, I created a comprehensive set of custom DAX measures. By avoiding Quick Measures and writing optimized DAX code, I ensured precise calculations, improved performance, and full control over business logic.
---

## 📈 Key Analysis & KPIs

### Core KPIs Tracked

* Total Sales
* Total Revenue
* Profit & Profit Margin
* Return Rate
* Customer Lifetime Value (CLV)

### Analytical Dimensions

* Region-wise performance comparison
* Category and product-level trend analysis
* Monthly and quarterly sales trends
* High-value customer segmentation

---

## 📊 Dashboard & Insights

### 📈 Dashboard Pages

#### 1. Executive Dashboard
<img width="1538" height="809" alt="image" src="https://github.com/user-attachments/assets/fad9fb5b-f349-44a9-8fe0-df2a69dbe0f3" />

**Key Metrics:**

* Total Revenue: ₹24.9M
* Total Profit: ₹10.5M
* Total Orders: 25.2K
* Return Rate: 2.2%

**Visualizations:**

* Revenue trending line chart with forecasting
* Order distribution by category (Accessories, Bikes, Clothing)
* Top 10 products by orders, revenue, and return percentage
* KPI cards including Revnue, Profit, Order, Return Rate
* Most ordered and returned product type analysis

#### 2. Customer Detail Dashboard
<img width="1489" height="817" alt="image" src="https://github.com/user-attachments/assets/a650d78f-36d4-4624-883b-af84f40fb487" />


**Key Metrics:**

* Unique Customers: 17.4K
* Revenue per Customer: ₹1,431

**Visualizations:**

* Revenue per customer trend over time
* Top 100 customers table with order count and revenue
* Customer segmentation by income level (High, Average, Low)
* Customer distribution by occupation (Professional, Management, Skilled Manual)

---

## 🚀 Business Impact

* Enabled faster decision-making through real-time KPI visibility
* Helped identify underperforming regions and products
* Supported targeted strategies for high-value customers

---


