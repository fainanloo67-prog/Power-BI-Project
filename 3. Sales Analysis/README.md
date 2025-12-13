# North America Retail Sales Analysis 

A multi-page Power BI sales analytics solution built to analyze retail performance across North America, focusing on sales growth, profitability, customer behavior, returns, discounts, and delivery efficiency.
This project emphasizes **advanced DAX techniques**, **dynamic ranking logic**, **centralize time intelligence logic with Calculation Groups** and **business-focused visual storytelling** for executive decision-making.

## Business Objectives
- Track overall sales, profit, orders, and returns
- Analyze year-over-year (YoY) performance trends
- Identify top and bottom performing entities across multiple dimensions
- Understand the relationship between discount, profit, and returns
- Provide actionable insights through interactive dashboards

## Data Modeling & Analytics Approach

### Tabular Editor & Calculation Groups

**Calculation Groups** were created using Tabular Editor to centralize time intelligence logic (e.g., Actual, PY, YoY %, Moving Average).

### Measure-Driven Model
- Centralized **Measure table** for all KPIs
- Measures grouped using **Display Folders** for clarity and maintainability

### Dynamic Ranking Technique
This project uses a fully **DAX-driven ranking model**, including:
- Dynamic **Top / Bottom N ranking**
- Ranking controlled by slicer input
- Ranking adaptable across:
  - City
  - State
  - Product
  - Customer
- Measure-based ranking logic (no hard-coded visuals)

### Advanced Visual Support Measures
- Dummy measures for:
  - Bubble positioning
  - Dynamic labels
  - Controlled ranking visuals
- KPI-specific measures aligned with ranking logic


## Dashboard Preview

<p align="center">
  <img src="./Images/Sales Metrics & Trends.jpg" width="90%" />
  <img src="./Images/Sales Analysis.jpg" width="90%" />
</p>

<p align="center">
  <img src="./Images/Sales Insights.jpg" width="90%" />
</p>

