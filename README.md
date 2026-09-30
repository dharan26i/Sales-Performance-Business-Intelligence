# \# Sales Performance \& Business Intelligence

# 

# \## Project Overview

# 

# This project analyzes sales transaction data to understand sales performance, profitability, customer behavior, product performance, regional performance, and sales channels.

# 

# An interactive Power BI dashboard was developed to transform raw sales data into meaningful business insights and support data-driven decision-making.

# 

# The project follows an end-to-end Business Intelligence workflow using \*\*Power Query, data cleaning, data transformation, data modeling, DAX, KPI development, data visualization, and Power BI dashboard development\*\*.

# 

# \---

# 

# \## Business Problem

# 

# A business has a large volume of sales transaction data but needs an interactive way to monitor sales performance, profitability, customers, products, regions, and sales channels.

# 

# The objectives of this analysis are to:

# 

# \* Monitor total sales and profit

# \* Analyze profit margin and order performance

# \* Identify sales trends over time

# \* Compare product category performance

# \* Analyze regional sales performance

# \* Understand customer segment performance

# \* Compare sales channels

# \* Monitor year-over-year sales and profit growth

# \* Provide an interactive dashboard for business analysis

# 

# \---

# 

# \## Dataset

# 

# The project uses a sales transaction dataset containing \*\*5,000 orders\*\* along with supporting customer, product, region, and date information.

# 

# The dataset is organized into the following tables:

# 

# \### Orders

# 

# Contains transaction-level sales information, including:

# 

# \* Order ID

# \* Order Date

# \* Customer ID

# \* Product ID

# \* Quantity

# \* Discount

# \* Sales

# \* Cost

# \* Profit

# \* Shipping Cost

# \* Sales Channel

# \* Payment Method

# \* Order Status

# 

# \### Customers

# 

# Contains customer information including:

# 

# \* Customer ID

# \* Customer Name

# \* Segment

# \* City

# \* State

# 

# \### Products

# 

# Contains product information including:

# 

# \* Product ID

# \* Product Name

# \* Category

# \* Sub-Category

# \* Base Price

# 

# \### Regions

# 

# Contains regional information including:

# 

# \* Region

# \* City

# \* Zone

# 

# \### Date

# 

# A dedicated date table used for time-based analysis and DAX time intelligence.

# 

# \---

# 

# \## Tools \& Technologies

# 

# \* Microsoft Power BI

# \* Power Query

# \* DAX

# \* Data Modeling

# \* Data Cleaning

# \* Data Transformation

# \* KPI Development

# \* Data Visualization

# \* Dashboard Development

# \* Microsoft Excel

# 

# \---

# 

# \## Project Workflow

# 

# \### 1. Data Loading

# 

# The sales dataset was loaded into Power BI from Excel.

# 

# Multiple related tables were imported for orders, customers, products, regions, and dates.

# 

# \---

# 

# \### 2. Data Cleaning \& Transformation — Power Query

# 

# The data was prepared using Power Query.

# 

# Data preparation included:

# 

# \* Setting appropriate data types

# \* Handling missing values

# \* Replacing missing payment methods with `Unknown`

# \* Replacing missing shipping costs with `0`

# \* Checking duplicate transaction records

# \* Validating customer and product identifiers

# \* Preparing date fields for time-based analysis

# 

# \---

# 

# \### 3. Data Modeling

# 

# A relational data model was created in Power BI using a star-schema approach.

# 

# The model includes:

# 

# \* Orders as the main fact table

# \* Customers as a customer dimension

# \* Products as a product dimension

# \* Regions as a regional dimension

# \* Date as a date dimension

# 

# Relationships were created between the fact and dimension tables to support interactive analysis.

# 

# \---

# 

# \### 4. DAX \& KPI Development

# 

# DAX measures were created to calculate important business KPIs, including:

# 

# \* Total Sales

# \* Total Profit

# \* Profit Margin

# \* Total Orders

# \* Total Customers

# \* Total Quantity

# \* Average Order Value

# \* Sales YTD

# \* Sales LY

# \* Sales Growth %

# \* Profit YTD

# \* Profit LY

# \* Profit Growth %

# \* Returned Orders

# \* Cancelled Orders

# \* Return \& Cancel Rate

# \* Completed Order Rate

# \* Average Discount

# \* Sales per Customer

# 

# These measures support business performance analysis and time-based comparisons.

# 

# \---

# 

# \## Power BI Dashboard

# 

# The Power BI dashboard provides an interactive view of overall sales and business performance.

# 

# \### Key Performance Indicators

# 

# \* Total Sales

# \* Total Profit

# \* Profit Margin

# \* Total Orders

# 

# \### Dashboard Visualizations

# 

# \* Sales Trend Over Time

# \* Sales by Product Category

# \* Sales by Region

# \* Sales by Customer Segment

# \* Sales by Sales Channel

# 

# \### Interactive Filters

# 

# \* Year

# \* Region

# \* Category

# \* Sales Channel

# 

# The dashboard uses \*\*DAX measures, data modeling, KPIs, slicers, data visualization, and interactive filtering\*\* to support business analysis.

# 

# \---

# 

# \## Dashboard Preview

# 

# !\[Sales Performance Dashboard](Dashboard.png)

# 

# \---

# 

# \## Data Model

# 

# The Power BI data model follows a \*\*star-schema approach\*\*, with the Orders table as the main fact table and Customers, Products, Regions, and Date as supporting dimension tables.

# 

# !\[Power BI Data Model](Model\_view.png)

# 

# \---

# 

# \## Key Business Insights

# 

# The dashboard is designed to help management:

# 

# \* Monitor overall sales and profitability

# \* Track sales trends over time

# \* Compare product category performance

# \* Identify regional sales differences

# \* Understand customer segment contribution

# \* Compare sales performance across channels

# \* Monitor sales and profit growth

# \* Identify areas requiring further business investigation

# 

# \---

# 

# \## Conclusion

# 

# This project demonstrates an end-to-end \*\*Business Intelligence and Power BI workflow\*\*:

# 

# \*\*Raw Data → Power Query → Data Cleaning \& Transformation → Data Modeling → DAX \& KPIs → Interactive Dashboard → Business Insights\*\*

# 

# The project demonstrates practical skills in:

# 

# \* Power BI

# \* Power Query

# \* DAX

# \* Data Modeling

# \* Data Cleaning

# \* Data Transformation

# \* KPI Development

# \* Data Visualization

# \* Dashboard Development

# \* Business Intelligence

# \* Business Analysis

# 

# \---

# 

# \## Project Files

# 

# | File | Description |

# |---|---|

# | `Sales\_Performance\_BI\_Dataset.xlsx` | Sales dataset and supporting tables |

# | `Sales\_Performance\_BI.pbix` | Power BI dashboard |

# | `Dashboard.png` | Power BI dashboard preview |

# | `Model\_view.png` | Power BI data model view |

# | `README.md` | Project documentation |

# 

# \---

# 

# \## Project Purpose

# 

# This project was created for educational and portfolio purposes to demonstrate practical \*\*Business Intelligence, Power BI, DAX, data modeling, and data analysis skills\*\*.

