📊 Data Analytics Project – End-to-End Analysis & Dashboard

1. Overview

This project demonstrates an end-to-end data analytics workflow, starting from raw data exploration to building an interactive business dashboard. The goal is to extract meaningful insights from data using Python and SQL, and present them clearly through Power BI and a final presentation.

The project covers data loading, cleaning, exploratory analysis, database querying, visualization, and reporting.

2. Dataset

Source: customer_shopping_behavior.csv
Domain: (e.g., Sales, Customers, Business Performance)
Description: The dataset contains structured data related to business performance, including metrics such as customer information, transactions, and key numerical fields used for analysis.

3. Tools & Technologies

 Python (Pandas, NumPy) – Data cleaning & preprocessing
 PostgreSQL – Business query analysis
 SQL – Aggregations, filtering, segmentation
 Power BI – Interactive dashboard
 Gamma – Business presentation
 GitHub – Version control & project documentation

 4. Project Workflow

    Step 1: Data Preparation (Python)
      Loaded dataset using Pandas
      Checked structure and summary statistics
      Handled missing values in review_rating using median imputation by category
      Standardized column names to snake_case
      Created age_group using binning
      Created purchase_frequency_days feature
      Removed redundant columns
      Loaded cleaned dataset into PostgreSQL
    
    Step 2: Business Analysis (SQL – PostgreSQL)
      Key business questions answered:
      Revenue comparison by gender
      High-spending discount users
      Top 5 products by rating
      Shipping type comparison
      Subscribers vs non-subscribers analysis
      Discount-dependent products
      Customer segmentation (New, Returning, Loyal)
      Top 3 products per category
      Repeat buyers vs subscription likelihood
      Revenue contribution by age group

5. Dashboard (Power BI)

An interactive dashboard was built to visualize:

KPIs (Total Customers, Average Purchase Amount, Average Rating)

Revenue trends

Customer segmentation insights

Product and shipping performance

Subscription impact on revenue

6. Business Insights

Subscribers contribute higher average revenue

Loyal customers drive significant repeat purchases

Certain products rely heavily on discounts

Specific age groups generate higher revenue

Express shipping users tend to spend more
