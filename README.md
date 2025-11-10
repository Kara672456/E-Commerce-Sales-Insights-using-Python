<h1 align="center">🛍️ Amazon India Sales Data Analysis (2025)</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Python-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Libraries-Pandas%20%7C%20NumPy%20%7C%20Matplotlib%20%7C%20Seaborn-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Environment-Jupyter%20Notebook-lightgrey?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Dataset-Amazon%20Sales%202025-yellowgreen?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Focus-EDA%20%7C%20Data%20Cleaning%20%7C%20Visualization-purple?style=for-the-badge"/>
</p>

---

## 📘 Executive Summary

This project represents a **comprehensive sales data analysis** for **Amazon India (2025)** using Python and data visualization libraries.  
It explores real-world business questions such as customer preferences, payment trends, and sales distribution across time and regions.  

The analysis takes raw e-commerce data and transforms it into clear, data-driven insights — the kind business managers, analysts, and marketing teams can use to make better strategic decisions.  

---

## 🎯 Project Objectives

1. 🛒 Evaluate **sales and revenue** across categories, regions, and months.  
2. 💳 Identify **preferred payment methods** and their correlation with transaction amounts.  
3. 🏙️ Determine **top-performing states** and cities by total revenue.  
4. 🔁 Analyze **returns and cancellations** to optimize delivery efficiency.  
5. 📊 Generate **visual insights and KPIs** to support data-driven business recommendations.

---

## 🧠 Business Context

In India’s growing e-commerce ecosystem, understanding how and when customers purchase products is critical.  
This analysis simulates Amazon India’s internal analytics — uncovering patterns that explain:  

- Which categories drive maximum revenue  
- How seasonality affects purchase behavior  
- Which payment methods are gaining traction  
- How delivery and return rates influence customer experience  

By combining data exploration and storytelling, this project replicates **real-world analytics tasks** performed by professional data analysts.

---

## 📦 Dataset Description

**Dataset Name:** `amazon_sales_2025_INR.csv`  
**Records:** ~50,000 transactions  
**Type:** Structured CSV dataset (transaction-level)  
**Source:** Synthetic dataset modeled after Amazon India’s sales for 2025  

| Column | Description |
|--------|-------------|
| `Order ID` | Unique identifier for each order |
| `Date` | Order placement date |
| `Category` | Product category (Electronics, Fashion, etc.) |
| `Sub-Category` | Specific product type |
| `Payment Mode` | COD, UPI, Credit Card, Net Banking |
| `Amount` | Order value (INR) |
| `State` | Customer location |
| `Status` | Order status (Delivered / Returned / Cancelled) |

---

## 🧰 Technology Stack

| Tool / Library | Purpose |
|----------------|----------|
| **Python 3.x** | Data analysis and logic |
| **Pandas** | Data wrangling and transformation |
| **NumPy** | Numerical operations |
| **Matplotlib** | Core visualization |
| **Seaborn** | Statistical and aesthetic visualization |
| **Jupyter Notebook** | Interactive development environment |

---

## 🧮 Analytical Workflow

### 🔹 1. Data Understanding
- Imported dataset and reviewed data types, missing values, and structure  
- Performed descriptive statistics and preliminary exploration  

### 🔹 2. Data Cleaning
- Removed duplicate and null records  
- Standardized categorical values (e.g., payment modes, cities)  
- Converted date formats and extracted time-based components (month, quarter)  

### 🔹 3. Data Transformation
- Derived new fields such as revenue per category, sales month, and return ratio  
- Grouped and aggregated sales data across multiple dimensions  
- Created summary tables for Power BI and visualization integration  

### 🔹 4. Exploratory Data Analysis (EDA)
- Visualized categorical and time-based trends  
- Explored payment and category performance metrics  
- Detected outliers and unusual behaviors  

### 🔹 5. Visualization
- Created clean, business-focused charts using Matplotlib and Seaborn  
- Highlighted KPIs through bar charts, pie charts, and trend lines  

---

## 📊 Key Performance Indicators (KPIs)

| KPI | Description |
|------|--------------|
| 💰 **Total Revenue** | Total value of successful transactions |
| 🛍️ **Total Orders** | Number of completed customer purchases |
| 📈 **Average Order Value (AOV)** | Mean amount spent per order |
| 🏙️ **Top Performing States** | Highest contributing regions by revenue |
| 💳 **Payment Mode Split** | Percentage distribution of payment methods |
| 🔁 **Return Rate** | Share of cancelled or returned orders |

---

## 📈 Visual Insights

### 🟩 Sales by Category
![Category Sales](visuals/total_sales_by_category.p_)
