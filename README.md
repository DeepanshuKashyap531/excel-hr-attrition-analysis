# 📊 HR Attrition Analysis — Microsoft Excel
### IBM HR Analytics Dataset — Identifying Key Drivers of Employee Turnover

**Author:** Deepanshu Kashyap  
**Tool:** Microsoft Excel (Pivot Tables, Charts, Dashboard)  
**Dataset:** IBM HR Analytics Employee Attrition Dataset  
**Domain:** Human Resources Analytics

---

## 📌 Project Overview

This project analyzes employee attrition patterns using the IBM HR Analytics dataset containing 1,470 employee records across 35 variables. The goal is to identify the root causes of employee turnover and provide actionable recommendations to improve retention — using Excel pivot tables, charts, and an interactive dashboard.

---

## 📁 Dataset Details

| Detail | Info |
|--------|------|
| Source | IBM HR Analytics (Kaggle) |
| Total Employees | 1,470 |
| Total Features | 35 |
| Format | CSV |

**Key Variables Used:** Department, Job Role, Monthly Income, Overtime, Job Satisfaction, Years At Company, Salary Band, Attrition

---

## 📈 Dashboard KPIs

| KPI | Value |
|-----|-------|
| Total Employees | 1,470 |
| Overall Attrition Rate | 16.2% |
| Average Monthly Salary | $6,502 |
| Average Job Satisfaction | 2.7 / 4 |
| Attrition Rate (Overtime Employees) | 31% |

---

## 🔍 Key Insights & Analysis

---

### 1. Attrition By Department

**Finding:** Sales department has the highest attrition rate at 20%, closely followed by Human Resources at 19%.

**Insight:** Both Sales and HR departments share common characteristics — lower salary bands and higher overtime frequency. This suggests that compensation and workload are the primary drivers of attrition across the organization, not just isolated to one department.

**Recommendation:** Conduct immediate salary benchmarking for Sales and HR roles and introduce workload management policies to reduce burnout in these departments.

---

### 2. Attrition By Years At Company

**Finding:** Employees with 0-2 years tenure account for approximately 30% of total attrition — the highest among all tenure groups.

**Insight:** New employees are leaving at an alarming rate, suggesting poor onboarding experience, unmet salary expectations, or cultural misfit during the early employment phase.

**Recommendation:** Introduce structured onboarding programs, mentorship for new hires, and performance-linked salary increments in the first two years to improve early retention.

---

### 3. Attrition By Salary Band

**Finding:** Employees in the low salary band have the highest attrition, followed by the medium band. High salary employees show minimal attrition.

**Insight:** Compensation is a primary driver of attrition. Underpaid employees are significantly more likely to leave regardless of other factors.

**Recommendation:** Review and revise salary bands for low and medium income roles, particularly in Sales and HR where attrition is already highest.

---

### 4. Overtime Vs Attrition

**Finding:** 31% of employees who work overtime leave the company, compared to significantly lower attrition among non-overtime employees.

**Insight:** Overtime is a strong predictor of attrition. Employees who are overworked and underpaid are the most likely to leave — combining this with the salary finding paints a clear picture of burnout-driven turnover.

**Recommendation:** Implement overtime caps, compensatory time off, or overtime pay adjustments to reduce burnout and improve retention among high-workload employees.

---

### 5. Job Satisfaction By Department

**Finding:** Employees with a job satisfaction score of 1 (lowest) have the highest attrition rate. Sales department consistently scores the lowest in job satisfaction across all departments.

**Insight:** Low satisfaction combined with low salary and high overtime creates a compounding effect that makes Sales employees significantly more likely to leave.

**Recommendation:** Conduct quarterly employee satisfaction surveys, address grievances proactively, and introduce non-monetary benefits such as flexible working hours and career development programs for Sales employees.

---

### 6. Attrition By Job Role

**Finding:** Laboratory Technician (62), Sales Executive (57), and Research Scientist (47) are the top three job roles with the highest attrition values.

**Insight:** Despite Research Scientist being a technical role, it still appears in the top 3 — suggesting that attrition is not purely a Sales problem but extends to technical roles with low mid-tier salaries.

**Recommendation:** Job-role specific retention strategies are needed rather than a blanket approach. Each high-attrition role requires targeted salary and satisfaction interventions.

---

## 💡 Overall Conclusion

The analysis reveals a clear pattern — **low salary + overtime + low job satisfaction = high attrition.** This is most concentrated in the Sales department but extends across multiple roles and departments. The company is losing its newest and lowest-paid employees at the highest rate, which is the most damaging form of attrition as it increases recruitment costs and reduces organizational knowledge retention.

**Three immediate priorities:**
1. Salary revision for low and medium band employees
2. Onboarding and early retention program for 0-2 year employees
3. Overtime regulation and workload management policies

---

## 🛠️ Excel Skills Used

| Skill | Application |
|-------|-------------|
| Pivot Tables | Summarizing attrition across departments, roles, salary bands |
| Pivot Charts | Visualizing patterns in attrition data |
| Dashboard Design | KPI cards, chart layout, color scheme |
| Data Grouping | Grouping years at company into tenure bands |
| Conditional Formatting | Highlighting high attrition values |
| Excel Formulas | AVERAGE, COUNTIF for KPI calculations |

---

## 📁 Project Structure

```
excel-hr-attrition-analysis/
│
├── README.md
├── HR_Attrition_Analysis.xlsx
└── outputs/
    └── dashboard_screenshot.png
```

---

## 👤 Author

**Deepanshu Kashyap**  
📧 deepanshukashyap531@gmail.com  
📍 Pune, Maharashtra  
🔗 [GitHub](https://github.com/DeepanshuKashyap531)
