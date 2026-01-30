# ☕ Coffee Shop Sales Dashboard (Power BI)

## Overview
This project is an interactive Power BI dashboard developed to analyze coffee shop sales performance across time, products, and store locations.
The dashboard enables monitoring of key KPIs and identifying sales trends using dynamic visuals and DAX measures.

All data preparation, modeling, and calculations were performed inside Power BI.

---

## Dataset
- Format: CSV / Excel
- Type: Transaction-level sales data
- Fields include:
  - Transaction date and time
  - Product category and product type
  - Store location
  - Unit price and quantity sold
  - Transaction ID

Raw data was used without external cleaning.

---

## Tools Used
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- Excel / CSV

---

## Data Modeling
- Custom Date Table created using DAX
- Relationship established between Date and Transactions tables
- Calculated columns created for:
  - Month, Month-Year
  - Day name and weekday/weekend
  - Hour
- Time intelligence implemented for month-over-month analysis

---

## Measures Implemented
- Total Sales
- Total Orders
- Total Quantity Sold
- Current Month (CM) metrics
- Previous Month (PM) metrics
- Month-over-Month (MoM) growth and difference
- Daily Average Sales
- Dynamic labels and tooltip measures

---

## Dashboard Visuals

### KPI Cards
- Total Sales
- Total Orders
- Total Quantity Sold
Each KPI displays:
- MoM percentage change
- Difference vs last month
- Trend line

---

### Time-Based Analysis
- Daily sales trend with average reference line
- Sales by Day and Hour matrix with conditional formatting
- Custom calendar visual with tooltip interaction

---

### Product Analysis
- Sales by Product Category (clustered bar chart)
- Sales by Product Type (clustered bar chart)

---

### Store Analysis
- Sales by Store Location
- Month-over-Month comparison by store

---

### Behavioral Insights
- Weekday vs Weekend sales distribution using donut chart

---

## Interactivity
- Month slicer
- Cross-filtering across visuals
- Custom tooltip pages
- Conditional formatting driven by measures

---

## Project Structure
coffee-shop-sales-dashboard/
│
├── Coffee_Shop_Sales_Dashboard.pbix
├── Coffee_Shop_Sales.csv
└── README.md

---

## Purpose
This project demonstrates practical Power BI, DAX, and data modeling skills suitable for data analyst and business intelligence roles.
