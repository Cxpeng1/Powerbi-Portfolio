# 📊 Superstore Sales Performance Dashboard

## 📌 Project Overview

This project analyzes retail sales performance using the Superstore dataset.  
The objective is to transform raw transactional data into actionable business insights using Power BI.

The dashboard progresses from high-level KPIs to detailed product, customer, geographic, and strategic insights.

---

## 🎯 Business Objectives

This dashboard answers the following key business questions:

- Which states and cities generate the highest revenue?
- Which product categories are both best-selling and most profitable?
- Which sub-categories and products are underperforming?
- Which customer segment contributes the most profit?
- What is the most preferred shipping mode?
- How has company performance trended over time?
- Where are the key risks and growth opportunities?

---

## 🗂 Dataset

- **Source:** Superstore retail dataset
- **Granularity:** Transaction-level data
- **Time Range:** Multi-year historical data

---

## 🧹 Data Processing & Modeling

### ✔ Data Validation

- Verified correct data types
- Checked for null values
- Reviewed duplicates
- Identified negative profit transactions
- Validated discount column consistency

### ✔ Data Modeling (Star Schema)

- Created a separate **Date Table** using DAX
- Included:
  - Year
  - Month
  - Quarter
  - Year-Month
- Established a one-to-many relationship with the Orders table
- Marked as official Date Table

This enables:

- Time intelligence (YoY growth, trend analysis)
- Continuous date tracking
- Best practice data modeling

---

## 📈 Dashboard Structure

### 1️⃣ Overview

High-level business performance:

- Total Revenue
- Total Profit
- Profit Margin %
- Total Orders
- Revenue & Profit Trend
- Sales by Category
- Sales by State (Map)

---

### 2️⃣ Product Performance

- Top 3 Sub-Categories
- Top 10 Loss-Making Products
- Profit Margin by Sub-Category
- Revenue vs Profit Scatter Analysis

**Focus:** Identify top performers and profitability risks.

---

### 3️⃣ Customer & Operational Insights

- Segment Sales & Profit Trends
- Top 10 Customers by Revenue
- Profit Margin by Segment
- Shipping Mode Analysis

**Focus:** Customer profitability and operational behavior.

---

### 4️⃣ Geographic Analysis

- Sales by State (Filled Map)
- Top States by Revenue
- Top Cities by Revenue
- Regional Profitability Analysis

**Focus:** Revenue concentration and regional performance.

---

### 5️⃣ Executive Summary

Strategic KPIs:

- Revenue Growth %
- Profit Growth %
- Profit Margin
- Loss-Making Product Count

Includes:

- Key Business Findings
- Strategic Recommendations

---

## 🔍 Key Insights

- Consumer segment drives the highest revenue and profit contribution.
- Technology category delivers the strongest profit margins.
- Revenue is concentrated among top customers.
- Several products consistently generate negative profit.
- Shipping mode impacts profitability trends.

---

## 🚀 Strategic Recommendations

- Review pricing and discount strategy for loss-making products.
- Focus marketing efforts on high-margin categories.
- Reduce dependency on top revenue-contributing customers.
- Optimize shipping cost structure to improve margin.
- Monitor discount impact on profitability.

---

## 🛠 Tools & Technologies

- Power BI
- DAX (Time Intelligence, KPI Calculations)
- Data Modeling (Star Schema)
- Data Cleaning & Validation

---

## 📌 Skills Demonstrated

- Data cleaning & transformation
- Data modeling best practices
- Time intelligence calculations
- KPI development
- Profitability analysis
- Geographic analysis
- Business insight generation
- Executive-level dashboard design

---

## 💼 Business Value

This dashboard transforms raw retail data into:

- Clear performance tracking
- Profitability visibility
- Risk identification
- Strategic decision support

It bridges descriptive analytics and business decision-making.

---

## 📷 Dashboard Preview

_(Insert screenshots here)_

---

## 👨‍💻 Author

**Chan Xu Peng**  
Bachelor of Computer Science (Data Science)  
Power BI | SQL | Python | Data Analytics

---
