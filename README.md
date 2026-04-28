# Customer Shopping Behavior Analysis

## Overview
This project analyzes customer shopping behavior using **Python, SQL, and Power BI**. The objective is to understand customer purchasing patterns, spending trends, subscription behavior, and product performance to support better business decision-making.

The project uses transactional shopping data and converts raw information into meaningful insights through data cleaning, SQL analysis, and interactive dashboard reporting.

---

## Business Problem
Retail businesses often struggle to understand:

- Which customers generate the most revenue  
- Whether subscribers spend more than non-subscribers  
- Which products perform best  
- How discounts affect purchases  
- Which customer groups should be targeted  

This project solves these problems using data analytics.

---

## Tools & Technologies
- **Python** – Data Cleaning & Exploratory Data Analysis  
- **Pandas / NumPy / Matplotlib / Seaborn**  
- **SQL (PostgreSQL)** – Business Query Analysis  
- **Power BI** – Dashboard & Visualization  

---

## Dataset Details
- **Rows:** 3,900  
- **Columns:** 18  

### Key Columns:
- Customer Age  
- Gender  
- Location  
- Subscription Status  
- Product Category  
- Item Purchased  
- Purchase Amount  
- Shipping Type  
- Discount Applied  
- Previous Purchases  
- Review Rating  

---

## Project Workflow

### 1. Data Cleaning & Preparation (Python)
- Loaded dataset using Pandas  
- Checked null values and data types  
- Filled missing values in Review Rating  
- Renamed columns into snake_case  
- Created new features:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant columns  

### 2. SQL Analysis
Solved real business questions such as:

- Revenue by gender  
- Subscribers vs non-subscribers spending comparison  
- Top-rated products  
- Standard vs Express shipping comparison  
- Customer segmentation (New / Returning / Loyal)  
- Top products by category  
- Discount dependency by product  
- Revenue by age group  

### 3. Dashboard Creation (Power BI)
Created an interactive dashboard showing:

- Total Revenue  
- Average Purchase Amount  
- Top Categories  
- Customer Segments  
- Subscription Insights  
- Shipping Trends  
- Product Performance  

---

## Key Insights
- Subscribers showed higher overall spending  
- Loyal customers contributed major repeat revenue  
- Some products depended heavily on discounts  
- Express shipping users had higher purchase values  
- Certain age groups generated maximum sales  

---

## Business Recommendations
- Launch loyalty programs for repeat customers  
- Increase subscriber benefits  
- Optimize discount strategy  
- Focus marketing on high-value age groups  
- Promote best-selling and top-rated products  

---

## Files Included

```text id="d0y0r"
README.md
business_problem_document.pdf
customer_behavior_sql_queries.sql
customer_shopping_dashboard.pbix
customer_behavior_analysis.ipynb
customer_shopping_behavior.csv
dashboard_preview.png
project_report.pdf
