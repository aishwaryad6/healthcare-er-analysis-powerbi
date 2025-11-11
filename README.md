# 🏥 Hospital Emergency Room (ER) Analysis — Power BI

## 📌 Project Overview  
The **Hospital Emergency Room (ER) Analysis** is built in **Power BI** to provide **real-time insights** into critical ER operational metrics. It enables hospital leadership and care coordinators to monitor **patient flow**, **wait times**, **referrals**, and **satisfaction levels**, helping improve staffing decisions, care quality, and resource utilization.

This project demonstrates my expertise in:  
- **Data Analysis & Business Intelligence (BI)**  
- **Power BI Dashboard Development**  
- **Data Modeling, SQL for ETL, and DAX calculations**  
- **Healthcare Data Analytics & Performance Monitoring**

---

## ❗ Problem Statement  
Hospitals often struggle with ER inefficiencies, including:  

- **Long wait times**, leading to patient dissatisfaction.  
- **No visibility** into peak hours, patient demographics, or referral trends.  
- **Inefficient resource allocation** and staffing challenges.  
- **Difficulty tracking admission rates and downstream referrals.**  

Without **real-time insights**, leadership cannot make informed decisions to improve ER operational efficiency.

---

## ✅ Solution Overview  
The Power BI dashboard provides:

- **Real-time tracking of ER performance metrics**
- **Daily, Monthly, and Consolidated views** for trend and variance analysis
- **Patient-level drill-down insights** for case investigation  
- **Interactive filters** (date, department, demographics, referral source)

---

## 🎯 Key Performance Indicators (KPIs)

| KPI | Description | Business Impact |
|-----|-------------|----------------|
| **Total ER Patients** | Total daily visits with trend sparkline | Measures patient inflow and demand |
| **Average Wait Time** | Avg. time before patient is seen | Helps optimize staffing & triaging |
| **Patient Satisfaction Score** | Avg. survey score per day | Identifies service quality issues |
| **Patients Referred** | No. of patients redirected to departments | Highlights referral bottlenecks |

---

## 🛠 Tools & Technologies Used  

| Category | Tools |
|----------|-------|
| Analytics & Visualization | **Power BI** |
| Data Transformation & ETL | **SQL**, **Power Query** |
| Scripting / Cleaning | **Python (Pandas, NumPy, Matplotlib, Seaborn)** |
| Storage / Source Files | **Excel & CSV**, **Azure / AWS (optional)** |

---

## 🗂 Data Model & Structure  

The dashboard uses a **relational data model** integrating multiple healthcare datasets:

### 🔑 Key Tables
- **Patients** → Patient demographics & info  
- **Admissions** → Arrival time, wait time, department, referral status  
- **SatisfactionScores** → Ratings + feedback comments  
- **Calendar** → Supports time intelligence (daily / monthly trends)

### 📌 Data Sources  
- **Patient Admissions Data**  
- **ER Wait Time Logs**  
- **Department Referral Records**  
- **Patient Satisfaction Surveys**  

> `![Data Model](assets/data_model.png)`

---

## 📊 Dashboard Views  

The dashboard is organized into **four analytical views**:

1️⃣ **Monthly View** → KPI comparison by month  
2️⃣ **Consolidated View** → Custom range performance + trend analysis  
3️⃣ **Patient-Level Detail View** → Drill-down with patient-level granularity  
4️⃣ **Summary View** → Snapshot for leadership decision-making  

> `![Dashboard Overview](assets/dashboard_overview.png)`

---

### 🔍 Key Insights  

✔ **Peak ER traffic happens between 10 AM – 4 PM** (highest wait times)  
✔ **Cardiology and Orthopedics receive most referrals** → triage optimization needed  
✔ **Weekend wait times are higher** → staffing imbalance  

---

## 📈 Methodology & Data Processing  

1️⃣ **Data Collection & Cleaning**
- Extracted raw data from SQL + Excel files
- Used Python (Pandas) to handle missing values and remove duplicates

2️⃣ **Data Transformation & Modeling**
- SQL used for joins, aggregations, and filtering
- Built star-schema model in Power BI using Power Query + relationships

3️⃣ **Dashboard Development**
- Developed KPIs using **DAX**
- Designed interactive visualizations + drill-down experience

---

## 💡 Business Recommendations  

| Recommendation | Expected Outcome |
|----------------|------------------|
| Increase staffing during **10 AM – 4 PM** | Reduces wait time & improves throughput |
| Prioritize triage for high-referral departments (Cardiology, Orthopedics) | Lowers patient handoff delays |
| Improve weekend staffing | Addresses predictable performance dip |
| Add predictive forecasting (ML) | Anticipates daily patient load |

---

### ✅ Result  
This dashboard transforms ER operational visibility from **reactive** → **proactive**, enabling data-driven planning and faster patient care.

---

