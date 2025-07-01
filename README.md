# Amazon-Product-Review-Analysis-Excel
*Project Type:* Exploratory Data Analysis  
*Tools Used:* Microsoft Excel (Pivot Tables, Charts, Formulas)  
*Role:* Junior Data Analyst
*Domain:* E-commerce Analytics

##  Project Overview

This case study involved analyzing 1,465 Amazon product listings across various categories, with a focus on product performance, customer reviews, pricing, and discount insights. The goal was to generate actionable recommendations for marketing, pricing strategy, and product management.

## Key Business Questions Answered

| # | Question |
1. What is the average discount percentage by product category?.
2. How many products are listed under each category?.
3. What is the total number of reviews per category?.
4.  Which products have the highest average ratings?.
5. What is the average actual price vs. the discounted price by category?.
6. Which products have the highest number of reviews?.
7. How many products have a discount of 50% or more?.
8. What is the distribution of product ratings (e.g., 3.0, 4.0)?.
9. What is the total potential revenue per category (actual price × rating count)?.
10. How many unique products fall into price ranges (<₹200, ₹200–₹500, >₹500)?.
11. How does the discount level relate to customer rating?.
12. How many products have fewer than 1,000 reviews?.
13.  Which categories offer the highest discounts?.
14. Top 5 products by rating and number of reviews combined?.


##  Technical Approach

- *Data Cleaning:*
  - Analysed categories using TRIM Function.
  - Normalized discount values and formatted numeric fields.

- *Feature Engineering:*
  - Created custom KPI: rating_score = rating × rating_count
  - Categorized prices using IF conditions into custom buckets.

- *Analysis Tools:*
  - *Pivot Tables* for aggregation (e.g., average discount by category)
  - *COUNTIF* and *calculated columns* for derived insights
  - *Scatter Charts* to explore correlations (discount vs. rating)

- *Visualization:*
  - Created a comprehensive Excel dashboard with:
    - Bar and pie charts
    - Slicers for filtering by category
    - Summary cards for key metrics
    - Top 5 product highlights


## 📊 Key Insights

1. What is the average discount percentage by product category? 0.476914676
2. How many products are listed under each category? 450
3. What is the total number of reviews per category? 26766377
4. Which products have the highest average ratings? tablets 
5. What is the average actual price vs the discounted price by category? 8480.32

## 📁 Files Included

| File | Description |

| Amazon_Review_Analysis.xlsx | Cleaned dataset, Pivot Tables, and Dashboard |
| dashboard_screenshot.png | Visual of the interactive dashboard |
| top_products_chart.png | Chart of top 5 products by rating × rating count |
| README.md | Project summary and documentation |


##  Skills Demonstrated

- Data Analysis using Excel
- Pivot Table customization and data aggregation
- Charting & dashboard creation
- Data storytelling and presentation
- Business insight development
- Formula-driven data modeling (IF, COUNTIF, LEFT, SORT, etc.)

##  What I Learned

This project sharpened my ability to:
- Work with semi-structured e-commerce data
- Communicate complex findings visually
- Use Excel as a complete analysis and storytelling tool


##  Project Previews

###  How does the discount level relate to customer rating?
![Screenshot (31)](https://github.com/user-attachments/assets/f9393153-312c-4d90-a894-42a78080cfaa)


###  Top 5 Products (Rating × Rating Count)  

![Screenshot (25)](https://github.com/user-attachments/assets/30de545a-c67e-4326-b253-fffbf2e5e12a)
