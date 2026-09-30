# Sales Performance & Business Intelligence

## Project Overview

This project focuses on analyzing sales performance and developing an interactive **Business Intelligence dashboard using Microsoft Power BI**.

The project follows an end-to-end data analytics workflow, starting from raw sales transaction data and progressing through data cleaning, transformation, data modeling, DAX-based KPI development, visualization, and business insights.

The dashboard enables users to monitor sales, profitability, orders, customer segments, product categories, regions, and sales channels through interactive filters and visualizations.

---

## Business Problem

Raw sales transaction data can make it difficult for businesses to understand overall performance and identify areas that require attention.

This project aims to provide a centralized dashboard that helps management:

- Monitor overall sales and profitability
- Track sales and profit trends over time
- Identify high-performing product categories
- Compare sales performance across regions
- Understand customer segment contribution
- Compare different sales channels
- Monitor important business KPIs
- Analyze performance using interactive filters

---

## Dataset

The project uses a structured Excel dataset containing multiple related tables.

### Orders

Contains transaction-level sales information such as:

- Order ID
- Order Date
- Customer ID
- Product ID
- Quantity
- Discount
- Sales
- Cost
- Profit
- Shipping Cost
- Sales Channel
- Payment Method
- Order Status

### Customers

Contains customer-related information:

- Customer ID
- Customer Name
- Segment
- City
- State

### Products

Contains product information:

- Product ID
- Product Name
- Category
- Sub-Category
- Base Price

### Regions

Contains regional information:

- Region
- City
- Zone

### Date

Contains calendar information used for time-based analysis:

- Date
- Year
- Month Number
- Month
- Quarter
- Year-Month

---

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Microsoft Excel
- Data Cleaning
- Data Transformation
- Data Analysis
- Data Visualization
- Business Intelligence
- Dashboard Development

---

## Project Workflow

**Raw Data → Data Cleaning → Power Query Transformation → Data Modeling → DAX & KPI Development → Data Visualization → Interactive Dashboard → Business Insights**

---

## Data Cleaning & Transformation

Data preparation was performed using **Power Query** before building the analytical model.

Key activities included:

- Validating column data types
- Converting date fields into appropriate date formats
- Handling missing values
- Replacing missing payment methods with `Unknown`
- Replacing missing shipping costs with `0`
- Checking duplicate transaction records
- Validating customer and product identifiers
- Preparing tables for relationship-based analysis

---

## Data Modeling

A relational **star-schema approach** was used to organize the data model.

The model contains:

- **Orders** as the main fact table
- **Customers** as a customer dimension
- **Products** as a product dimension
- **Regions** as a regional dimension
- **Date** as a date dimension

Relationships were created between the fact and dimension tables to support filtering and analysis.

The Date table was used for time-intelligence calculations such as YTD and year-over-year analysis.

---

## DAX & KPI Development

DAX measures were created to calculate important business metrics, including:

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Profit Margin
- Total Quantity
- Average Order Value
- Total Cost
- Sales YTD
- Profit YTD
- Sales LY
- Profit LY
- Sales Growth %
- Profit Growth %
- Returned Orders
- Cancelled Orders
- Return & Cancellation Rate
- Average Discount
- Sales per Customer
- Completed Orders
- Completed Order Rate

These measures were used to support KPI cards, trend analysis, and interactive dashboard visualizations.

---

## Dashboard Preview

![Sales Performance Dashboard](Dashboard.png)

The Power BI dashboard provides an interactive overview of sales performance using KPI cards, charts, and slicers.

### Key KPIs

- Total Sales
- Total Profit
- Profit Margin
- Total Orders

### Dashboard Visualizations

- **Sales Trend Over Time**
- **Sales by Product Category**
- **Sales by Region**
- **Sales by Customer Segment**
- **Sales by Sales Channel**

### Interactive Filters

Users can filter the dashboard using:

- Year
- Region
- Category
- Sales Channel

These filters allow users to explore different parts of the business and analyze performance dynamically.

---

## Data Model

The Power BI model follows a **star-schema approach**, with Orders acting as the central fact table and Customers, Products, Regions, and Date serving as supporting dimension tables.

![Power BI Data Model](Model_view.png)

---

## Key Business Insights

The dashboard can be used to identify:

- Changes in sales performance over time
- Profitability and profit margin trends
- Product categories contributing to sales
- Regional differences in sales performance
- Customer segment contribution to overall sales
- Sales channel performance
- Order completion, return, and cancellation patterns

These insights can help businesses monitor performance and support data-driven decision-making.

---

## Project Files

| File | Description |
|---|---|
| `Dashboard.png` | Power BI dashboard screenshot |
| `Model_view.png` | Power BI data model screenshot |
| `Sales_Performance_BI_Dataset.xlsx` | Project dataset |
| `business_analytics.pbix` | Power BI project file |
| `README.md` | Project documentation |

---

## Conclusion

This project demonstrates an end-to-end **Business Intelligence and Data Analytics workflow using Power BI**.

It covers practical experience with **Power Query, data cleaning, data transformation, star-schema data modeling, DAX, KPI development, time-intelligence analysis, interactive dashboards, and business-focused data visualization**.

The project demonstrates how raw transactional data can be transformed into an interactive analytical solution that supports business performance monitoring and decision-making.