# Customer Shopping Behavior Analysis

This repository contains a complete data analysis project on customer shopping behavior for a retail company. The project analyzes 3,900 purchase transactions to uncover insights into spending patterns, demographics, product preferences, and subscription effects. 

## Project Overview
A retail company seeks to understand customer behavior to boost sales and loyalty. Key focus areas include demographics (age, gender), purchase details (amount, category, discounts), and behaviors (reviews, shipping, frequency). 

Dataset: `customer_shopping_behavior.csv` (3,900 rows, 18 columns including Customer ID, Age, Gender, Item Purchased, Category, Purchase Amount, etc.). 



## Workflow
1. **Python EDA**: Load CSV, handle 37 missing Review Ratings, create features, export to MySQL. 
2. **SQL Analysis**: Query database for metrics like top categories (Clothing: Blouse/Pants top-sellers). 
3. **Visualization**: Power BI dashboard  shows subscription (27% Yes), avg purchase $59.76, avg rating 3.75.
4. **Insights & Recs**: Target males/high-revenue groups; boost subscriptions; loyalty programs for repeat buyers. 

## Key Findings
- Males drive higher revenue despite fewer transactions. 
- Top-rated: Gloves (3.86), Sandals (3.84). 
- Loyal customers dominate (3,116); focus on converting new/returning.
- Express shipping correlates with higher spend.

## Recommendations
- Promote subscriber benefits (27% uptake). 
- Highlight top products; review discount policies (e.g., Hat: 50% discounted). 
- Target marketing to middle-aged/high-revenue ages. 

## Setup & Run
1. Install: `pandas`, `sqlalchemy`, `pymysql`.
2. Run notebook  to clean and load data to MySQL. 
3. Execute SQL  in MySQL Workbench. 
4. View dashboard in PowerPoint  or rebuild in Power BI. 

## Tech Stack
- Python (pandas), Jupyter, SQL (MySQL), Power BI.
MIT License.
