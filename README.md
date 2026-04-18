# 📊 Dyno Lab Utilization Dashboard (Power BI)

## 📌 Overview
This project is an end-to-end Power BI solution built to monitor and analyze the utilization of Dyno Labs used for automotive testing.

The dashboard provides insights into operational efficiency, helping management track utilization, idle time, breakdown hours, and engineer workload.

> ⚠️ Note: Sample data is used for demonstration purposes.

---

## 🎯 Objective
- Track utilization efficiency of testbeds
- Monitor idle and breakdown hours
- Analyze engineer workload
- Provide insights for better resource planning

---

## 🛠 Tools & Technologies
- Power BI
- DAX (Data Analysis Expressions)
- Excel (data collection & validation)

---

## ⚙️ Methodology

### 1️⃣ Data Collection Design
- Designed Excel-based data entry template
- Implemented validation rules and dropdown controls
- Standardized logging format for reliable data input

---

### 2️⃣ Custom Calendar (DAX)
Created a custom calendar to handle:
- Company-specific working days
- Special holidays
- Working Saturdays
- Non-standard schedules

---

### 3️⃣ Data Modeling (Star Schema)

#### Dimension Tables:
- DimDate
- DimEngineer
- DimTestbed
- DimModel
- DimCategory

#### Fact Table:
- FactTestHours

Established relationships:
- Fact → Dimension (Many-to-One)
- Single-direction filtering for performance optimization

---

### 4️⃣ Key DAX Measures

- Total Working Hours
- Idle Hours
- Breakdown Hours
- Utilization %

Utilization Formula:


---

### 5️⃣ Dashboard Visualizations

- Monthly Utilization Trends (Line Chart)
- Hour Distribution (Donut Chart)
- Engineer-wise Utilization (Bar Chart)
- Testbed Performance (Stacked Bar)
- Category-wise Distribution (Pie Chart)
- Model-wise Analysis

---

## 📊 Insights Generated
- Identified underutilized testbeds
- Highlighted breakdown trends
- Tracked engineer efficiency
- Improved visibility into operations

---

## 🚧 Challenges Faced
- No structured dataset initially
- Handling complex working day logic
- Designing scalable data model
- Creating meaningful KPIs

---

## 📈 Impact
- Eliminated manual reporting effort
- Improved operational visibility
- Enabled data-driven decision-making
- Optimized resource allocation

---

## 🚀 Future Improvements
- Real-time dashboard integration
- Predictive maintenance using historical trends
- Automated alerts for low utilization
