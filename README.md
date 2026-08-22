# Retail Sales Analysis Dashboard

A Business Analytics project that uses **Microsoft Power BI** and **MySQL** to analyze retail sales data and present the results through an interactive dashboard.

## Project Overview

The project focuses on connecting retail sales data from different sources, cleaning and transforming the data, and creating an interactive Power BI dashboard for business analysis.

The dashboard helps analyze:

- Total sales
- Sales by store
- Sales by product category
- Sales trends over time
- Quantity sold by store
- Customer-level sales details

The project was completed as **Experiment No. 1 – Retail Sales Analysis Using Power BI & MySQL** for the BCA Business Analytics course.

## Objectives

- Import retail sales data from CSV/Excel and MySQL.
- Connect MySQL data to Power BI Desktop.
- Clean and transform the imported data.
- Create relationships between relevant data tables.
- Build interactive Power BI visualizations.
- Analyze sales based on store, category, customer, and time.
- Present business insights through a centralized dashboard.

## Technologies Used

| Technology | Purpose |
|---|---|
| Microsoft Power BI Desktop | Data modeling, analysis, and dashboard creation |
| MySQL | Retail sales database |
| CSV / Excel | Source data |
| Power Query | Data cleaning and transformation |
| DAX | Power BI calculations and measures |

## Data Fields

The retail dataset contains important fields such as:

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount
- Store

## Dashboard Features

### 1. Total Sales
A KPI card displays the overall sales amount generated from the transactions.

### 2. Sales by Store
A column chart compares sales across stores such as Bangalore, Kurnool, Chennai, and Hyderabad.

### 3. Sales by Product Category
The dashboard compares sales for:

- Electronics
- Clothing
- Beauty

The project report identifies **Electronics** as the highest-selling category.

### 4. Quantity Sold by Store
This visualization compares the total quantity sold by each store. The report identifies **Bangalore** as having the highest quantity sold, followed by Kurnool, Hyderabad, and Chennai.

### 5. Sales Trend
A time-based visualization and monthly sales trend help identify periods of higher and lower sales.

### 6. Customer Sales Details
A detailed table allows individual customer transactions to be examined using fields such as Customer ID, Month, Gender, Price per Unit, and Product Category.

### 7. Product Category Filter
An interactive filter allows users to select Beauty, Clothing, or Electronics and analyze the selected category.

## Data Preparation

The following data preparation steps were performed:

1. Collected the retail sales dataset in CSV format.
2. Obtained retail sales data from MySQL.
3. Created a `retail_db` database in MySQL.
4. Created and populated the sales table.
5. Connected Power BI Desktop to MySQL.
6. Imported the required data.
7. Checked for errors and missing values.
8. Verified data types for fields such as Date, Quantity, Price per Unit, and Total Amount.
9. Renamed fields where necessary.
10. Prepared numerical fields for calculations and visualization.

## Dashboard Preview

The final dashboard contains KPI cards, column charts, a line chart, filters, and a customer sales table to provide an interactive view of retail performance.

## How to Open the Project

### Requirements

- Windows
- Microsoft Power BI Desktop
- MySQL Server (required if recreating the MySQL connection)
- The retail sales dataset

### Steps

1. Install **Power BI Desktop**.
2. Download or clone this repository.
3. Open the Power BI project file.
4. If prompted, update the data-source settings.
5. If using MySQL, make sure the MySQL server is running and the required `retail_db` database and sales table are available.
6. Refresh the data.
7. Open the report page to explore the dashboard.

> **Note:** Power BI Desktop is required to edit or refresh the `.pbix` project. Data-source credentials and local MySQL settings may need to be configured on another computer.

## Key Insights

Based on the dashboard and project analysis:

- Electronics has the highest sales among the displayed product categories.
- Bangalore has the highest quantity sold among the analyzed stores.
- Store-level and category-level comparisons help identify stronger sales contributors.
- Monthly sales trends provide a view of changes in sales performance over time.
- Customer-level details allow individual transactions to be examined.

## Learning Outcomes

Through this project, I learned how to:

- Connect Power BI to CSV/Excel and MySQL data sources.
- Import and organize data in Power BI.
- Use Power BI Report View and Data View.
- Work with the Data and Visualizations panes.
- Create and format charts, tables, and KPI cards.
- Analyze retail sales by category, store, customer, and time.
- Apply filters for interactive analysis.
- Build a retail sales dashboard for business analysis.
- Present data-driven insights using Power BI.

## Project Information

**Student:** Varshith R  
**Register Number:** 2411021240072  
**Program:** Bachelor of Computer Applications (BCA)  
**Semester:** V  
**University:** Alliance University  
**Subject:** Business Analytics  
**Project:** Retail Sales Analysis Using Power BI & MySQL  
**Date:** 22-08-2026

## Conclusion

The retail sales data was successfully connected to Power BI Desktop using CSV and MySQL data sources. After importing, cleaning, and organizing the data, an interactive dashboard was developed to analyze sales by store, product category, customer, and time.

The project demonstrates how Power BI can be used to convert retail sales data into meaningful visual insights that support data-driven business decisions.
