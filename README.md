# Sales-Dashboard-PowerBi

Project Overview
This project is a beginner-friendly interactive sales dashboard built using Microsoft Power BI. The dashboard provides insights into sales performance, customer count, product categories, and country-wise filtering.

Features
KPI Cards
Total Orders
Total Customers
Total Sales
Interactive Filters
Order Date
Country
Product Category
Visualizations
Sales Trend Analysis
Product-wise Sales
Category-wise Sales Distribution

Tools & Technologies Used

# Sales Dashboard 2026 – Power BI Project

## Project Overview

This project is a beginner-friendly interactive sales dashboard built using Microsoft Power BI.
The dashboard provides insights into sales performance, customer count, product categories, and country-wise filtering.

---

# Dashboard Preview

(Add your dashboard screenshot here)

Example:

```text
images/dashboard.png
```

---

# Features

* KPI Cards

  * Total Orders
  * Total Customers
  * Total Sales

* Interactive Filters

  * Order Date
  * Country
  * Product Category

* Visualizations

  * Sales Trend Analysis
  * Product-wise Sales
  * Category-wise Sales Distribution

---

# Tools & Technologies Used

| Tool             | Purpose                        |
| ---------------- | ------------------------------ |
| Power BI Desktop | Dashboard creation             |
| Power Query      | Data cleaning & transformation |
| DAX              | Calculations & measures        |
| Excel            | Dataset source                 |

---


Dataset Information

The dataset contains:

Customer details
Product information
Sales records
Country data
Order dates

Tables used:
customers
orders

KPIs Used
Total Sales = SUM(orders[sales])

NoOrders = COUNT(orders[order_id])

NoCustomers = DISTINCTCOUNT(customers[customer_id])

Dashboard Insights
Laptop category generated the highest sales.
United States contributed major sales volume.
Sales trends vary across quarters.
Product categories help identify top-performing segments.


Future Improvements
Add profit analysis
Add map visualization
Add customer segmentation
Add forecasting
Add drill-through pages

This Power BI Sales Dashboard project demonstrates basic business intelligence and data visualization skills using Power BI Desktop. The dashboard provides insights into sales trends, customer count, product performance, and category-wise analysis through interactive charts and filters. This project was created for learning and portfolio purposes

