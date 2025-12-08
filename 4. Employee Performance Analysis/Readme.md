## 👥 Employee Performance Analysis - HR

### 📌 Project Overview
An end-to-end HR analytics and employee performance dashboard built in Power BI.  
This report enables HR and operations teams to monitor workforce health, performance, retention, promotions, and store-level insights through interactive and drill-through-driven analytics.

---

### 🎯 Business Objectives
- Track total and active headcount over time
- Analyze attrition and retention trends by role, department, and store
- Identify high performers and promotion-ready employees
- Monitor training, overtime, absenteeism, and satisfaction metrics
- Enable detailed employee and store-level performance analysis

---

### 🧠 Data Modeling & Calendar Logic
- Implemented a **custom calendar table using a Power Query (M) function**
- Calendar is dynamically generated (ISO-8601 compliant)
- Supports:
  - Year, Month, Quarter
  - Fiscal year logic
  - Flexible start/end dates
- Ensures reliable and scalable **time-intelligence calculations** across all HR KPIs

---

### 📐 Measures & Model Structure
- Centralized **Measure table** for all calculations
- Measures organized using **Display Folders**, including:
  - Headcount
  - Termination
  - Performance KPIs
  - Training & Overtime
  - Compensation Metrics
- Designed for:
  - Clean model structure
  - High scalability
  - Long-term maintainability

---

### 📊 Key Metrics & KPIs
- Total Headcount / Active Headcount
- Attrition Rate (YoY)
- Retention Rate %
- Terminations (Current vs Previous Year)
- High Performers & High Performers %
- Training Hours & Overtime
- Average Salary, Benefits, Bonus
- Employee Satisfaction & NPS
- Promotion Prediction Categories

---

### 🔄 Drill Through Design
#### ✅ Employee-Level Drill Through
- Drill through from HR overview to **individual employee detail**
- Includes:
  - Performance trend over multiple years
  - Manager evaluation vs employee performance
  - Compensation breakdown
  - Training, overtime, and absenteeism trends
  - Hiring and exit timeline

#### ✅ Store-Level Drill Through
- Drill through from HR and sales analytics to **store detail pages**
- Combines:
  - Workforce KPIs
  - Sales performance metrics
  - Customer satisfaction and delivery indicators
- Enables store-by-store workforce benchmarking

---

### 🎯 Advanced Visualization Techniques
#### ✅ Promotion Timeline Visualization
- Custom promotion timeline built using:
  - Helper (Dummy) measures
  - Line chart with conditional formatting
- Highlights:
  - Promotion years per employee
  - Multiple successful promotions
- Visual indicators dynamically change color based on promotion success count

---

### 🛠 Tools & Technologies
- Power BI Desktop
- DAX
- Power Query (M)
- Measure Parameters
- Drill Through
- Custom Calendar Function

---

### 📌 Dashboard Preview

<p align="center">
  <img src="./Images/HR Metrics.jpg" width="48%" />
  <img src="./Images/Store Metrics.jpg" width="48%" />
</p>

<p align="center">
  <img src="./Images/Employee Details.jpg" width="48%" />
  <img src="./Images/Store Details.jpg" width="48%" />
</p>
