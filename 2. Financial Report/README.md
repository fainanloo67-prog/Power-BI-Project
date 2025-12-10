# Financial Statement Report – Revenue, Expense & Profitability Analytics

This project is an end-to-end Power BI financial reporting solution that replicates a modern **P&L / Income Statement** view for a SaaS-style business.  
The report is designed for both **executive review** and **finance team analysis**, with dynamic views for Revenue, Expenses, COGS, OPEX and Net Income across years, quarters, account classes and detailed account names.

## Project Objectives

- Provide a **statement-style view** of Revenue, COGS, OPEX, Other Expenses and Net Income.
- Track **year-over-year (ΔPY)** performance for each major KPI.
- Analyze **trends by account class and account name** using a structured financial hierarchy.
- Compare **Revenue vs Budget** and **Expenses vs Budget** over time.
- Enable finance teams to quickly identify **which accounts drive growth or margin erosion**.

## Report Pages

### 1. Overview – P&L Summary

- High-level KPIs for:
  - **Revenue**, **Expenses**, **COGS**, **Gross Profit**, **EBIT**, **Net Income**
  - Each KPI includes a **ΔPY %** (Year-over-Year change vs prior year).
- Small-multiple trend charts for each KPI (monthly view with prior-year comparison).
- **Waterfall Profit & Loss** visual to show how each account group contributes from Revenue down to Net Income.
- **Revenue vs Expenses** monthly comparison chart to highlight margin trends.

### 2. Revenue Analysis

- Statement-style layout focused on **top-line performance**:
  - Revenue, Gross Profit, EBIT, Net Income – all with **monthly trends vs last year**.
- **Revenue trends by MEMO**:
  - Contribution of different revenue streams (e.g., Recurring Income, Non Recurring Income, Other Income).
- **Top Accounts Revenue Trends**:
  - Small-multiple area charts for the **top revenue accounts** over time.
- Detailed **Revenue table by account hierarchy**:
  - LEVEL_02 (e.g., Recurring Income) → Account Name
  - Revenue for each year + **Revenue as % of Total** (share of total revenue).

### 3. Expense Analysis

- Dedicated view for **Expense structure and growth**:
  - Total Expenses, COGS, OPEX, Other Expenses – each with monthly trend vs prior year.
- **Expenses Trend by CLASS**:
  - Class-level stacked area chart showing how Customer Support, G&A, R&D, Sales & Marketing, etc. evolve over time.
- **Expenses Trend by NAME**:
  - Top vendor / account trends (e.g., Google Ads, AWS, Payroll, etc.).
- Detailed **Expense table by account name**:
  - Expense per year + **Expense as % of Revenue** to quickly see which accounts are cost-heavy.
- The layout mirrors a **management financial statement**:  
  Overview → Revenue → Expense, with consistent navigation and design.

---

## Analytical Techniques

### Advanced DAX & Measure Branching

- Core base measures for Revenue, COGS, OPEX, Other Expenses, Gross Profit, EBIT, Net Income.
- Derived measures for:
  - **Prior-Year (PY)** metrics  
  - **ΔPY %** (YoY % change)  
  - **Budget vs Actual** for both Revenue and Expenses  
  - **Expense as % of Revenue** and **Revenue share of total**
- Measure branching is used heavily so that **one base measure feeds multiple derived KPIs**, keeping the model clean and maintainable.

---

## Dashboard Preview

<p align="center">
  <img src="./Images/Overview.jpg" width="90%" />
</p>
<p align="center">
  <img src="./Images/Revenue.jpg" width="90%" />
  <img src="./Images/Expense.jpg" width="90%" />
</p>

