# Customer Shopping Behavior Analysis: Insights from Transactional Data

This project analyzes **3,900 customer transactions** to uncover insights into **spending patterns, customer segmentation, product preferences, and subscription behavior**.  
The goal is to provide actionable recommendations to improve marketing strategy, product positioning, and subscription adoption.  
The analysis was performed using **Python (Pandas)** for data preparation and **SQL** for structured data analysis, with visualizations in **Power BI**.

---

## Project Goals

The analysis focuses on identifying:

- **Spending Patterns & Revenue:** Total revenue by gender, age group, and subscription status.  
- **Customer Segmentation:** Categorize customers as **Loyal, Returning, or New**, and examine repeat purchase behavior.  
- **Product Preferences:** Identify top-rated, best-selling, and discount-driven products.  
- **Discount & Shipping Impact:** Evaluate how discounts and shipping types influence purchase amounts.

---

## Technologies Used

- **Python (Pandas):** Data cleaning, preparation, feature engineering, and exploratory analysis.  
- **SQL (PostgreSQL):** Structured queries for revenue, product, and customer behavior analysis.  
- **Power BI:** Interactive dashboards to visualize key metrics and insights.

---

## Data Summary

- **Dataset:** 3,900 rows, 18 columns of customer transactions.  

| Feature Group       | Key Columns                                         |
|--------------------|----------------------------------------------------|
| **Demographics**    | Age, Gender, Location, Subscription Status        |
| **Purchase Details**| Item Purchased, Category, Purchase Amount, Season, Size, Color |
| **Shopping Behavior**| Discount Applied, Promo Code, Previous Purchases, Review Rating, Shipping Type |

- **Missing Data:** Imputed missing `Review Rating` values using median by product category.  
- **Feature Engineering:** Created `age_group` and `purchase_frequency_days` columns.

---

## Key Findings

### Revenue & Spending
- **Gender Revenue:** Male customers generated higher total revenue than female customers.  
- **Age Group Revenue:** Young Adults contributed the highest revenue, followed by Middle-aged customers.  
- **Shipping Impact:** Express shipping purchases had slightly higher average purchase amounts than Standard shipping.

### Product Insights
- **Top-Rated Products:** Gloves, Sandals, and Boots had the highest average review ratings.  
- **Top Products by Category:**  
  - Accessories: Jewelry  
  - Clothing: Blouse  
  - Footwear: Sandals  
- **Discount-Dependent Product:** Hats had the highest percentage of discounted purchases.

### Subscription & Loyalty
- **Subscription Status:** 27% of customers are subscribed, 73% are not.  
- **Average Spend:** Non-subscribers spent slightly more than subscribers on average.  
- **Customer Segmentation:** Majority are **Loyal** customers, followed by Returning and New segments.

---

## Business Recommendations

- **Increase Subscription Rate:** Offer exclusive benefits and incentives to boost subscription adoption.  
- **Customer Loyalty Programs:** Reward repeat buyers to maintain and expand the Loyal customer base.  
- **Targeted Marketing:** Focus campaigns on high-revenue demographics like Young Adults and customers preferring Express Shipping.  
- **Optimize Discounts:** Evaluate discount strategies for products like Hats to balance revenue and margin.

---

## Project Structure

