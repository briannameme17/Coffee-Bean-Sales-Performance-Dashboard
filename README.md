# Coffee Bean Sales Performance Dashboard

## Project Overview

This project is an Excel based sales performance dashboard analyzing coffee bean sales across time, geography, customers, and product attributes. The dashboard is designed to deliver clear business insights through structured data analysis and interactive visualization.

The project demonstrates core data analytics skills including data preparation, relational modeling, KPI development, and dashboard creation using Microsoft Excel.

---

## Business Objective

The objective of this dashboard is to analyze coffee bean sales performance and answer key business questions:

Which coffee bean types generate the highest revenue  
How sales performance changes over time  
Which countries contribute most to total sales  
Which customers generate the highest sales value  
How roast type, package size, and loyalty status influence performance  

The dashboard enables users to explore sales data interactively and support data driven decision making.

---

## Dataset Structure

The dataset is organized into multiple related tables that reflect a real world sales environment.

### Orders Table

Contains transactional sales data including product ID, quantity, unit price, total sales, coffee type, roast type, size, country, and order date.

### Customers Table

Contains customer ID, customer name, email, phone number, address, city, country, postcode, and loyalty card status.

### Products Table

Contains product attributes including coffee type, roast type, size, unit price, price per 100g, and profit calculations.

---

## Data Preparation and Modeling

### Step 1 Data Cleaning and Standardization

Reviewed all tables for formatting consistency  
Standardized date, numeric, and currency fields  
Ensured consistent naming for coffee types, roast types, and countries  
Validated data integrity across tables  

### Step 2 Feature Engineering

Calculated total sales using quantity multiplied by unit price  
Created price per 100g to allow fair comparison across package sizes  
Calculated profit values to support margin analysis  
Extracted year and month from order date for time based analysis  

### Step 3 Data Relationships

Linked orders table to customers table using customer ID  
Linked orders table to products table using product ID  
Structured the data model to support PivotTables and dashboard filtering  

---

## Pivot Tables and Aggregations

PivotTables were created to aggregate and summarize sales data for analysis and visualization.

Monthly sales by coffee type  
Sales totals by country  
Top five customers by total sales  
Sales distribution by roast type and size  

### Monthly Sales Pivot Table

![Monthly Sales Pivot Table](images/excel-3.jpg)

This PivotTable aggregates total sales by year, month, and coffee type and serves as the data source for the sales trend visualization.

---

## Dashboard Design

The dashboard was designed with usability and clarity in mind, allowing business users to explore data without modifying underlying tables.

### Interactive Dashboard

![Coffee Sales Dashboard](images/excel-2.jpg)

Slicers allow filtering by roast type, package size, loyalty card status, and date range. All charts update dynamically based on selections.

---

## Key Visualizations

### Total Sales Over Time

![Total Sales Over Time](images/excel-2.jpg)

This line chart displays monthly sales trends by coffee type, allowing comparison of Arabica, Excelsa, Liberica, and Robusta performance.

### Sales by Country

![Sales by Country](images/excel-6.jpg)

This chart highlights revenue distribution across the United States, Ireland, and the United Kingdom.

### Top Five Customers

![Top Five Customers](images/excel-7.jpg)

This visualization identifies the highest value customers based on total sales.

---

## Product and Profit Analysis

### Product Pricing and Profit Table

![Product Pricing and Profit Table](images/excel-8.jpg)

This table provides insight into product pricing, price per 100g, and profit to support margin and pricing analysis.

---

## Customer Data Overview

### Customer Master Table

![Customer Table](images/excel-1.jpg)

The customer table supports geographic analysis, loyalty segmentation, and customer value insights.

---

## Business Insights

Sales are primarily driven by the United States market  
Arabica and Excelsa generate strong revenue across multiple periods  
Loyalty card customers frequently appear among top revenue contributors  
Smaller package sizes command higher price per 100g, indicating potential margin opportunities  

---

## Tools and Skills Demonstrated

Microsoft Excel  
PivotTables and PivotCharts  
Interactive slicers and timelines  
Data modeling and relational structure  
Calculated metrics and KPI development  
Dashboard design and data storytelling  
Sales and customer analytics  

---

## Professional Relevance

This project demonstrates the ability to transform raw sales data into a structured dashboard that supports business analysis and decision making. The skills shown align with responsibilities commonly found in business analyst, data analyst, operations analyst, and revenue analysis roles.

---

## Project Notes

Created for portfolio and skills demonstration purposes  
Designed to reflect realistic data structures and analytical workflows  
