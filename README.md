# New Wheels SQL Business Analysis

## Project Overview
This project analyzes the business performance of **New Wheels**, a vehicle resale company that provides an end-to-end platform for listing, selling, and delivering pre-owned vehicles.

The company has recently experienced **declining sales, customer ratings, and orders**. Using SQL, this project answers key business questions and provides insights to help leadership understand the decline and improve business performance.

---

## Objective
- Analyze customer, order, and product data using **SQL**
- Identify trends in **orders, revenue, and customer feedback**
- Generate insights for **business decision-making**
- Provide **recommendations to improve performance**

---

## Dataset
The analysis uses three main tables:

- **customer_t** – customer information (state, credit card type)
- **order_t** – order details (quantity, discount, feedback, shipping date, quarter)
- **product_t** – vehicle information (maker, price)

---

## Key Business Questions
The analysis answers the following questions:

1. Distribution of customers across states  
2. Top 5 vehicle makers preferred by customers  
3. Most preferred vehicle maker in each state  
4. Average customer rating by quarter  
5. Feedback distribution trends over time  
6. Order trend by quarter  
7. Net revenue and quarter-over-quarter change  
8. Revenue vs order trend  
9. Average discount by credit card type  
10. Average shipping time by quarter  

---

## Key Insights
- **California and Texas** have the highest number of customers.
- **Chevrolet** is the most preferred vehicle brand.
- Customer ratings show a **declining trend across quarters**.
- Negative feedback increased significantly from **Q1 to Q4**.
- Both **orders and revenue decreased steadily throughout the year**.
- Some credit cards receive **higher discounts**, affecting pricing strategy.

---

## Business Recommendations
- Improve **customer service and after-sales support**.
- Focus marketing efforts on **high-performing states**.
- Optimize **discount strategies with credit card partners**.
- Reduce **shipping delays** to improve customer satisfaction.
- Track business performance through a **centralized KPI dashboard**.

---

## Tools Used
- SQL  
- MySQL  
- Window Functions (RANK, LAG)  
- Aggregate Functions  
