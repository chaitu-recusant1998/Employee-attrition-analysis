# 📊 Employee Attrition Analysis – Initial Findings & Roadmap

> This document presents an initial exploratory analysis of an employee attrition dataset.  
> It highlights key patterns, potential drivers of attrition, and outlines the next steps for deeper investigation and visualization.

---

## 🛠️ Project Steps

1. **Cleaned the dataset using Microsoft Excel**  
   - Removed duplicates, handled missing values, and standardized formatting.

2. **Performed exploratory data analysis (EDA) in Excel**  
   - Used pivot tables, charts, and filters to summarize key metrics and trends.

3. **Documented key findings and hypotheses**  
   - Focused on attrition factors like age, income, gender, satisfaction, and travel.

4. **Designed a wireframe layout for Power BI dashboard**  
   - Included KPI cards, bar charts, donut charts, and slicers for dynamic filtering.

5. **Built an interactive Power BI dashboard**  
   - Visualized attrition insights using slicers, filters, and drill-down features.

6. **Compiled structured observations and patterns**  
   - Grouped insights by demographics, compensation, and satisfaction.

7. **Outlined next steps for deeper analytics**  
   - Identified advanced metrics and modeling directions to explore.

---

## 📈 Key Insights from Initial Analysis

### ✅ Overall Attrition Rate:
- **16%** of total employees have left the organization.

### ✅ Attrition by Age Group:
- Of those who left, **8% are aged 30–50**, suggesting middle-age retention challenges.

### ✅ Business Travel Frequency:
- **70%** of employees rarely travel for business.  
  *Hypothesis:* Business travel may not influence attrition significantly (needs testing).

### ✅ Attrition by Department:
- The **R&D department** has the most employees and the highest attrition count, likely due to its size.

### ✅ Distance from Home:
- **42.99%** of employees live within a 5-mile radius.  
  However, those living **5–15 miles away** show higher attrition—needs further analysis.

### ✅ Education Level and Attrition:
- Majority hold **Bachelor’s degrees**, followed by **Masters** and **College** grads.  
  Doctorate holders are the fewest, and attrition follows this same order.

### ✅ Monthly Income by Education:
- **Doctorate > Masters > Bachelors > College** in terms of average monthly income.

### ✅ Hike Percentile and Performance Rating:
- Minimal differences across education levels, suggesting limited impact on attrition.

---

## 🔍 Noteworthy Patterns & Hypotheses

### 🟠 Environment Satisfaction:
- **Lower environment satisfaction → higher attrition.**  
  A major factor to investigate further.

### 🟠 Income + Environment Satisfaction:
- **Low satisfaction + high income → employees stay.**  
  **Low satisfaction + low income → employees leave.**

### 🟠 Job Satisfaction + Income:
- Employees with **high job satisfaction** but **low income** still left, suggesting salary outweighs satisfaction in some cases.

### 🟠 Income as a Retention Factor:
- Points 9–11 confirm **monthly income plays a critical role**, especially when satisfaction is low.

### 🟠 Gender-Based Insights:
- **Female employees** have higher average monthly income.  
  However, **male employees** show higher attrition rates.

### 🟠 Job Level Satisfaction:
- Employees with **low job level satisfaction** leave the most.

### 🟠 Demographic Patterns:
- **18–30 single employees** have the highest attrition, followed by married and middle-aged singles.  
  Even **middle-aged married employees** show noticeable attrition levels.

---

## 🔄 What’s Next?

### 🧩 To-Do List:

- 🔍 Analyze remaining columns:
  - Overtime
  - Years at company
  - Promotion history
  - Work-life balance
  - Training time

- 🧪 Validate current hypotheses:
  - Use correlation analysis and statistical tests.

- 📊 Build Power BI Dashboard:
  - Based on the wireframe layout already designed.
  - Include filters, tooltips, slicers, and drill-downs.

- 🧠 Group Analysis Dimensions:
  - **Satisfaction**: job, environment, relationship
  - **Compensation**: income, hike %, job level
  - **Demographics**: age, gender, marital status, education
  - **Logistics**: commute, travel frequency

- 📐 Develop Derived Metrics:
  - Attrition Risk Score
  - Employee Retention Index
  - Weighted Satisfaction Score

- ❓ Start Asking Strategic Questions:
  - What combination of features most strongly predicts attrition?
  - Can we cluster high-risk employee groups?
  - What’s the potential impact of increasing salary or offering commute support?

---

## 📁 Files in This Repository

- `employee_attrition_analysis.xlsx` – Cleaned dataset and initial EDA
- `powerbi_dashboard.pbix` – Interactive dashboard
- `attrition_wireframe.png` – Wireframe design layout
- `README.md` – Project overview and next steps

---

Feel free to ⭐ this repo if you found it helpful or fork it to explore deeper insights!


