# 🛒 Flipkart E-Commerce Sales Analysis & Forecasting

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-Metric-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

**Author:** Risheek Bajaj  
**Email:** bajajrisheek012@gmail.com  
**Tools Used:** Microsoft Power BI, Power Query, DAX, Excel

---

## 📑 Table of Contents
1. [Project Overview](#-project-overview)
2. [Problem Statement](#-problem-statement)
3. [Data Architecture & Modeling](#-data-architecture--modeling)
4. [Key Insights & Findings](#-key-insights--findings)
5. [Dashboard Structure](#-dashboard-structure)
6. [Technical Challenges & Solutions](#-technical-challenges--solutions)

---

## 🚀 Project Overview
This project involves a comprehensive analysis of Flipkart's e-commerce sales data to understand business performance across multiple dimensions: sales, profitability, customer behavior, and product performance. Using **Power BI**, I transformed raw transactional data into an interactive report that empowers stakeholders to make data-driven decisions regarding inventory, marketing, and revenue forecasting.

**Key Metrics Snapshot:**
* **Total Revenue:** $160M 
* **Total Profit:** $88M 
* **Total Products Sold:** 713K 
* **Total Orders:** 113K 

---

## 🎯 Problem Statement
In the competitive online marketplace, identifying meaningful patterns in massive datasets is difficult. The objective of this report was to:
1.  **Analyze Performance:** Track KPIs like Total Revenue, Profit, and Order Volume over time.
2.  **Customer Segmentation:** Understand demographics (Age, Gender) and buying patterns to improve targeting.
3.  **Product Optimization:** Identify top-selling and least-selling categories to optimize inventory.
4.  **Forecasting:** Predict future revenue and analyze how price/discount changes impact profitability.

---

## 🏗 Data Architecture & Modeling

I engineered a **Star Schema** data model to ensure efficient query performance and accurate reporting.

### 1. Fact Table
* **Fact_Ecommerce:** Contains quantitative data such as Order ID, Sale Price, Shipping Fee, Order Quantity, and Status.

### 2. Dimension Tables
* **Dim-Customer:** Customer details including Age, Gender, Location, and Zone.
* **Dim-Product:** Product Name, ID, and Category links.
* **Dim-Order:** Order Date, Delivery Type, and Delivery Status.
* **Dim-Calendar:** A dedicated date table for time-intelligence analysis (Year, Quarter, Month).
* **Dim-Location/Category:** Hierarchical tables for granular analysis.

---

## 📊 Dashboard Structure

The report is divided into 5 interactive pages, each serving a specific analytical purpose:

### 1. Overview Dashboard
* *Goal:** High-level executive summary of business health.
* **Visuals:** KPI cards for Revenue and Profit; Trend lines for Revenue by Year; Zone-wise revenue distribution.
* **Insight:** Zone 3 is the highest revenue contributor ($69M), significantly outperforming Zone 4 ($21M).

### 2. Order Insights
* *Goal:** Analyze shipping efficiency and order characteristics.
* **Visuals:** Orders by Status (Delivered vs. Returned), Age Group analysis, and Delivery Type.
* **Insight:** There is a significant return rate (~26.99%), indicating a potential area for operational improvement.

### 3. Product Insights
* *Goal:** Identify high-performing categories and trends.
* **Visuals:** Revenue by Product Category/Sub-category, Weekly sales trends.
* **Insight:** **Fashion** ($52.82M) and **Electronics** ($48.84M) are the dominant categories, contributing over 60% of total revenue.

### 4. Customer Insights
* *Goal:** Understand who the customers are and where they come from.
* **Visuals:** Customer distribution by Location (Top locations: Greater Accra, Ashanti), Revenue per Customer Gender.
* **Insight:** The customer base is heavily concentrated in specific regions, suggesting targeted regional marketing could be effective.

### 5. Profit Insights & Forecasting
* *Goal:** Predictive analytics for future planning.
* **Visuals:** "What-if" parameters for Price and Discount increments; Profit forecasting based on historical trends.
* **Capability:** Allows stakeholders to simulate scenarios (e.g., "What happens to profit if we increase discounts by 5%?").

---

## 💡 Key Findings & Recommendations

1.  **High Return Rate:** With nearly **27% of orders returned**, investigation into product quality or description accuracy in the "Fashion" category is recommended.
2.  **Category Dominance:** Fashion and Electronics drive the business. Inventory strategies should prioritize these high-volume categories to prevent stockouts.
3.  **Regional Focus:** Marketing spend should be optimized by focusing on top-performing zones (Zone 3) while investigating low-performance reasons in Zone 4.
4.  **Strategic Pricing:** The forecasting model suggests that minor adjustments in discount strategies could significantly impact net profitability, which can be tested using the "What-If" parameters built into the dashboard.

---

## 📬 Contact
If you have questions about this analysis or want to discuss data strategies:

* **Name:** Risheek Bajaj
* **Email:** bajajrisheek012@gmail.com
* **Portfolio:** https://risheekbajaj.github.io/
* **LinkedIn:** https://www.linkedin.com/in/risheek-bajaj/