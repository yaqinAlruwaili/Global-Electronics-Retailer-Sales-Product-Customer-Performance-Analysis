
# Global Electronics Retailer | Sales, Product & Customer Performance Analysis

## Project Overview

An interactive Power BI analytics project analyzing a fictional global electronics retailer's business performance from 2016 to 2021.

The project focuses on three key business areas: Sales Performance, Product Performance, and Customer Performance, transforming raw business data into actionable insights through interactive dashboards.

## Project Objectives

- Analyze overall sales performance, profitability, and store performance across markets.
- Evaluate product performance by identifying top-performing products, brands, and categories.
- Analyze customer demographics, purchasing behavior, and spending patterns.
- Identify business trends and opportunities to support decision-making.

## Dashboards

### 1. Sales Performance

Analyzes overall sales performance across time, countries, and stores.

**Key Metrics:**
- Total Sales
- Total Cost
- Profit Margin %
- Total Orders
- Units Sold

**Business Questions:**
- How are sales and profitability changing over time?
- Which countries generate the highest sales?
- How does store performance compare?

### 2. Product Performance

Evaluates product and category performance to identify the main drivers of revenue and profitability.

**Key Metrics:**
- Total Products
- Total Brands
- Total Categories
- Average Unit Cost
- Average Unit Price
- Average Profit Margin

**Business Questions:**
- Which product categories and brands perform best?
- Which products generate the highest profit?
- Do products with higher total sales necessarily generate higher profits?

### 3. Customer Performance

Explores customer demographics and purchasing behavior to understand the customer base and spending patterns.

**Key Metrics:**
- Total Customers
- Total Customers with Orders
- Sales per Customer
- Repeat Customer Rate

**Business Questions:**
- Who are the retailer's customers?
- How frequently do customers make purchases?
- How is customer spending distributed?

## Data Sources

The project uses the Global Electronics Retailer dataset from Maven Analytics, which is fictional and consists of five tables:

- Sales
- Customers
- Products
- Stores
- Exchange Rates

The dataset covers business transactions from 2016 to 2021.

## Data Preparation & Transformation

- **Dataset Understanding:** Reviewed the source tables, examined their structure, and understood the relationships between datasets.
- **Data Type Correction:** Ensured that columns had the appropriate data types for accurate analysis.
- **Data Cleaning:** Removed unnecessary columns and irrelevant tables to simplify the data model.
- **Date Table Creation:** Created a dedicated Date Table to support time-based analysis and reporting.
- **Customer Segmentation:** Created DAX-based customer segments to analyze purchase frequency and spending behavior.
- **Data Model:** Built a standard Star Schema model where all dimension tables (Dim_Date, Dim_Customers, Dim_Stores, and Dim_Products) filter the single Fact_Sales table through clean One-to-Many (1 to *) relationships.

## Tools & Technologies

- **Power BI:** Interactive Dashboards, Data Modeling, DAX.
- **Power Query:** Data Cleaning, Transformation, and Data Integration.
- **Microsoft Excel:** Source Data Review and Validation.

## Key Insights & Observations

### 1. Sales Performance

- Generated $279M in total sales with a 59% profit margin.
- In-store sales reached $222M, significantly exceeding online sales of $57M.
- North America was the leading region, contributing approximately $173M in sales.
- Total orders reached 26K, with 989K units sold.

### 2. Customer Performance

- Analyzed a customer base of 15K, with 12K customers making purchases.
- Achieved a 61% repeat customer rate.
- High-spending customers represented the largest spending segment, with approximately 11.2K customers.
- 4.6K customers placed only one order, highlighting an opportunity to improve customer retention.

### 3. Product Performance

- Computers generated the highest category sales at $97M, followed by Home Appliances at $54M.
- The leading brand generated approximately $59M in sales.
- Black was the top-selling product color, generating $69M in sales.
- The highest-profit product generated approximately $1.69M in profit.

