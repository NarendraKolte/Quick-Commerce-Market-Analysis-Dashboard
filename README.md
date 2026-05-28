# Quick Commerce Market Analysis Dashboard

## Overview

An end-to-end Power BI dashboard project focused on analyzing the performance of leading quick commerce platforms such as Blinkit, Zepto, Swiggy Instamart, Flipkart Minutes, Dunzo, Big Basket, Amazon Now, and Jio Mart.

This project transforms raw operational and customer data into actionable business insights using Power BI, DAX, Power Query, and interactive visualizations.

---

## Business Problem

Quick commerce companies operate in highly competitive markets where operational efficiency, delivery performance, customer satisfaction, and discount strategies directly impact profitability and growth.

This dashboard helps answer critical business questions such as:

* Which platform generates the highest revenue?
* Which company has the best operational efficiency?
* Do discounts improve sales performance?
* Which cities should companies expand into?
* How do delivery times affect customer experience?

---

## Project Features

### KPI Tracking

* Total Revenue
* Total Orders
* Average Order Value (AOV)
* Average Customer Rating
* Average Delivery Time
* Discount Usage %

### Dashboard Pages

#### 1. Overview Dashboard

* Revenue analysis
* Platform comparison
* KPI monitoring
* Performance summary

#### 2. City Insights

* Revenue by city
* Order distribution
* City ranking analysis
* Expansion opportunity identification

#### 3. Platform Operations

* Delivery efficiency analysis
* Value per KM calculation
* Operational performance benchmarking
* Delivery partner insights

#### 4. Discount Strategy Analysis

* Discount impact on order behavior
* Revenue comparison
* Customer purchasing trends
* Promotional effectiveness tracking

---

## Tools & Technologies Used

* Power BI
* DAX
* Power Query
* Data Modeling
* Excel
* Git & GitHub
* Data Visualization
* Business Intelligence

---

## Key DAX Measures

```DAX
Total Revenue = SUM('Table1 (2)'[Order_Value])

Total Orders = COUNT('Table1 (2)'[Order_ID])

Avg Delivery Time = 
AVERAGE('Table1 (2)'[Delivery_Time_Min])

Discount % = 
DIVIDE(
    COUNTROWS(
        FILTER(
            'Table1 (2)',
            'Table1 (2)'[Discount_Applied] = 1
        )
    ),
    COUNTROWS('Table1 (2)')
)
```

---

## Key Insights

* Swiggy Instamart generated the highest revenue.
* Zepto demonstrated the best operational efficiency.
* Discounts increased basket size more than order volume.
* Gurgaon, Bengaluru, and Mumbai showed strong expansion potential.
* Faster delivery time did not always guarantee higher customer ratings.

---

## Skills Demonstrated

* Data Cleaning & Transformation
* Dashboard Design
* KPI Development
* DAX Calculations
* Business Storytelling
* Operational Analytics
* Interactive Reporting
* Data Visualization

---

## Project Outcome

This dashboard enables data-driven decision-making for:

* Market expansion
* Operational optimization
* Delivery performance improvement
* Customer satisfaction enhancement
* Strategic discount planning

---

## About Me

Aspiring Data Analyst passionate about transforming raw data into meaningful business insights using Power BI, SQL, Excel, and Python.

### Connect With Me

* LinkedIn: https://www.linkedin.com/in/narendra-kolte-9181b02b8/
* GitHub: https://github.com/NarendraKolte
