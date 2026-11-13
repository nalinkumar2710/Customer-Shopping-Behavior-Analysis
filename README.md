# Customer Shopping Behavior & Revenue Analytics

![SQL](https://img.shields.io/badge/SQL-MySQL-1F4E79?style=flat&logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-DAX_&_KPI_Dashboards-F2C811?style=flat&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-Pandas_|_NumPy_|_Seaborn-3776AB?style=flat&logo=python&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-Data_Validation-217346?style=flat&logo=microsoft-excel&logoColor=white)

## 📌 Business Problem & Objective
Retail and e-commerce businesses often struggle to identify which customer segments, promotional discounts, and shipping channels drive sustainable revenue versus margin erosion. 

This end-to-end analytics project analyzes **3,900+ retail transaction records** across product categories, customer demographics, subscription tiers, and payment channels to answer core business questions:
1. How do **New, Returning, and Loyal** customer cohorts differ in Average Order Value (AOV) and total revenue contribution?
2. Do promotional discounts and subscription programs increase overall customer spend?
3. Which product categories and shipping channels deliver the highest revenue and customer satisfaction ratings?

---

## 📊 Power BI KPI Dashboard
![Power BI Dashboard](images/dashboard.png)
---

## 🛠️ Tech Stack & Workflow
* **Python (`Customer_Shopping_Behavior_Analysis.ipynb`):** Cleaned 3,900+ retail transaction records using Pandas, imputed missing review ratings, standardized column schemas, and performed exploratory data analysis (EDA).
* **SQL (`customer_behavior_sql_queries.sql`):** Wrote SQL queries using Joins, CTEs, CASE statements, and Window Functions (`DENSE_RANK`) to segment New, Returning, and Loyal customer cohorts and evaluate revenue drivers.
* **Power BI (`customer_behavior_dashboard.pbix`):** Built an interactive KPI dashboard with custom DAX measures tracking Average Order Value (AOV), Total Revenue, Average Review Rating, Subscriber Split, and Category Revenue.

---

## 🔍 Key Insights & Business Recommendations
* **Customer Cohort Segmentation:** **Loyal customers** drive the largest share of repeat revenue, while **Returning buyers** show high upsell potential when targeted with personalized offers.
* **Subscriber vs. Non-Subscriber Spend:** Active subscribers maintain steady order frequency, whereas non-subscribers rely heavily on promotional discounts to convert.
* **Category Performance:** **Clothing** and **Accessories** lead transaction volume and revenue across age brackets, followed by **Footwear** and **Outerwear**.
* **Actionable Strategy:** Introduce checkout loyalty prompts for Returning buyers (3–5 purchases), replace blanket discounts on high-margin Accessories with minimum-spend bundles, and prioritize Express/Standard shipping incentives.

---

## 📂 Project Files in This Repository
* `Business Problem Document.pdf` — Formal business problem framing and stakeholder requirements.
* `customer_shopping_behavior.csv` — Raw retail transaction dataset (3,900+ rows).
* `Customer_Shopping_Behavior_Analysis.ipynb` — Python data cleaning, preprocessing, and EDA notebook.
* `customer_behavior_sql_queries.sql` — SQL scripts for customer segmentation, discount analysis, and product ranking.
* `customer_behavior_dashboard.pbix` — Interactive Power BI dashboard file.
* `Customer Shopping Behavior Analysis.pdf` & `.pptx` — Executive summary report and stakeholder presentation deck.

---

## 👤 Author
**Adepu Nalin Kumar**  
[LinkedIn](https://www.linkedin.com/in/nalinkumar27) | [GitHub](https://github.com/nalinkumar2710)