# 📊 Dyno Lab Utilization Dashboard (Power BI)

## 📌 Overview
This project is an end-to-end Power BI solution built to monitor and analyze the utilization of Dyno Labs used for automotive testing.

The dashboard provides insights into operational efficiency, helping management track utilization, idle time, breakdown hours, and engineer workload.

## One of the projects I worked on was a Testbed Utilization Dashboard in Power BI. The goal was to track testbed efficiency, monitor idle and breakdown hours, and analyze engineer workload for better resource planning.

I first designed an Excel-based data collection template with validation rules to ensure accurate and standardized data entry. Then, I built a star schema data model in Power BI using dimension and fact tables. I also created a custom calendar in DAX to handle company-specific working days, holidays, and working Saturdays.

Using DAX, I developed measures like Total Working Hours, Idle Hours, Breakdown Hours, and Utilization %. Finally, I created interactive dashboards to visualize utilization trends, engineer performance, and testbed efficiency.

The project improved operational visibility, reduced manual reporting effort, and helped management make better resource allocation decisions.

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
