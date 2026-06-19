# Olist E-Commerce Business Intelligence Analysis

## Overview
This project analyzes the Olist Brazilian E-Commerce dataset — real anonymized 
transaction data from a marketplace connecting small sellers to major e-commerce 
platforms, covering 100,000+ orders from 2016-2018. The analysis answers four 
core business questions that mirror real-world e-commerce decision-making around 
revenue drivers, operations, seller management, and customer retention.

## Business Questions Answered

**1. What drives Average Order Value (AOV)?**
Analyzed AOV across 73 product categories. Electronics and appliances (computers, 
large appliances) drive the highest AOV (R$500-1,150) — nearly 6x higher than 
categories like home comfort and flowers.

**2. How does delivery time affect customer satisfaction?**
Compared review scores for early vs late deliveries. Orders delivered before the 
estimated date scored 4.29/5 on average vs 2.27/5 for late deliveries — a 47% drop, 
showing delivery expectation management matters more than raw speed.

**3. What does seller performance look like?**
Analyzed revenue and ratings across 2,970 sellers. Top sellers by revenue 
(700-1,900+ orders) maintain consistent ratings of 3.8-4.4, while single-order 
sellers often show inflated 5.0 ratings due to low review volume.

**4. What are customer retention patterns?**
Found only ~3% of customers are repeat buyers — but this is structurally expected 
given Olist's durable-goods category mix. High-AOV categories (computers, furniture) 
see almost no repeat purchases, while low-AOV categories (home linens, beauty, 
sports/leisure) drive most repeat behavior.

## Key Business Insight
There's a clear inverse relationship between AOV and repeat purchase behavior. 
This suggests a dual strategy: maximize one-time order value in durable, high-AOV 
categories while investing retention efforts (loyalty programs, personalized 
recommendations) in low-AOV, high-frequency categories where repeat behavior is 
naturally higher.

## Tools Used
Python (pandas for data cleaning and aggregation, matplotlib for visualization), 
Jupyter Notebook

## Dataset
[Olist Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) 
on Kaggle
