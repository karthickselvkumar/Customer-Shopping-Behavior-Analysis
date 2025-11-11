# Customer Shopping Behavior Analysis: Insights from Transactional Data

This project utilizes transactional data to perform a deep-dive analysis of customer shopping behavior, providing actionable insights for marketing, product positioning, and subscription strategy. The analysis was performed using Python for data preparation and cleaning, followed by SQL (PostgreSQL) for structured data analysis.

## 🎯 Project Goals

The primary goal of this analysis was to uncover strategic insights by examining:
* [cite_start]Spending patterns and total revenue by demographics and groups (Gender, Age Group, Subscription Status)[cite: 28, 60, 47].
* [cite_start]Customer segments (Loyal, Returning, New) and repeat buyer behavior[cite: 53, 58].
* [cite_start]Product preferences, including top-rated, best-selling, and discount-dependent products[cite: 42, 55, 50].
* [cite_start]The impact of discounts and shipping types on purchase amounts[cite: 38, 44].

## 🛠️ Technologies Used

* [cite_start]**Python:** Data Loading, Exploration, Cleaning, Feature Engineering[cite: 14, 19, 21].
    * *Libraries:* `pandas`
* [cite_start]**PostgreSQL:** Structured Query Language (SQL) for in-depth business transactions and analysis[cite: 25, 27].
* [cite_start]**Power BI:** Visualizing key findings in an interactive dashboard[cite: 62, 63].

## 📊 Data Summary

[cite_start]The dataset contains **3,900 rows** and **18 columns** of transactional data[cite: 6, 7].

| Feature Group | Key Columns Included |
| :--- | :--- |
| **Demographics** | [cite_start]Age, Gender, Location, Subscription Status [cite: 9] |
| **Purchase Details** | [cite_start]Item Purchased, Category, **Purchase Amount (USD)**, Season, Size, Color [cite: 10] |
| **Shopping Behavior**| [cite_start]Discount Applied, Promo Code Used, Previous Purchases, Review Rating, Shipping Type [cite: 11] |

* [cite_start]**Missing Data Handled:** 37 missing values in the `Review Rating` column were imputed using the median rating of each product category[cite: 12, 19].
* [cite_start]**Feature Engineering:** New columns for `age_group` and `purchase_frequency_days` were created[cite: 22, 23].

## 💡 Key Findings

### Revenue and Spending
* [cite_start]**Gender Revenue:** Male customers generated significantly more total revenue ($\$157,890$) than female customers ($\$75,191$)[cite: 34, 37].
* [cite_start]**Age Group Revenue:** **Young Adults** contributed the highest total revenue ($\$62,143$), followed by the Middle-aged group ($\$59,197$)[cite: 61].
* [cite_start]**Shipping Type:** Express shipping had a slightly higher average purchase amount ($\$60.48$) compared to Standard shipping ($\$58.46$)[cite: 46].

### Product Insights
* [cite_start]**Top-Rated Products:** Gloves (3.86), Sandals (3.84), and Boots (3.82) were the top 3 products by average review rating[cite: 43].
* **Top Products by Category:**
    * [cite_start]*Accessories:* Jewelry (171 orders)[cite: 57].
    * [cite_start]*Clothing:* Blouse (171 orders)[cite: 57].
    * [cite_start]*Footwear:* Sandals (160 orders)[cite: 57].
* [cite_start]**Discount-Dependent:** The **Hat** had the highest percentage of discounted purchases (50.00%)[cite: 52].

### Subscription & Loyalty
* [cite_start]**Subscription Status:** 73% of customers do not have a subscription, while 27% are subscribed[cite: 80, 90].
* [cite_start]**Subscription Spend:** Non-subscribers had a marginally higher average spend ($\$59.87$) than subscribers ($\$59.49$)[cite: 49].
* [cite_start]**Customer Segmentation:** The majority of customers are in the **Loyal** segment (3,116 customers), followed by Returning (701) and New (83) customers[cite: 54].

## 🚀 Business Recommendations

Based on the analysis, the following strategic recommendations are proposed:

1.  [cite_start]**Boost Subscriptions:** Promote exclusive benefits for subscribers to increase the low 27% subscription rate[cite: 80, 99].
2.  [cite_start]**Customer Loyalty Programs:** Implement rewards for repeat buyers to maintain and grow the "Loyal" customer segment[cite: 102, 54].
3.  [cite_start]**Targeted Marketing:** Focus marketing spend on high-revenue groups like **Young Adults** and target users who prefer **Express Shipping**[cite: 61, 46, 105].
4.  [cite_start]**Review Discount Policy:** Carefully analyze the performance of discounts on products like the Hat to balance sales boosts with margin control[cite: 52, 103].

## 📂 Project Structure
