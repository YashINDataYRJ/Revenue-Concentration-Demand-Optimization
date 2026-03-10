# 🍕 Revenue Concentration & Demand Optimization

**SQL + Power BI portfolio project** analyzing **21,350 pizza orders** to identify revenue drivers, demand patterns, and operational insights.

**Tools:** SQL • MySQL • Power BI  
**Techniques:** Aggregations • Joins • Subqueries • Window Functions • Star Schema  

🔗 **LinkedIn:** https://linkedin.com/in/yashraj33  
💻 **GitHub:** https://github.com/YashINDataYRJ

---

## Project Overview

- Analyzed Pizza Hut’s 2015 transaction dataset using **SQL and Power BI**.
- Explored **sales performance, demand patterns, and product revenue drivers**.
- Implemented **12 SQL queries** ranging from **basic aggregations to advanced window functions**.
- Built a **Power BI dashboard** to visualize KPIs and business insights.

---

## Dataset

- **orders** — order date and time  
- **order_details** — individual items within each order  
- **pizzas** — pizza size and price  
- **pizza_types** — pizza names, categories, and ingredients  

---

## Data Schema

- **pizza_types → pizzas** (linked by `pizza_type_id`)
- **pizzas → order_details** (linked by `pizza_id`)
- **orders → order_details** (linked by `order_id`)
- **order_details** acts as the **central fact table** connecting orders with pizza attributes.

---

## Key Metrics

- **Total Revenue:** $147,140  
- **Total Orders:** 21,350  
- **Total Pizzas Sold:** 49,574  
- **Average Daily Orders:** 138  
- **Peak Hour:** 12:00–13:00  
- **Top Pizza:** Thai Chicken Pizza  
- **Top Category:** Classic  

---

## SQL Skills Demonstrated

**Basic**
- `COUNT()`
- `SUM()`
- `GROUP BY`
- `ORDER BY`

**Intermediate**
- Multi-table `JOIN`
- Subqueries
- Time-based aggregation

**Advanced**
- Window functions (`SUM() OVER`)
- Ranking (`RANK() OVER`)
- Revenue contribution calculations

---

## Key Insights

- **Lunch hours (12–13)** generate the highest order volume.
- **Evening window (17–19)** is the second peak demand period.
- **Large pizzas dominate sales**, representing the largest share of orders.
- Revenue distribution across categories is **balanced**, reducing dependency on a single category.

---

## Business Recommendations

- Increase staffing during **lunch and evening peak hours**.
- Introduce **premium chicken-based pizzas** to increase average order value.
- Focus promotions around **Large pizza sizes**.
- Consider removing **low-demand XXL pizzas** to simplify operations.

---

## Repository Structure


- **dashboard/**
  - `PizzaHut_Sales_Dashboard.jpg`

- **docs/**
  - Project Explanation
  - Domain Knowledge
  - Dashboard Insights
  - Business Requirements

---

## Tools & Skills

- SQL  
- MySQL  
- Power BI  
- Data Analysis  
- Data Visualization  
- Star Schema Modeling  

---

## Author

**Yash Raj**

- LinkedIn: https://linkedin.com/in/yashraj33  
- GitHub: https://github.com/YashINDataYRJ  

⭐ Built as a **portfolio project to demonstrate SQL analytics and business insight generation.**
