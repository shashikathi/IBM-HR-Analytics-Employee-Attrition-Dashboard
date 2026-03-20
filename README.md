# 🧑‍💼 IBM HR Analytics — Employee Attrition Intelligence Dashboard

> _"Great companies don't lose great people. They understand why people leave — before they do."_


[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Excel](https://img.shields.io/badge/Excel-Analysis-brightgreen?logo=microsoftexcel&logoColor=white)](https://microsoft.com/excel)
[![Status](https://img.shields.io/badge/Project-Complete-brightgreen)]()

---

## 🚀 TL;DR

**End-to-end HR People Analytics dashboard** that identifies why employees leave — and what HR teams can do about it.

- Analyzed **1,470 employee records** across 35 variables
- Powered by **Python + Power BI** for deep workforce insights
- Uncovered **7 critical attrition drivers** with actionable HR recommendations
- Focus on **retention ROI** — because replacing one employee costs 50–200% of their annual salary 💸

> People Analytics isn't just about dashboards — it's about **saving talent before it walks out the door.**

---

## ⚡ Highlights

- 🧹 Cleaned & validated **1,470 employee records** across 35 HR variables
- 📊 Built **interactive Power BI dashboards** with drill-down by department, role & satisfaction
- 🔍 Identified **overtime** as the #1 attrition predictor — **30.5% turnover vs 10.4% baseline**
- 💰 Uncovered a **$2,046/month pay gap** between employees who left vs stayed
- 🧠 Delivered **7 strategic HR recommendations** mapped directly to each finding
- 📈 Overall Attrition Rate: **16.1%** — Sales Representatives peaking at a critical **39.8%**

---

## 🖼 Dashboard Sneak Peek

### 📊 Overall Attrition Overview
Company-wide attrition breakdown with interactive department and role filters

### 💰 Compensation vs Attrition Analysis
Monthly income comparison — employees who left earned **$2,046/month less** than those who stayed

### ⏰ Overtime Impact Heatmap
Overtime workers leaving at **30.5%** — nearly 3x the non-overtime baseline rate

### 😊 Job Satisfaction Retention Matrix
Satisfaction Level 1 employees churning at **22.8%** vs just **11.3%** for Level 4

### ✈️ Business Travel Attrition Breakdown
Frequent travelers leaving at **24.9%** vs only **8.0%** for non-travel employees

### 📅 Tenure Risk Analysis
Employees who left averaged just **5.1 years** — vs **7.4 years** for those who stayed

---

## 📈 Key Findings Snapshot

| Finding | Segment | Attrition Rate |
|---|---|---|
| 🔴 Overtime Workers | 416 employees | **30.5%** |
| 🔴 Sales Representatives | 83 employees | **39.8%** |
| 🔴 Compensation Gap | Left vs Stayed | **$2,046/month lower** |
| 🟡 Low Job Satisfaction | Level 1 employees | **22.8%** |
| 🟡 Frequent Business Travel | 277 employees | **24.9%** |
| 🟡 Early Tenure Vulnerability | Avg years at company | **5.1 yrs vs 7.4 yrs** |
| 🟢 High Satisfaction Retained | Level 4 employees | **11.3%** ✅ |

---

## 🗂 Folder Structure

```
IBM-HR-Attrition-Analytics/
│
├─ IBM_HR-Analytics_Dashboard.pbix     # Interactive Power BI dashboard
├─ attrition_analysis.py               # Python EDA & statistical analysis
├─ dataset.csv                         # IBM HR Analytics dataset (1,470 records)
├─ Graphs/                             # Exported dashboard visuals
├─ requirements.txt                    # Python dependencies
└─ README.md                           # This file
```

---

## 🧠 Analysis Workflow

1️⃣ **Data Cleaning & Validation** — handled data types, nulls, and standardized 35 categorical & numerical HR variables

2️⃣ **Exploratory Data Analysis (EDA)** — Python/Pandas deep dive into attrition patterns by department, role, salary, satisfaction & tenure

3️⃣ **Key Driver Identification** — cross-tabulation of 7 attrition predictors with statistical comparison across employee segments

4️⃣ **Power BI Dashboard** — interactive visuals with slicers for department, job role, satisfaction level, and travel frequency

5️⃣ **HR Strategy Translation** — every finding converted into a concrete, implementable retention recommendation for HR teams

---

## 💡 Top 3 Strategic HR Recommendations

> Ranked by retention ROI potential:

**1️⃣ Overtime Reduction Policy** 🔴 Highest Impact
> 30.5% of overtime workers leave. Workload audits and role-based staffing adjustments could reduce overall attrition by an estimated 3–5 percentage points.

**2️⃣ Sales Representative Retention Program** 🔴 Urgent
> Nearly 1 in 2 Sales Representatives leave (39.8%). Career path clarity, commission restructuring, and mentorship programs are the highest-leverage interventions for this segment.

**3️⃣ Compensation Benchmarking** 🟡 High ROI
> Employees who left earned $2,046/month less on average. Even a $500–$1,000 salary adjustment in high-risk roles delivers significantly better ROI than full replacement costs.

---

## 🚀 Quickstart

```bash
# Clone repository
git clone https://github.com/shashikathi/IBM-HR-Attrition-Analytics.git
cd IBM-HR-Attrition-Analytics

# Install dependencies
pip install -r requirements.txt

# Run Python EDA analysis
python attrition_analysis.py
```

*(To explore the interactive dashboard)*
```
1. Download Power BI Desktop — free at powerbi.microsoft.com
2. Open IBM_HR-Analytics_Dashboard.pbix
3. Use department, role & satisfaction slicers to explore attrition segments
```

---

## 🧩 Tech Stack

| Category | Tools |
|---|---|
| Data Analysis | Python, Pandas, NumPy |
| Machine Learning | Scikit-learn, Logistic Regression |
| Visualization | Power BI, Matplotlib, Seaborn |
| Spreadsheet Analysis | Microsoft Excel |
| Environment | Jupyter Notebook |

---

## 📊 Dataset

**IBM HR Analytics Employee Attrition & Performance**
- 📁 1,470 employee records
- 📋 35 variables — salary, satisfaction, tenure, travel, overtime, department & more
- 🔗 Source: [Kaggle — IBM HR Analytics Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

> *Fictional dataset created by IBM data scientists for HR analytics education and portfolio development.*

---

## 🌱 Future Enhancements

- 🤖 Predictive attrition model — flag at-risk employees before they resign
- 📡 Real-time HRIS integration for live attrition monitoring
- 🧠 SHAP explainability for individual employee risk scores
- 📧 Automated manager alerts for high-risk employee segments
- 🌐 Streamlit web app for HR teams without Power BI access

---

## 👨‍💻 Author

**Kathi Shashi Preetham Goud** — B.Tech CSE | Data Science & People Analytics
📍 Hyderabad, India

🔗 [LinkedIn](https://linkedin.com/in/shashikathi)
🔗 [GitHub](https://github.com/shashikathi)
📧 shashikathi56@gmail.com

---

## 🌟 Show Some ❤️

If this project helped you understand People Analytics better, give it a ⭐ on GitHub!
Let's build data-driven HR solutions that actually retain great talent. 🚀
