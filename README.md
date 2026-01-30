# Kultra Mega Stores SQL Capstone Project
A SQL‑driven data analysis case study of inventory, sales, and shipping performance for Kultra Mega Stores (2009–2012), uncovering actionable insights to improve revenue, customer value, and logistics decisions.


## Table of Contents
1. [Project Summary](#project-summary)
2. [Dataset Description](#dataset-description)
3. [Business Context](#business-context)
4. [Dataset & Tools](#dataset--tools)
5. [Key Insights & SQL Techniques](#key-insights--sql-techniques)
6. [How to Explore This Project](#how-to-explore-this-project)
7. [Limitations & Future Work](#limitations--future-work)

---

## Project Summary 
This project analyzes historical sales, customer, and shipping data to identify patterns, trends, and areas of improvement for a fictional retail company. Using SQL queries, aggregation, and joins, actionable insights were generated to support strategic decisions in inventory management, customer targeting, and logistics optimization.

**Skills & Tools:**  
- SQL querying (`JOIN`, `GROUP BY`, `ORDER BY`, aggregation functions)  
- Data analysis and interpretation  
- Microsoft Excel (data inspection & visualization)  
- Documentation and reporting  

---

## Dataset Description
- Time period: 2009–2012
- Data includes:
  - Orders
  - Customers
  - Products
  - Shipping details



---

## Business Context
Kultra Mega Stores wanted to understand their sales performance, customer behavior, and shipping efficiency over the period 2009–2012. The goal of this case study is to provide insights that help:  
- Improve inventory management  
- Identify top-performing products and regions  
- Optimize customer engagement and shipping processes

---

## Dataset & Tools
**Dataset:**  
- **Data Categories:** Orders, Customers, Shipping Details, Products  
- **Period:** 2009–2012  
- **Source:** DSA Capstone project files  

**Tools Used:**  
- SQL Server (querying & aggregation)  
- Microsoft Excel (preliminary inspection & charts)  
- GitHub (project hosting & documentation)

---

## Key Insights & SQL Techniques

| Insight | SQL Technique | Result |
|--------|---------------|--------|
| Highest sales by product category | `GROUP BY` + `ORDER BY DESC` | Technology category dominated sales |
| Top-performing regions | Aggregation + ranking | Identified top 3 regions for sales, bottom 3 regions for improvement |
| Customer order behavior | `JOIN` + filtering | Repeat customers contributed 40% of total revenue |
| Shipping efficiency | Aggregation & calculated fields | Found delays mainly in Northern regions |

*Visuals and charts included in the `images/` folder.*

---

## How to Explore This Project

1. Clone the repository:  
```bash
[git clone https://github.com/Tohby823/kultra-mega-stores-sql.git ](https://github.com/Tohby823/kultra-mega-store-sql/blob/main/README.md)
```
2. Open README.md for documentation
3. Explore SQL scripts in the `sql/ ` folder
4. View any charts or tables in the `images/` folder
5. Run queries in SQL Server to reproduce findings

---

## Limitations & Future Work
1. Dataset only spans 2009–2012, so insights may not reflect current trends
2. Some shipping and logistics data were unavailable, limiting analysis
3. Dataset regions are fictional and may not correspond to real locations
4. Future work: integrate with Power BI/Tableau dashboards for interactive visualization and predictive analytics

---

sql/
