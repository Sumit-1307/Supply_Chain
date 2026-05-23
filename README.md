# Supply_Chain
Built an interactive Supply Chain Analytics Dashboard using Power BI to analyze sales, profit, shipping performance, delivery status, customer insights, and product trends from a real-world dataset. Used Power Query for data cleaning, DAX for KPI calculations, and created dynamic visualizations to generate meaningful business insights.
# Supply Chain Analytics Dashboard – Power BI Project

## Project Overview

This project is an end-to-end Supply Chain Analytics Dashboard created using Power BI to analyze sales, shipping, customer behavior, delivery performance, and product insights from a global supply chain dataset.

The dashboard helps in understanding how different regions, products, shipping modes, and customer segments impact overall business performance. It transforms raw operational data into meaningful insights through interactive visualizations and KPI tracking.

The dataset contains over 180,000+ records and includes detailed information related to:

* Orders and Sales
* Shipping and Delivery
* Customer Details
* Product Categories
* Profit and Benefit Analysis
* Regional Performance
* Late Delivery Risk
* Shipping Modes and Time Analysis

---

 Tools & Technologies Used

* Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)
* Excel / CSV Dataset
* Data Modeling
* Interactive Dashboard Design

---

 Key Dashboard Features

 Sales & Revenue Analysis

* Total Sales Overview
* Sales Trend by Month and Year
* Region-wise and Country-wise Sales Analysis
* Product Category Performance
* Top Performing Products

 Profit & Order Insights

* Total Profit / Benefit Tracking
* Profit by Product Category
* Order Volume Analysis
* Average Sales Per Customer
* Benefit Per Order Analysis

 Shipping & Delivery Analysis

* Shipping Mode Performance
* Scheduled vs Actual Shipping Days
* Delivery Status Tracking
* Late Delivery Risk Analysis
* Shipping Delay Insights

 Customer Insights

* Customer Segment Analysis
* Top Customers by Sales
* Customer Distribution by Region
* Customer Purchase Patterns

 Product Performance

* Most Ordered Products
* Product Category Analysis
* Product Pricing Insights
* Product-wise Revenue Contribution

---

 KPIs Used in the Dashboard

Some important KPIs created in this project include:

* Total Sales
* Total Orders
* Total Profit
* Average Order Value
* Sales Per Customer
* Previous Month Sales
* Profit Margin %
* Late Delivery %
* Shipping Delay Days
* Order Growth %

---

 Data Cleaning & Transformation

The raw dataset was cleaned and transformed using Power Query.

Main transformation steps:

* Removed null and duplicate values
* Changed incorrect data types
* Created date hierarchy
* Formatted columns for analysis
* Built relationships between tables
* Optimized data model for performance

---

 DAX Measures Used

Some custom DAX measures created:

```DAX
TOTAL SALES = SUM('SUPPLY CHAIN'[Sales])

TOTAL PROFIT = SUM('SUPPLY CHAIN'[Benefit per order])

TOTAL ORDERS = COUNT('SUPPLY CHAIN'[Order Id])

AVERAGE ORDER VALUE = DIVIDE([TOTAL SALES],[TOTAL ORDERS])

Previous Month Sales =
CALCULATE(
    [TOTAL SALES],
    DATEADD('SUPPLY CHAIN'[order date (DateOrders)],-1,MONTH)
)
--------

 Dashboard Objectives

The main goal of this project was to:

* Analyze supply chain operations efficiently
* Identify shipping delays and risks
* Improve decision-making using data insights
* Track business performance using KPIs
* Build an interactive and professional Power BI dashboard

---

## Insights Generated

* Certain shipping modes caused higher late delivery rates.
* Some product categories generated high sales but lower profit margins.
* Specific regions contributed significantly to overall revenue.
* Delivery performance directly affected customer experience.
* Seasonal trends impacted sales and order volume.

---

 Files Included

* `.pbix` Power BI Dashboard File
* CSV Dataset Files
* Dashboard Screenshots
* README Documentation

---

 Project Highlights

* Interactive Power BI Dashboard
* Professional UI Design
* Dynamic Filters & Slicers
* Advanced DAX Calculations
* Business-Focused Insights
* Real-World Supply Chain Dataset

---

Conclusion

This project demonstrates how Power BI can be used to convert large supply chain datasets into meaningful business insights. The dashboard provides a complete overview of operational performance, helping businesses monitor sales, delivery efficiency, customer trends, and profitability in a single interactive report.

---

