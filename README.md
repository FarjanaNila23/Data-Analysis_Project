
# Superstore Sales Data Analysis
## Project Overview
The Superstore Sales Analysis project provides an interactive dashboard and drill-through pages to analyze sales, profit, and revenue trends. The report enables business stakeholders to make data-driven decisions by visualizing key performance indicators (KPIs), customer segments, product performance, and the impact of discounts on sales and profitability.
## Objective
The objective of this Power BI report is to provide a comprehensive analysis of Superstore sales data, enabling business stakeholders to make data-driven decisions. The report helps in understanding revenue trends, profit margins, customer behaviour, product performance, and the impact of discounts on sales and profitability. Users can gain deep insights into key business metrics, optimize sales strategies, and enhance profitability by utilising interactive visualisations and drill-through pages.
## Data Sources
Dataset: [supermarket-dataset](https://www.kaggle.com/datasets/bravehart101/sample-supermarket-dataset)
## Data Cleaning and Processing
To ensure data accuracy and usability, the following steps were taken:
 - Handled Missing Values for any missing values in key columns like Sales, Profit, and Discount.
 - Have done Data Type Validation to ensure correct data types (e.g., dates for Order Date and Ship Date, numerical values for Sales and Profit).
 - Identified and analyzed extreme values in Order date, Sales and Profit to prevent skewed insights.
 - Verified Region, Category, and Product IDs were correctly mapped across tables.
 - Date Formatting has been done to Standardise date formats for proper time-based analysis.
## Data Organization and Modeling
 - To improve data organization and enhance analysis, the dataset has been structured into four tables
 - Connected tables using primary and foreign keys.
 - Added multiple calculated columns and groups to categorize data effectively
 - Developed multiple measures to compute key metrics and dynamic analysis
       
## Dashboard and Visualizations
**Main Dashboard**

The primary dashboard includes:
  1.	Total Revenue, Total Profit, Total Sales Quantity
  2.	Revenue Trend Over Time 
  3.	Total Revenue by Region and Sales Category
  4.	Profit Margin KPI with Trend Over Time
  5.	Discount Analysis and Order processing
  6.	Key influencers
     
**Drill-Through Pages Summary**:
   - Customer Details Page: Provides insights into customer-based revenue and profit trends.
   - Product Performance Page: Analyzes product sales and profitability across regions.
   - Discount Analysis Page: Examines the impact of discounts on sales and profit margins.
     
## Row-Level Security (RLS) Implementation
   RLS is configured to restrict data access based on user roles:
   - Admin Role: Access to all data.
   - Users Role: Restricted access based on defined conditions.

## Interactivity and Filters
   To enhance user experience, the report includes:
   - Drill-through navigation for detailed insights on customers, products, and discount analysis.
   - Dynamic Titles update based on selected Customer Segments.
   - Slicers and Filters have been used so that Users can filter data by Year, Region, Product Category, and Customer Segment.

## Business Questions Addressed
   1. What is the total revenue, and how does profit vary across categories and years?
   2. Which products are the best-sellers and most profitable?
   3. How do sales vary by year, region, and state?
   4. How do discounts affect sales and profitability across categories?
   5. How does shipping mode impact delivery time and profit margins?
   6. How does order processing time vary across regions and segments?
   7. Which locations have the highest customer density, and how does this impact sales?
     
## Insights and Business Impact
   - High discounts often reduce profitability despite increasing sales.
   - Technology products generate the highest revenue but require optimized discounting strategies.
   - Certain regions contribute significantly to revenue, guiding targeted marketing strategies.







