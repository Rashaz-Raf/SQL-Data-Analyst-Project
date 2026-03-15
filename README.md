# 🧠 Advanced Data Analytics

This project delivers a full-stack **data analytics solution** using SQL to perform **Advanced Trend & KPI Analysis**, and **Insightful Reporting** on a sales dataset.

It is structured for modular development, enabling seamless database initialization, analytical processing, and report generation using clean SQL workflows.

---

## 📦 Dataset Overview

The dataset is structured into a **star schema**:

- `gold.dim_customers.csv` – Customer details (demographics, IDs)
- `gold.dim_products.csv` – Product details (categories, pricing)
- `gold.fact_sales.csv` – Sales transactions (orders, dates, revenue)

---


### 📈 Advanced Analytics

Key Modules:

- change_over_time_analysis.sql – Monthly & yearly sales trends

- cumulative_analysis.sql – Rolling totals and moving averages

- perfomance_analysis.sql – Year-over-year comparisons

- part_to_whole_analysis.sql – Category contribution to total sales

- data_segmentation.sql – Cost-based product segmentation, customer lifecycle grouping

---

## 📋 Reports


### 🧑 Customer Report (customer_report.sql)
Creates the view: gold.report_customers

Metrics & KPIs:

- Age, age group, customer segment (VIP, Regular, New)

- Total orders, sales, quantity, lifespan, recency

- Avg. order value and monthly spend

---

### 📦 Product Report (product_report.sql)
Creates the view: gold.report_products

Metrics & KPIs:

- Category, subcategory, segment (High/Mid/Low performer)

- Total orders, quantity, customers

- Avg. selling price, avg. order revenue, monthly revenue

---
