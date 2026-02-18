# 🧠 Employee Health & Productivity Analytics

## Optimizing Workforce Performance: An Analysis of Employee Health, Stress, and Productivity Drivers

**Sector:** Human Resources / Corporate Wellness Analytics
**Institute:** Newton School of Technology

---

## 👥 Team Members

* Aditya Srivastava
* Hardik Hathwal
* Syed Darain Qamar
* Srijan Patel
* Abhinav Choudhary
* Rohan Choudhary

---

# 📌 Executive Summary

### 🔎 Problem

A mid-sized corporate organization lacks data-driven visibility into how employee health factors (stress, sleep, lifestyle) impact productivity. HR decisions around wellness and workload management are based on intuition rather than analytics, increasing burnout risk and reducing efficiency.

### 🛠 Approach

We acted as Workplace Analytics Consultants and analyzed ~10,500 employee records.
Our process included:

* Data cleaning & standardization (Google Sheets)
* KPI framework development
* Correlation analysis
* Segmentation & risk detection
* Interactive dashboard development

### 🔥 Key Insights

* **Stress is the primary productivity driver** → Correlation: **-0.81**
* **Sleep significantly impacts performance** → Correlation: **+0.77**
* **4.32% employees are High Health Risk**, requiring urgent intervention

### ✅ Key Recommendations

* Implement workload control policies
* Launch stress-management programs
* Promote sleep hygiene initiatives

---

# 🏢 Sector & Business Context

## Sector Overview

HR Analytics (People Analytics) is increasingly used to optimize employee productivity through health and behavioral insights.

## Current Challenges

* Rising burnout and stress
* Hidden productivity risks (sleep deficit, stress, overwork)
* Health and performance data stored separately

## Why This Problem?

This project quantifies how employee health impacts productivity and enables HR to make evidence-based workforce decisions.

---

# 🎯 Problem Statement

> Which employee health and lifestyle factors most significantly impact productivity, and what targeted HR interventions can optimize performance while minimizing burnout risk?

---

# 📊 Project Scope

**Population:** 10,500 employees
**Departments:** IT, HR, Marketing, Finance, Operations

**Variables Analyzed:**

* Productivity Score
* Stress Level
* Sleep Hours
* Work Hours
* Step Count
* Heart Rate
* Smoking Status

**Tools Used:** Google Sheets

---

# 📈 Success Criteria

* Identify ≥ 3 high-impact correlations
* Develop Burnout Risk metric
* Create interactive dashboard with segmentation

---

# 📁 Data Description

**Size:** ~10,500 rows × 15 columns
**Format:** Structured CSV

### Key Columns

* `EmployeeID`
* `Department`
* `StressLevel`
* `SleepHours`
* `ProductivityScore`
* `WorkHours`
* `HeartRate`
* `SmokingStatus`

### Data Limitations

* Stress is self-reported
* No historical time-series data
* Snapshot analysis only

---

# 🧹 Data Cleaning & Preparation

Performed in Google Sheets.

### Missing Values

Filled missing values in:

* Age
* Department
* SleepHours
* WorkHours
* ProductivityScore
* Gender

### Standardization

* Corrected case inconsistencies
* Standardized categorical variables
* Ensured numeric formatting
* Verified unique EmployeeID

### Feature Engineering

Created:

* **SleepBucket:** Sleep Deficit (<6), Optimal (6–8), Excess (>8)
* **WorkHourCategory:** Underutilized, Balanced, Overwork
* **StressCategory:** Low, Moderate, High

---

# 📊 KPI & Metric Framework

### 1️⃣ Average Productivity Score

`AVERAGE(ProductivityScore)` → **52.14**

Baseline organizational performance.

---

### 2️⃣ High Health Risk Rate

`454 / 10500` → **4.32%**

Identifies vulnerable employees.

---

### 3️⃣ Sleep Deficit Risk Rate

`3815 / 10500` → **36.33%**

Sleep strongly impacts productivity.

---

### 4️⃣ High Stress Risk Rate

`3483 / 10500` → **33.17%**

Stress significantly reduces output.

---

### 5️⃣ Overwork Risk Rate

`3628 / 10500` → **34.55%**

Overwork does not proportionally increase productivity.

---

# 📊 Exploratory Data Analysis (EDA)

## Trend Analysis

* Sleep Deficit group shows lowest productivity
* Balanced work hours outperform Overwork
* High stress employees show sharp productivity decline

## Correlation Analysis

| Variable Pair              | Correlation | Insight                |
| -------------------------- | ----------- | ---------------------- |
| Stress vs Productivity     | **-0.81**   | Strong negative impact |
| Sleep vs Productivity      | **+0.77**   | Strong positive impact |
| Work Hours vs Productivity | +0.12       | Weak relationship      |

---

# 🧠 Advanced Analysis

## Segmentation (Health Risk Matrix)

* **Segment A:** High Stress + Low Sleep → Critical Risk
* **Segment B:** Moderate Stress + Balanced Work → Sustainable
* **Segment C:** Low Stress + High Performance → Model Employees

## Risk Detection

4.32% flagged as High Health Risk → Priority HR intervention group.

---

# 📊 Dashboard Design

## Implementation

Built in Google Sheets using:

* Pivot Tables
* KPI Scorecards
* Slicers
* Interactive charts

## Dashboard Objective

Provide HR with a centralized, real-time view of workforce health and productivity relationships.

## Structure

* **Top Row:** KPI cards
* **Middle Section:** Productivity comparisons
* **Bottom Section:** Distribution metrics

## Filters

* Age Group
* Health Risk
* Sleep Bucket
* Stress Category

---

# 📌 Key Insights (Decision-Oriented)

* Stress is the strongest productivity driver.
* Sleep below 6 hours significantly reduces output.
* Overwork shows diminishing returns.
* 36% workforce has sleep deficit.
* 33% workforce experiences high stress.
* 4.32% require immediate health intervention.

---

# 🚀 Recommendations

* Implement structured stress management programs.
* Introduce email curfew policy (post 7 PM).
* Cap excessive work hours.
* Provide free health screenings.
* Promote sleep and wellness campaigns.

---

# 💰 Business Impact Estimation

* Shifting Sleep Deficit group → potential **10–15% productivity gain**
* Targeting High Risk group reduces medical leave & turnover
* Reduced burnout improves service quality

---

# ⚠ Limitations

* Self-reported stress bias
* Correlation ≠ causation
* No time-series analysis

---

# 🔮 Future Scope

* Regression-based productivity prediction
* Sentiment analysis on employee comments
* Historical trend analysis
* Wearable-based objective health data

---

# 🏁 Conclusion

Employee health is not just a wellness issue — it is a productivity driver.
By addressing High Stress (33%) and Sleep Deficit (36%), the organization can unlock significant latent performance.

The dashboard enables leadership to shift from:

> **“Managing Attendance” → “Managing Energy.”**

---

# 📚 Appendix

### Data Dictionary

* `SleepBucket`
* `ProductivityGap`
* `StressCategory`
* `WorkHourCategory`

---

# 👥 Contribution Matrix

| Member            | Role               |
| ----------------- | ------------------ |
| Aditya Srivastava | Report Lead        |
| Hardik Hathwal    | Data Analyst       |
| Syed Darain Qamar | Project Lead       |
| Srijan Patel      | Data Analyst       |
| Abhinav Choudhary | Visualization Lead |
| Rohan Choudhary   | Research Support   |

---