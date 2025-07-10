# 🏦 ICICI Bank Customer Churn Analysis — EDA in Python

This project aims to analyze **customer churn behavior** for ICICI Bank using Python. By performing **exploratory data analysis (EDA)**, we identify the key factors that influence whether a customer is likely to exit (churn) and derive valuable insights that can guide **retention strategies**.

---

## 📌 Objective

- Analyze **demographics, account features, and behavior** to uncover churn patterns.
- Identify **at-risk customer segments** based on tenure, balance, geography, and more.
- Calculate **churn rates** and **correlations** to understand what drives customer attrition.

---

## 📁 Dataset Overview

- Each row represents a **bank customer** with columns like:
  - `CustomerID`, `CreditScore`, `Geography`, `Gender`, `Age`, `Tenure`, `Balance`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`, `EstimatedSalary`, `Exited` (target)
- The target column `Exited` shows whether the customer churned (1) or not (0)

---

## 🛠️ Tools & Libraries Used

- **Pandas** – Data manipulation
- **NumPy** – Statistical calculations
- **Matplotlib & Seaborn** – Visual analysis

---

## 🧠 Key Business Questions Solved

1. What is the **overall churn rate**?
2. How does churn vary by **age group, gender, and geography**?
3. What is the **impact of tenure** on churn?
4. What percentage of churned users had a **credit card**?
5. How do churned customers compare in terms of **average balance and salary**?
6. Are customers with more products **less likely to churn**?
7. Is there a **correlation between credit score and churn rate**?
8. Which **salary ranges** show higher churn rates?
9. Are longer-tenured customers more **loyal**?

---

## 📊 Notable Insights & Findings

- The **overall churn rate** is approximately **20%**.
- **Female customers** churned at a slightly higher rate than males.
- Customers aged **30–50** showed **higher churn** than younger or older segments.
- **France** had the highest churn rate among all regions.
- Surprisingly, many churned customers **did have a credit card**, indicating it isn’t a strong retention factor.
- **Tenure** showed a non-linear relation: customers with **medium tenure (4–6 years)** churned more often.
- Churners had a **higher average balance**, indicating loss of high-value clients.
- There is **no strong correlation** between credit score and churn.
- Customers with **fewer products** tend to churn more — opportunity for **cross-selling**.
- **Higher income customers** were also seen in churn group — they might be leaving for better investment options.

---

## 📈 Visualizations Used

- Bar charts comparing churn by gender, region, tenure
- Histograms of age and salary distribution among churned customers
- Correlation heatmaps for numerical features
- Pie charts for product/service usage analysis

---


