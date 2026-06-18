# 🛒 SwiftMart Sales, Customer Performance & Churn Analysis Dashboard

> An end-to-end Excel data analytics project focused on sales performance, customer behavior, retention analysis, and churn monitoring through interactive dashboards.

---

## 📌 Table of Contents

* Project Overview
* Problem Statement
* Business Objectives
* Project Workflow
* Data Cleaning & Preparation
* Feature Engineering
* Business KPIs
* Dashboard Overview
* Key Insights
* Tech Stack
* Project Structure
* Dashboard Preview

---

## 📖 Project Overview

SwiftMart is a fictional e-commerce company seeking to improve business performance through data-driven decision-making.

This project transforms raw transactional data into an interactive Excel dashboard solution that helps stakeholders:

* Monitor revenue and profitability trends
* Analyze customer purchasing behavior
* Identify high-value customers
* Measure customer retention and churn
* Track product and category performance
* Support strategic business decisions

---

## ❓ Problem Statement

E-commerce businesses generate large amounts of transactional data but often struggle to convert it into actionable insights.

Key questions addressed:

* Which products and categories generate the most revenue?
* Which customers contribute the highest business value?
* How effectively is the company retaining customers?
* What percentage of customers are at risk of churn?
* Which customer segments require attention?

---

## 🎯 Business Objectives

| Objective             | Description                                        |
| --------------------- | -------------------------------------------------- |
| Revenue Analysis      | Track sales growth and profitability               |
| Customer Analysis     | Understand purchasing behavior and customer value  |
| Product Performance   | Identify best-performing products and categories   |
| Customer Retention    | Monitor active, at-risk, and churned customers     |
| Business Intelligence | Build an interactive dashboard for decision-makers |

---

## 🔄 Project Workflow

Raw CSV Files
↓
Power Query Data Cleaning
↓
Data Modeling & Relationships
↓
Feature Engineering
↓
KPI Calculation
↓
Interactive Excel Dashboard (3 Pages)

---

## 🧹 Data Cleaning & Preparation

The dataset was cleaned and transformed using Power Query.

Key steps performed:

* Removed duplicate records
* Handled missing values
* Standardized data types
* Corrected invalid records
* Managed missing product information
* Created relationships between Orders, Customers, and Products tables
* Built a centralized data model using Power Pivot

---

## ⚙️ Feature Engineering

Additional business fields were created to improve analysis:

### Customer Status

Customers were classified into:

* Active Customer
* At Risk Customer
* Churned Customer

Based on the difference between customer purchase dates and the latest transaction date available in the dataset.

### Customer Lifetime Value (CLV)

Estimated customer value generated throughout their relationship with the business.

### Age Group Segmentation

Customers categorized into:

* Young
* Adult
* Senior
* Older

### Repeat Customer Indicator

Used to identify customer loyalty and retention patterns.

---

## 📊 Business KPIs

The dashboards track key business metrics:

* Total Revenue
* Total Profit
* Total Orders
* Total Customers
* Average Order Value (AOV)
* Customer Lifetime Value (CLV)
* Repeat Customer Rate
* Churn Rate
* Retention Rate
* Active Customers
* At Risk Customers
* Churned Customers
* Profit Margin

---

## 📈 Dashboard Overview

### Dashboard 1 — Executive Dashboard

High-level overview of business performance.

Includes:

* Revenue Trend
* Profit Trend
* Sales by Category
* Top Cities by Revenue
* Order Status Distribution
* Executive KPIs

---

### Dashboard 2 — Sales & Customer Performance Dashboard

Customer and product performance analysis.

Includes:

* Top Products by Revenue
* Top Products by Profit
* Sales by Customer Segment
* Top Customers by CLV
* Customer Revenue Analysis
* Product Performance Analysis

---

### Dashboard 3 — Churn & Retention Dashboard

Customer retention and churn monitoring.

Includes:

* Active Customers
* At Risk Customers
* Churned Customers
* Customer Status Distribution
* Churn by Customer Segment
* Churn by Age Group
* Revenue by Customer Status
* Monthly Active vs Churned Customers

---

## 💡 Key Insights

* Revenue and profit trends highlight seasonal business performance.
* A small group of customers contributes a significant share of total revenue.
* Customer retention remains a key driver of long-term profitability.
* Certain customer segments show higher churn risk.
* Product performance varies significantly across categories.
* High-value customers can be identified using CLV analysis.

---

## 🛠️ Tech Stack

| Tool            | Purpose                        |
| --------------- | ------------------------------ |
| Microsoft Excel | Dashboard Development          |
| Power Query     | Data Cleaning & Transformation |
| Power Pivot     | Data Modeling                  |
| Pivot Tables    | KPI Calculations               |
| Pivot Charts    | Data Visualization             |
| Excel Formulas  | Feature Engineering            |

---

## 📁 Project Structure

swiftmart-sales-customer-churn-analysis/

├── Data/
│ ├── Orders.csv
│ ├── Customers.csv
│ └── Products.csv
│
├── Dashboard/
│ └── SwiftMart_Sales_Customer_Churn_Analysis.xlsx
│
├── Screenshots/
│ ├── Executive_Dashboard.png
│ ├── Sales_Customer_Performance.png
│ └── Churn_Retention_Dashboard.png
│
└── README.md

---

## 🖼️ Dashboard Preview

### Executive Dashboard

(Add Screenshot)

### Sales & Customer Performance Dashboard

(Add Screenshot)

### Churn & Retention Dashboard

(Add Screenshot)

---

## 🤝 Connect With Me

* LinkedIn: Your LinkedIn Profile
* Email: Your Email Address

---

⭐ If you found this project useful, consider giving it a star.
