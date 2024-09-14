# Zomato SQL Project: Data Analysis for a Food Delivery Company

Welcome to the GitHub repository for the Zomato SQL Project! This project highlights my SQL problem-solving skills through real-world analysis of Zomato, a prominent food delivery service in India. Below, you’ll find a detailed breakdown of the project structure, SQL queries, and key insights derived from the data analysis.

---

## Project Overview

This project demonstrates my ability to tackle complex SQL problems in a business context. The goal was to analyze Zomato's customer and order data to derive meaningful insights, solve business problems, and provide actionable recommendations. The database includes information about customers, restaurants, orders, and deliveries.

---

## Project Structure

### Database Setup
- **Database:** `zomato_db`
- **Tables:**
  - `restaurants` - Stores restaurant data.
  - `customers` - Contains customer details.
  - `riders` - Rider data.
  - `orders` - Records of customer orders.
  - `deliveries` - Details of order deliveries.

### Key SQL Tasks:
1. **Data Import:** Sample data was inserted into the database after tables were created.
2. **Data Cleaning:** Null values were handled, and data integrity was ensured.
3. **Business Problem Solving:** 20 advanced SQL queries solved specific business problems using the data.

---

## Executive Summary

### Overview of Findings

The analysis uncovered significant insights regarding customer behavior, restaurant performance, and order trends. For a stakeholder in the marketing or operations department, three key takeaways are:
1. The peak ordering times occur between 18:00 and 20:00, indicating optimal hours for promotions.
2. High-value customers (who have spent more than 100K) represent a small but critical segment, contributing disproportionately to total revenue.
3. Non-delivered orders remain a challenge, especially for restaurants in major cities, where operational efficiencies need to be improved.

![Sales Trends Snapshot](link-to-visualization.png)

---

## Insights Deep Dive

### Category 1: Customer Behavior Analysis

- **Insight 1:** High-value customers are responsible for over 30% of total revenue.
- **Insight 2:** Customers who haven't ordered since 2023 need to be re-engaged.
- **Insight 3:** "Arjun Mehta" was the customer with the most frequent orders in the past year, mainly ordering during evening hours.
- **Insight 4:** Customers who place more than 750 orders have an average order value (AOV) of 250 INR.

![Customer Segmentation Graph](link-to-visualization.png)

### Category 2: Restaurant Performance

- **Insight 1:** Restaurant revenue varies significantly by city, with Delhi ranking highest in 2023.
- **Insight 2:** The most popular dish in Mumbai is the "Butter Chicken," dominating orders in that region.
- **Insight 3:** Non-delivered orders are concentrated in specific restaurants, indicating potential operational challenges.
- **Insight 4:** Restaurants that have been with the platform for more than a year show a 12% growth in monthly orders.

![Restaurant Performance Graph](link-to-visualization.png)

### Category 3: Delivery Analysis

- **Insight 1:** Riders with faster delivery times tend to receive higher ratings, with the majority completing deliveries in under 20 minutes.
- **Insight 2:** Rider efficiency varies across cities, with an average delivery time of 18 minutes in Delhi and 25 minutes in Kolkata.
- **Insight 3:** Rider earnings are directly correlated with the number of deliveries, averaging an 8% commission per delivery.
- **Insight 4:** Order cancellations are more frequent during peak hours (18:00-20:00), suggesting capacity issues.

![Rider Efficiency Chart](link-to-visualization.png)

### Category 4: Order Trends

- **Insight 1:** The most popular time for orders is between 18:00 and 20:00, making it the ideal slot for targeted promotions.
- **Insight 2:** Order volume peaks in summer, with seasonal dishes showing higher demand during this period.
- **Insight 3:** The average order value has seen a 15% increase year-over-year.
- **Insight 4:** Growth in monthly sales trends is primarily driven by the introduction of new restaurants and an increase in promotional offers.

![Order Trends Visualization](link-to-visualization.png)

---

## Recommendations:

Based on the analysis, the following actions are recommended:
- **For Marketing:** Launch targeted campaigns during peak ordering hours (18:00-20:00) to capitalize on high customer engagement.
- **For Operations:** Focus on improving delivery efficiency by optimizing rider routes and minimizing non-delivered orders.
- **For Customer Retention:** Re-engage customers who have not placed orders in 2024 with personalized offers and incentives.
- **For Restaurant Management:** Focus on underperforming restaurants to identify and resolve operational bottlenecks.

---

## Assumptions and Caveats:

Throughout the project, several assumptions were made to address data challenges:
- **Missing data:** Records with missing delivery times were excluded from the analysis to ensure accuracy in rider performance metrics.
- **Outliers:** Orders with excessively high delivery times were treated as outliers and removed from the dataset.
- **Seasonal trends:** Certain assumptions about seasonal demand were based on historical order data, which may not fully account for external factors (e.g., holidays, promotions).

---

## ERD (Entity Relationship Diagram)

![ERD Diagram](https://github.com/erickyegon/Zomato-SQL-Project/blob/main/erd.png)

---

## Conclusion

This project showcases the use of SQL to solve real-world business problems for a food delivery company. Through detailed data analysis, insights were derived that can help optimize operations, improve customer retention, and increase restaurant revenue. For a comprehensive view of all SQL queries used, visit the SQL section [here]([link-to-SQL-queries](https://github.com/erickyegon/Zomato-SQL-Project/blob/main/20%20Business%20Problems%20solution.sql).

---

## Resources

- **Interactive Tableau Dashboard:** [Link to Tableau Dashboard](link-to-dashboard)
- **SQL Queries:** [Link to SQL Queries](link-to-SQL-queries)

---

*All data used in this project is fictional and generated for educational purposes only.*
