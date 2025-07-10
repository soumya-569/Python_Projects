# ☕ Coffee Shop Sales Analysis — EDA in Python

This project analyzes transactional data from a chain of coffee shops using Python. It dives deep into customer purchase behavior, revenue trends, product category performance, and store-wise performance metrics. The analysis helps uncover patterns that can guide business strategy for sales growth and operational optimization.

---

## 📌 Objective

- Understand which products and categories are performing best.
- Identify **peak hours**, **revenue patterns**, and **seasonal trends**.
- Evaluate **store performance**, **customer preferences**, and **sales patterns**.
- Apply **Pareto analysis**, **week-on-week** and **month-on-month growth metrics** to derive actionable insights.

---

## 📁 Dataset Overview

- Fields include:
  - `transaction_id`, `transaction_date`, `transaction_time`, `store_location`, `product_id`, `product_type`, `product_category`, `unit_price`, `transaction_qty`
- The dataset simulates real-world coffee shop transactions across different stores and product categories.

---

## 🛠️ Tools & Libraries Used

- **Pandas** – For data wrangling
- **NumPy** – For numerical analysis
- **Matplotlib & Seaborn** – For plotting insights and trends

---

## 🧠 Business Questions Answered

1. What are the **top 5 best-selling products**?
2. Which store **generated the most revenue**?
3. How does **monthly revenue trend** look?
4. What are the **top product categories** per store?
5. Which **hour of the day** sees the highest sales?
6. What is the **average transaction size** by store?
7. What is the **sales distribution** between weekdays and weekends?
8. Which products contribute to **80% of total revenue** (Pareto analysis)?
9. What are the **seasonal patterns** in sales?
10. How does **product pricing vary** across types?

---

## 📊 Key Insights & Findings

- **Best-Selling Products**: Specific items dominate total sales by quantity.
- **Top Stores**: One or more store locations consistently bring in the highest revenue.
- **Revenue Trends**:
  - Monthly trends reveal **seasonality**, with peaks in specific months.
  - Week-over-week and month-over-month trends help track growth over time.
- **Category Analysis**:
  - Top 3 product categories per store highlight local preferences.
  - Product category contribution to total revenue shows that a few categories drive the majority of income.
- **Time-based Trends**:
  - Peak sales occur during **morning and early evening hours**.
  - **Weekends** generate significantly more sales in some stores.
- **Pareto Analysis**: A small set of products (~20%) contribute to ~80% of total revenue.
- **Seasonal Performance**: Sales are highest in **summer** months, suggesting opportunities for seasonal promotions.
- **Slow Sellers**: Identification of products generating the least revenue aids in inventory optimization.

---

## 📈 Visuals Included

- Bar plots for best-selling products
- Line graphs for monthly & weekly revenue trends
- Heatmaps for hourly store sales
- Pareto chart showing top revenue-driving products
- Pie charts for category-wise contributions

---
