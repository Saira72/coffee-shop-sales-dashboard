☕ Coffee Shop Sales Dashboard | Power BI

Overview

This project is an interactive Power BI dashboard built to analyze coffee shop sales performance across time, products, and store locations.

All data preparation, modeling, and calculations were done within Power BI using DAX and Power Query.

##Dataset

Format: CSV / Excel

Data type: Transactional sales data

Contains:

Transaction date & time

Product category & product type

Store location

Quantity sold & unit price

Transaction ID

Raw data was used; no external data cleaning was performed.

#Tools Used

Power BI Desktop

DAX

Power Query

Excel / CSV

##Data Modeling

Custom Date Table created using DAX

Relationships established between Date and Transactions tables

Calculated columns for:

Month, Month-Year

Day name, weekday/weekend

Hour

Time intelligence implemented for MoM analysis

##Key Measures

Total Sales

Total Orders

Total Quantity Sold

Current Month (CM) metrics

Previous Month (PM) metrics

Month-over-Month (MoM) growth & difference

Daily Average Sales

Dynamic labels and tooltip measures

##Dashboard Visuals

KPIs

Total Sales

Total Orders

Total Quantity Sold

Each KPI includes:

MoM % change

Difference vs last month

Trend line

##Time Analysis

Daily sales trend with average reference line

Sales by Day & Hour matrix with conditional formatting

Custom calendar visual with hover interaction

##Product Analysis

Sales by Product Category (clustered bar chart)

Sales by Product Type (clustered bar chart)

##Store Analysis

Sales by Store Location

Month-over-Month comparison

##Behavioral Insights

Weekday vs Weekend sales distribution (donut chart)

##Interactivity

Month slicer

Cross-filtering across visuals

Custom tooltip pages

Conditional formatting driven by measures

##Project Structure

Coffee-Shop-Sales-PowerBI/
│
├── Coffee_Shop_Sales.csv

├── Coffee_Shop_Sales.pbix

└── README.md

##Purpose

This project showcases practical Power BI, DAX, and data modeling skills for data analytics and business intelligence roles.
