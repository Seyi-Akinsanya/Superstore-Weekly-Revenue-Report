# :bar_chart: Business Requirements Document (BRD) - Superstore Revenue Report Dashboard :notebook:

---

## :pushpin: 1.0 Overview

### :triangular_flag_on_post: 1.1 Purpose
The **Superstore Revenue Report Dashboard** provides **executives, product category managers, and regional managers** with a **real-time view of sales performance, average order value (AOV), and profit margins** across different categories, markets, and regions.

The dashboard facilitates **data-driven decision-making** by:
- Tracking **weekly sales trends**.
- Identifying **underperforming categories**.
- Supporting **regional market analysis**.

### :triangular_flag_on_post: 1.2 Objectives
- Provide **executives** with a **high-level overview** of key revenue performance indicators.
- Enable **product category managers** to **analyze sales trends by category and sub-category**.
- Assist **regional managers** in evaluating **market and region-based sales performance**.
- Support **data-driven decisions** with **interactive drill-through features**.
- Identify **underperforming product categories and regions** to take corrective action.

---

## :pushpin: 2.0 Business Needs & Requirements

### :triangular_flag_on_post: 2.1 Key Business Questions Answered

#### 🎯 **Executives**
- What is the overall **sales revenue**, **profit margin**, and **AOV** for the current reporting week?
- How does **current performance compare** to forecast, last year, and the five-week rolling average?
- Are we meeting financial **targets and expectations**?

#### 📊 **Product Category Managers**
- How are different **product categories** performing in terms of **sales vs forecast**?
- Which **sub-categories** are contributing most to revenue, and which ones are underperforming?
- What trends can be identified within specific **product groups**?

#### 🌍 **Regional Managers**
- How does **sales performance vary by region**?
- What are the **strongest and weakest markets** in terms of revenue and profit?
- How can we **optimize regional sales strategies** to improve performance?

---

## :pushpin: 3.0 Dashboard Components & Functionalities

### :triangular_flag_on_post: 3.1 High-Level KPIs (Top Metrics)
- **💰 Sales Revenue:** `$89.70K` - Total revenue for the selected reporting week.
- **📈 Average Order Value (AOV):** `$444.08` - The average sales per transaction.
- **📊 Profit Margin:** `11.07%` - Percentage of revenue retained as profit after expenses.

#### **Comparison Metrics**
- **Forecast Comparison** – Deviation from projected performance.
- **Last Year’s Performance** – YoY (Year-over-Year) growth or decline.
- **Five-Week Rolling Average** – Short-term trend analysis.

### :triangular_flag_on_post: 3.2 Interactive Features
- **📅 Week Selector (Left Panel)** – Users can select different weeks to view historical data.
- **📊 Tab Selector (Sales | AOV | Profit Margin)** – Users can toggle between KPIs for detailed analysis.
- **🔍 Drill-through Options** – Clicking on a category, sub-category, or region enables deeper insights.

### :triangular_flag_on_post: 3.3 Category Analysis
- **Product Categories (Sales vs Forecast)**
  - **Overperforming Categories:** `Office Supplies (+$2.6K)`, `Furniture (+$2.5K)`.
  - **Underperforming Categories:** `Technology (-$9.6K)`.

### :triangular_flag_on_post: 3.4 Regional Market Performance
- **Regional Sales vs Forecast**
  - **Best Performing Markets:** `USCA ($7K)`, `Europe ($5K)`.
  - **Worst Performing Markets:** `Asia Pacific (-$13K)`, `LATAM (-$4K)`.

### :triangular_flag_on_post: 3.5 Sub-Category Performance
- **Sales vs Forecast (Scatter Plot)**
  - Each dot represents a **sub-category**.
  - **Clickable for drill-through analysis**.
  - Example: **Printers & Copiers perform well, while Machines & Appliances underperform.**

### :triangular_flag_on_post: 3.6 Regional Sales Performance
- **Sales, Profit, and Orders by Region**
  - Includes **regional breakdown of sales, profit, and order count**.
  - Helps **regional managers prioritize interventions** in struggling regions.

---

## :pushpin: 4.0 Functional Requirements

### :triangular_flag_on_post: 4.1 Data Sources
- **Sales Data** – Real-time sales transactions database.
- **Forecast Data** – Sales projections for comparison.
- **Historical Data** – Previous years’ revenue for trend analysis.
- **Regional & Product Data** – Category and market-level breakdowns.

### :triangular_flag_on_post: 4.2 Data Refresh & Update Frequency
- **🔄 Weekly refresh** aligned with reporting weeks.
- **🕒 Historical data retention** for trend analysis over multiple periods.

### :triangular_flag_on_post: 4.3 User Access & Permissions
- **Executives** – Full access to all metrics and drill-through features.
- **Product Category Managers** – Access to **category and sub-category** data.
- **Regional Managers** – Access to **regional sales data and market insights**.

---

## :pushpin: 5.0 Business Rules & Constraints

- All **monetary values** are in **USD**.
- Sales forecasts are **updated quarterly**, but weekly reports **compare actual vs forecast**.
- Drill-through capabilities are available **only for category, sub-category, and regional views**.

---

## :pushpin: 6.0 Success Criteria

- **Executives can quickly assess** overall financial performance and compare against forecasts.
- **Category managers can identify** which product categories/sub-categories need attention.
- **Regional managers can analyze** sales trends across different markets.
- The dashboard enables **data-driven decision-making** to improve revenue and profit.

---

## :pushpin: 7.0 Appendix

### :triangular_flag_on_post: 7.1 Glossary
- **Sales Revenue** – Total income generated from sales transactions.
- **AOV (Average Order Value)** – Total sales revenue divided by the number of transactions.
- **Profit Margin** – Percentage of revenue that remains after deducting costs.
- **Forecast** – Predicted revenue performance based on business models.
- **Five-Week Rolling Average** – Moving average of sales over the last five weeks.

---

## :pushpin: 8.0 Final Notes

This BRD ensures that the **Superstore Revenue Report Dashboard** meets the analytical needs of **executives, product category managers, and regional managers** by providing an **interactive, data-driven approach** to:
- **Tracking performance**.
- **Identifying trends**.
- **Making strategic business decisions**.

🚀 **For inquiries, please contact:**
- 📧 **Seyi Akinsanya** at `akinsanyaseyi225@gmail.com`
