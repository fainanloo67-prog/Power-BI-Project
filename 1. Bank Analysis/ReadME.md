# Transaction Banking Report (Bank Analysis)

## 📌 Project Overview
This Power BI solution analyzes **transaction banking performance** for a fictional retail bank in Spain.  
The report tracks total amounts, fees, transactions, and customers over time and breaks them down by
customer segment, branch, channel, and product category.

## 🎯 Business Questions
- How are **total transaction amounts and fees** trending year over year?
- Which **customer segments and income levels** generate the most activity and revenue?
- Which **branches and channels** (ATM, mobile, branch, online) are performing best?
- How do different **products** (loan, credit card, checking account, mortgage, etc.) contribute to
  total revenue and late payment fees?
- Where are there opportunities to improve **customer behaviour and profitability**?

  
## 🧠 DAX & Modeling Techniques

This project leverages **enterprise-level semantic modeling techniques** to keep the model
scalable, clean, and maintainable.

### ✅ Calculation Groups (Tabular Editor)
The model uses **Calculation Groups created in Tabular Editor** to standardize time-intelligence
logic across all measures, including:

- **12-Month Rolling Average (RAVG 12M)**
- **Year-over-Year (YoY / ΔPY) calculations**
- **Dynamic YoY text indicators** (used in KPI cards)

By using Calculation Groups:
- Time-intelligence logic is written **once** and applied to all relevant measures
- Measure duplication is avoided
- DAX remains concise and reusable
- The semantic model scales easily as new KPIs are added

### ✅ Measure Organization & Display Folders
Measures are organized in a dedicated **Measure table**, with clear display folders
created and maintained using **Tabular Editor**, including:

- Main Measures
- Revenue Measures
- Customer Behaviours
- KPI_PY_Measures
- Visualization Measures
- Currency Switch

This structure improves:
- Model readability
- Developer productivity
- Long-term maintainability

### ✅ Time-Intelligence & KPI Logic
- Current vs Previous Year (YoY / ΔPY)
- Percentage change indicators
- Rolling 12-month averages
- Dynamic formatting and KPI-driven visuals
