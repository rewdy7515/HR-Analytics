# HR-Analytics

**HR Analytics: Employee Turnover Prediction at Salifort Motors**

This project uses machine learning and data analysis to predict employee resignations based on internal HR data. The main objective is to help Salifort Motors reduce turnover and retain top talent by identifying key risk factors.

📄 [Read the full report (PDF)](report/Hr_Analytics_Report.pdf)

---

## 📊 Overview

- **Dataset:** 14,999 employee records
- **Features used:**
  - Satisfaction level
  - Performance evaluation
  - Number of projects
  - Monthly hours worked
  - Time at the company
  - Work accidents
  - Promotions in last 5 years
  - Department, Salary, and Turnover

---

## 📈 Model Results

- ✅ **Recall:** 92% — catches most employees who actually resign
- ✅ **Precision:** 98.9% — very few false positives
- ✅ **AUC Score:** 0.96 — excellent separation between leavers and stayers

---

## 🧠 Insights

- Employees with very low or very high workloads are more likely to leave.
- Low satisfaction + high hours worked = high resignation risk.
- Most resignations happen within the first 2–3 years.
- Promotions and salary growth are key to retention.

---

## 🛠️ Tools & Technologies

- Python (Pandas, Matplotlib, Scikit-learn)
- Random Forest Classifier
- Jupyter Notebooks

---

## ✅ Recommendations

- Use the trained model as an early warning system in HR.
- Optimize workload to 3–5 projects per employee.
- Invest in salary/promotion plans within the first 2–4 years.
