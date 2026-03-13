Customer Shopping Behavior Analysis
===================================

A complete **end-to-end data analytics project** analyzing customer purchase behavior to uncover insights about spending patterns, product preferences, and customer segments.

The project demonstrates the **full analytics workflow** including **data cleaning, exploratory data analysis (EDA), SQL business analysis, dashboard visualization, and business reporting**.

Project Objective
=================

The goal of this project is to analyze customer transaction data to answer the key business question:

> How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?

The analysis helps businesses understand:

*   Customer purchasing behavior
    
*   Product performance
    
*   Revenue drivers
    
*   Customer loyalty patterns
    
*   Marketing opportunities
    

Business Problem
================

A retail company wants to better understand customer purchasing behavior across:

*   Demographics
    
*   Product categories
    
*   Discounts and promotions
    
*   Subscription programs
    
*   Purchase frequency
    

Management wants insights that can help improve:

*   Sales performance
    
*   Customer engagement
    
*   Loyalty programs
    
*   Marketing strategy
    

Dataset Overview
================

The dataset contains transactional data of customer purchases.

**Dataset Statistics**

MetricValueTotal Records3,900Total Features18Missing Values37Data TypeTransactional Retail Data

**Feature Categories**

### Customer Demographics

*   Age
    
*   Gender
    
*   Location
    
*   Subscription Status
    

### Purchase Information

*   Item Purchased
    
*   Category
    
*   Purchase Amount
    
*   Season
    
*   Size
    
*   Color
    

### Shopping Behavior

*   Discount Applied
    
*   Promo Code Used
    
*   Previous Purchases
    
*   Frequency of Purchases
    
*   Review Rating
    
*   Shipping Type
    

Project Workflow
================

The project follows a **complete data analytics pipeline**:

`   Raw Dataset     │     ▼Data Cleaning & Preparation (Python)     │     ▼Exploratory Data Analysis (Python)     │     ▼Business Analysis (PostgreSQL)     │     ▼Data Visualization (Power BI)     │     ▼Insights & Business Recommendations     │     ▼Report + Presentation   `

Tech Stack
==========

Python - Data cleaning and EDA

Pandas - Data manipulation

PostgreSQL - Business queries and structured analysis

Power BI - Interactive dashboards

Jupyter Notebook - Analysis environment

Gamma AI - Presentation generation

GitHub - Version control and project portfolio

Data Preparation (Python)
=========================

The dataset was cleaned and transformed using Python.

### Key Steps

**1\. Data Loading**

*   Loaded dataset using pandas
    

**2\. Data Exploration**

*   df.info() for structure
    
*   df.describe() for summary statistics
    

**3\. Handling Missing Values**

*   37 missing values in **Review Rating**
    
*   Filled using **median rating per product category**
    

**4\. Removing Redundant Columns**

*   promo\_code\_used removed due to redundancy with discount\_applied
    

**5\. Feature Engineering**

*   Created **age\_group**
    
*   Created **purchase\_frequency\_days**
    

**6\. Column Standardization**

*   Converted column names to **snake\_case**
    

**7\. Database Integration**

*   Clean dataset loaded into **PostgreSQL** for SQL analysis.
    

Exploratory Data Analysis (EDA)
===============================

EDA was performed to understand the dataset and identify patterns.

Key analysis included:

*   Purchase distribution
    
*   Customer demographics
    
*   Category sales trends
    
*   Review ratings distribution
    
*   Discount usage patterns
    

These insights helped guide the **SQL business queries**.

SQL Business Analysis (PostgreSQL)
==================================

After cleaning the data, the dataset was loaded into **PostgreSQL** to perform business-focused analysis.

### Key SQL Questions

1.  Revenue by gender
    
2.  High-spending discount users
    
3.  Top rated products
    
4.  Shipping type comparison
    
5.  Subscribers vs non-subscribers
    
6.  Discount dependent products
    
7.  Customer segmentation
    
8.  Top products per category
    
9.  Repeat buyers and subscription behavior
    
10.  Revenue contribution by age group
    

Key Insights
============

Some major insights discovered:

**Revenue by Gender**

*   Male customers generated significantly higher revenue.
    

**Customer Segmentation**

*   Loyal customers represent **~80% of the customer base**.
    

**Top Product Rating**

*   Gloves achieved the highest average rating.
    

**Discount Patterns**

*   Hats received discounts in **50% of purchases**, the highest among products.
    

**Age Group Revenue**

*   Young Adults generated the highest total revenue.
    

**Shipping Preference**

*   Express shipping users had slightly higher average purchases.
    

Power BI Dashboard
==================

An interactive **Power BI dashboard** was built to visualize the insights.

### Dashboard KPIs

*   Total Customers
    
*   Average Purchase Amount
    
*   Average Product Rating
    

### Key Visualizations

*   Revenue by Category
    
*   Sales by Age Group
    
*   Subscription Status Distribution
    
*   Shipping Type Comparison
    

### Dashboard Filters

*   Gender
    
*   Subscription Status
    
*   Category
    
*   Shipping Type
    

Business Recommendations
========================

Based on the analysis, several strategic recommendations were proposed:

### 1\. Improve Subscription Conversion

Introduce incentives to increase subscription adoption.

### 2\. Strengthen Loyalty Programs

Reward returning customers to encourage repeat purchases.

### 3\. Optimize Discount Strategy

Review discount policies to avoid unnecessary margin loss.

### 4\. Promote Top Products

Feature best-selling and highest-rated items in marketing campaigns.

### 5\. Target High-Value Demographics

Focus marketing efforts on **young adult and middle-aged segments** generating the most revenue.


Future Improvements
===================

Possible extensions for this project:

*   Build **predictive models for customer lifetime value**
    
*   Implement **customer churn prediction**
    
*   Add **time series sales forecasting**
    
*   Deploy an **interactive web dashboard**
    

Author
======

**Khushi Malviya**

B.Tech Computer Science Final Year StudentAspiring 

**Data Analyst / Data Scientist**
