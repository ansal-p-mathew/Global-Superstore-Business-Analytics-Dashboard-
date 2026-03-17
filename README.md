# Global Superstore Analytics Dashboard

## Overview

This project presents an interactive Power BI dashboard built using the Global Superstore dataset.
It provides insights into sales performance, profitability, and customer behavior through structured data modeling, DAX measures, and intuitive visual design.

The dashboard follows a multi-page layout with interactive filtering and navigation to support efficient data exploration.

---

## Objectives

* Analyze sales and profit performance across regions and categories
* Identify top-performing customers, products, and states
* Track year-over-year (YoY) growth trends
* Enable interactive analysis using filters and slicers

---

## Tools and Technologies

* Power BI Desktop
* DAX (Data Analysis Expressions)
* Data Modeling (Date Table, Relationships)
* Global Superstore Dataset (CSV/Excel)

---

## Dashboard Structure

### Sales Analysis

* Total Sales, Current Year Sales, Previous Year Sales
* Year-over-Year Growth (%)
* Sales trend over time
* Sales by category and segment
* Top 5 products by sales

### Profit Analysis

* Total Profit, Current Year Profit, Previous Year Profit
* YoY Profit Growth (%)
* Profit by category and sub-category
* Top 5 profitable products
* Profit trend (CY vs PY)

### Customer Demographics

* Top 10 active customers (by quantity)
* Top 10 valuable customers (by profit)
* Top 5 profitable states
* Profit distribution by ship mode
* Sales and profit comparison by region

---

## Key Features

* Multi-page dashboard design
* Bookmark-based filter panel with toggle functionality
* Top-N filtering for focused insights
* Time intelligence using DAX (YoY, Previous Year)
* KPI cards for quick performance monitoring
* Consistent visual theme and layout

---

## Data Modeling

* Created a dedicated Date Table using DAX
* Established relationships between tables
* Used measures for calculations instead of calculated columns
* Enabled time-based analysis using SAMEPERIODLASTYEAR

---
## Screenshots

### Sales Dashboard

![Sales Dashboard](images/sales.png)

### Profit Dashboard

![Profit Dashboard](images/profit.png)

### Demographics Dashboard

![Demographics Dashboard](images/demographics.png)

---

## Insights

* A small group of customers contributes significantly to overall revenue
* Sales and profit vary considerably across regions
* Certain product categories generate high sales but lower profit margins
* Seasonal trends impact sales performance across years

---

## How to Use

1. Open the `.pbix` file in Power BI Desktop
2. Use the filter panel to refine analysis
3. Navigate between pages using the navigation buttons
4. Interact with visuals for deeper insights

---

## Future Enhancements

* Add forecasting models
* Implement row-level security
* Improve mobile layout optimization
* Integrate real-time data sources

---

## Contact

For queries or collaboration, feel free to connect via LinkedIn or GitHub.
