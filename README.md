# Consumer-Goods-Analysis
This SQL project analyzes Atliq Hardware’s consumer goods data to solve 10 real-world business questions. It covers sales trends, product performance, and customer insights using JOINS, CTEs, aggregation, and window functions. Built for the Codebasics Resume Project Challenge.

---

## 📌 Project Objective

To answer 10 real-world business questions using SQL by analyzing sales, manufacturing costs, discounts, and customer behavior. The goal is to derive meaningful insights that help stakeholders make data-driven decisions.

---

## 🧮 Dataset Overview

The data belongs to a fictional consumer goods company, **Atliq Hardware**, with 6 tables:

| Table                    | Description                                       |
|-------------------------|---------------------------------------------------|
| `dim_customer`          | Customer profiles, region, market, platform      |
| `dim_product`           | Product details with category & segment info     |
| `fact_sales_monthly`    | Monthly sales performance                        |
| `fact_gross_price`      | Gross selling price by product and fiscal year   |
| `fact_manufacturing_cost` | Production costs by year                        |
| `fact_pre_invoice_deductions` | Discounts before invoicing               |

---

## 📊 Business Questions Solved

| No. | Request Summary                                              | SQL Technique |
|-----|--------------------------------------------------------------|---------------|
| 1   | Markets where "Atliq Exclusive" operates in APAC             | `DISTINCT`, `WHERE` |
| 2   | % increase in unique products from 2020 to 2021              | `COUNT`, `CTE`, `CROSS JOIN` |
| 3   | Product count by segment                                     | `GROUP BY`, `ORDER BY` |
| 4   | Segment with most unique product growth (2020 → 2021)        | `JOIN`, `COUNT`, `CTE` |
| 5   | Products with highest/lowest manufacturing cost              | `MIN`, `MAX`, `JOIN`, `Subquery` |
| 6   | Top 5 customers with highest avg. pre-invoice discount (2021, India) | `AVG`, `GROUP BY`, `JOIN` |
| 7   | Monthly gross sales for "Atliq Exclusive"                    | `SUM`, `JOIN`, `GROUP BY`, `ROUND` |
| 8   | Quarter with highest quantity sold in 2020                   | `CASE`, `SUM`, `GROUP BY` |
| 9   | Channel with highest gross sales in 2021                     | `JOIN`, `SUM`, `ROUND` |
| 10  | Top 3 selling products in each division (2021)               | `RANK()`, `PARTITION BY` |

---

## 🛠️ Skills & Concepts Used

- Joins (INNER, LEFT)
- Aggregation: `SUM`, `COUNT`, `AVG`, `MIN`, `MAX`
- CTEs and Subqueries
- Window Functions: `RANK()`, `ROW_NUMBER()`
- CASE-WHEN Logic
- Date/Time operations
- Performance optimization for large queries

---

## Ad-Hoc Requests & Outputs

1. Provide the list of markets in which customer "Atliq Exclusive" operates its business in the APAC region

   ![Request 1 Output](![image](https://github.com/user-attachments/assets/069d9b5d-03b1-42fd-85b4-17f9d57c9818)
)

---

## 🧑‍💻 Author

**Sarthak More**  
💼 Aspiring Data Analyst | 📊 SQL • Power BI • Excel  
🔗 [LinkedIn](https://www.linkedin.com/in/sarthak-more-8812b6213)  
🔗 [GitHub](https://github.com/Sarthak18-DA)

---

## 📝 Acknowledgements

Special thanks to [Dhaval Patel](https://www.linkedin.com/in/dhavalsays/) and the [Codebasics](https://www.codebasics.io/) team for providing this amazing challenge.

---

## 📽️ Bonus (Optional)

🔗 [Presentation Video](#) – Explaining how I solved each business problem using SQL.  
🔗 [LinkedIn Post](#) – About my experience solving this challenge.

