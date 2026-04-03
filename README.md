# customer-trends-data-analysis-SQL-Python-PowerBI
data analytics project showcasing customer shopping behavior using pyhton sql and power bi.

### Project Overview
This project analyzes transactional data from 3,900 purchases to uncover customer spending patterns, product preferences, subscription behavior, and discount effectiveness. The insights guide strategic decisions in marketing, loyalty programs, and product positioning.

### Dataset Summary
Rows: 3,900 | Columns: 18
Key features:
Demographics: Age, Gender, Location, Subscription Status
Purchase details: Item, Category, Amount, Season, Size, Color
Behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency, Review Rating, Shipping Type
Missing data: 37 null values in Review Rating (imputed with category median)

### Project Steps
Load Dataset – Import data using Python (Pandas).
Exploratory Data Analysis (EDA) – Check distributions, missing values, outliers, and correlations.
Data Cleaning – Handle nulls, fix data types, remove duplicates, and create calculated columns.
Load to Database – Insert cleaned data into PostgreSQL/MySQL/SQL Server.
SQL Queries – Run queries for KPIs (e.g., total sales by region, monthly trends, top products).
Power BI Dashboard – Connect to database and build interactive visuals.
Generate Report – Summarize insights in a structured document.
Create PPT – Use Gamma AI to convert report into a polished presentation.
