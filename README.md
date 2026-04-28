# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes customer shopping behavior using **Python, SQL, and Power BI** to uncover patterns in customer purchases, spending habits, product preferences, and subscription trends.  

The dataset contains **3,900 customer transactions** across multiple product categories. The goal of this project is to generate business insights that can help improve marketing strategies, customer retention, and revenue growth.

---

## Tools & Technologies Used
- **Python** – Data cleaning, preprocessing, exploratory data analysis  
- **Pandas / NumPy / Matplotlib / Seaborn** – Data manipulation & visualization  
- **PostgreSQL / SQL** – Business queries & advanced analysis  
- **Power BI** – Interactive dashboard creation  

---

## Dataset Information
- **Rows:** 3,900  
- **Columns:** 18  

### Main Features:
- Customer Demographics: Age, Gender, Location, Subscription Status  
- Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color  
- Shopping Behavior: Discount Applied, Previous Purchases, Review Rating, Shipping Type, Frequency of Purchases  

---

## Project Workflow

### 1. Data Cleaning & Preparation (Python)
- Loaded dataset using Pandas  
- Checked missing values and handled null entries  
- Imputed missing values in `Review Rating` using category median  
- Renamed columns into snake_case format  
- Created new columns:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant columns after consistency checks  

### 2. SQL Business Analysis
Performed multiple business queries such as:

- Revenue comparison by gender  
- High-spending discount users  
- Top 5 highest-rated products  
- Shipping type comparison (Standard vs Express)  
- Subscribers vs Non-Subscribers spending analysis  
- Discount-dependent products  
- Customer segmentation (New / Returning / Loyal)  
- Top products by category  
- Repeat buyers subscription trends  
- Revenue contribution by age group  

### 3. Power BI Dashboard
Built an interactive dashboard to visualize:

- Total Revenue  
- Customer Segments  
- Top Categories  
- Purchase Trends  
- Shipping Preferences  
- Subscription Insights  

---

## Key Insights
- Subscribers showed stronger purchasing behavior than non-subscribers  
- Loyal customers contributed significant repeat revenue  
- Some products heavily depended on discounts for sales  
- Express shipping users had higher average purchase amounts  
- Certain age groups generated more revenue than others  

---

## Business Recommendations
- Launch loyalty rewards for repeat buyers  
- Increase subscriber benefits to boost memberships  
- Optimize discount strategies to protect profit margins  
- Focus ads on high-performing customer segments  
- Promote top-rated products in campaigns  

---

## Files Included
- `Customer_Shopping_Behavior.pbix` → Power BI Dashboard  
- `analysis.sql` → SQL Queries  
- `report.pdf` → Full Project Report  

---

## How to Use
1. Open `.pbix` file in Power BI Desktop  
2. Run SQL queries in PostgreSQL/MySQL  
3. Explore report for methodology & findings  

---

## Author
**Ashish Upadhyay**  

---

## Connect With Me
Feel free to connect for feedback, collaboration, or opportunities.
