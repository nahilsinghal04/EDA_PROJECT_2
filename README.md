# IBM HR Analytics: Attrition Analysis & Insights

**Dataset**: [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

---

## 1. Data Overview & Preprocessing
* **Dataset**: IBM HR Analytics Employee Attrition & Performance dataset
* **Dimensions**: 1,470 rows and 33 features *(after dropping constant columns: `EmployeeCount`, `Over18`, and `StandardHours`)*
* **Data Quality**: **0 missing values** and **0 duplicate rows**
* **Target Variable**: `Attrition_Num` (Binary: `1` for "Yes", `0` for "No")

---

## 2. Analysis & Visualizations Summary

### **Line Chart: Attrition Rate (%) vs. Years at Company**
* **Finding**: The attrition rate is highest among employees during their first year at the company (around **35–40%**). It drops significantly as tenure increases, spiking occasionally at specific long-term milestones (e.g., around 30+ years, likely corresponding to retirement or late-career transitions).

### **Histograms: Key Feature Distributions**
1. **Age Distribution**: Normal-like distribution centered around **30–40 years old**.
2. **Monthly Income Distribution**: Right-skewed distribution; a majority of employees earn **under $5,000/month**, with a few high earners pulling the tail up to $20,000/month.
3. **Distance From Home Distribution**: Heavily right-skewed; most employees live close to the office (**under 10 miles/km**), with fewer employees commuting longer distances.

### **Box Plots: Key Features vs. Attrition**
1. **Monthly Income vs. Attrition**: Employees who left the company (`Yes`) generally had lower median monthly incomes compared to those who stayed (`No`).
2. **Age vs. Attrition**: Younger employees show a higher likelihood of attrition compared to older, more established employees.
3. **Distance From Home vs. Attrition**: Employees who left tended to have a slightly higher median distance from home compared to those who stayed.

---

## 3. Key Insights & HR Takeaways
* **Early Tenure Risk**: Focus retention strategies on onboarding and the first 1–2 years of employment, where turnover risk is highest.
* **Compensation Impact**: Lower monthly income correlates strongly with higher turnover; reviewing compensation bands for entry-to-mid-level roles could reduce attrition.
* **Commute & Age**: Younger employees and those with longer commutes are more prone to leaving. Flexible/hybrid work options or transportation benefits could help mitigate this.
