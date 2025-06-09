# Euphoria-Store-Sales-Analysis
Euphoria, a global skincare and beauty e-commerce brand, needed insights into its markets, products, and profitability. They want to know  • Are they hitting the profit margin?  • Which markets are lagging?  • Are the discounts killing profitability?

## Project Overview
Euphoria is a skincare and beauty e-commerce brand interested in gaining more insights about the market, products, customers, and sales.

## Problem Statement
Specifically, the e-store aims to achieve an average annual profit margin of 15% across all product groups, 20% annual overall sales growth with a higher target of 30% for the corporate segment, and at least $400K in annual sales for each market.

## Deliverables
A comprehensive Power BI report for the brand’s sales executives(Stakeholders) that visualizes these KPIs and provides actionable insights to drive strategic decision-making for the store's future growth.

## Business Statement
1.  What were the most profitable segments from 2020 to 2023?
2.  Can we have a map visual to interact with locations to see the profit distribution?
3.  What were the most profitable markets since 2020?
4.  What were the best seller products since 2020?
5.  Following above, can we also view the best seller categories and subcategories?
6.  In each market, can we view the sales trend of each product/category/subcategory from 2020 to 2023?
7.  In each market, can we view the profits trend of each product/category/subcategory from 2020 to 2023?
8.  Did we have a good discount strategy last a few years?
9.  Can we list top 10 customers who spent most from each country every year?
10. Which countries contributed most profits to each category?


## Aim and Objectives
## Aim
The aim of this project is to should analyze sales volumes and profitability across various product groups and markets, focusing on key performance indicators (KPIs) critical to the e-store's success.

## Objectives
1. Track key metrics like Sales, Profit, Quantity, and Profit Margin across time and geographies.
2. Access the effectiveness of the brand’s discount strategy.

## Exploratory Data Analysis
## Data Cleaning and Transformation
1. Removed duplicates and handled missing values
While preparing the raw data, I checked for duplicate records, I used Power Query in Power BI to remove duplicate rows in the data. I also checked for null or blank values.

2. Standardized Data Formats
I checked the data types of all the column fields of the data and made sure they are in the appropriate data types. I created a custom Date table to enable time intelligence functions like YoY calculations and filtering. The Date table included: Year, Quarter, Month, Month name, and number (to sort visuals correctly).

3. Removed Unnecessary Columns to Improve Dashboard Performance
I carefully reviewed each column and checked if useful for business analysis or visualization. I identified several columns that were irrelevant to the analysis or had no analytical value. Columns that didn’t contribute to key metrics, insights, or filtering were dropped to reduce redundancy in the data.

4. Created Necessary DAX Measures for Accurate Analysis
To drive meaningful insights from the data, I developed a set of well-structured DAX (Data Analysis Expressions) measures in Power BI. These measures were designed to calculate key performance metrics and enable dynamic analysis across time, product categories, customer segments, and markets. I started by identifying the core business KPIs such as Total Sales, Total Profit, Profit Margin (%), and Total Quantity Sold. I then created time-based measures using DAX time intelligence functions, such as:
Year-over-Year (% YoY) Growth, Previous Year Sales, and Profit Margin. I also created segment-specific measures, such as Corporate Sales and Corporate YoY Growth %, to track against their 30% growth target.





    ![Screenshot 2025-06-07 143528](https://github.com/user-attachments/assets/f5949c7e-23d3-490e-bbff-040f00e6c4fa)





