Customer Lifetime Value (CLV) Prediction & Customer Segmentation

Overview:
This project focuses on predicting Customer Lifetime Value (CLV) using transactional e-commerce data. It helps businesses estimate future revenue, identify high-value customers, and design targeted retention strategies.
In addition, customer segmentation is performed to classify users into low, medium, and high-value groups based on their predicted CLV.

Problem Statement:
Businesses often struggle to answer:
Which customers are most valuable?
How much revenue will a customer generate in the future?
Which customers should be prioritized for retention?

This project solves these problems using data-driven predictive modeling.

Dataset:
Online Retail Dataset (UCI Machine Learning Repository)
Contains real-world transactional data including:
Customer ID
Purchase date
Quantity
Unit price

Approach:
1. Data Preprocessing
Removed missing customer IDs
Filtered invalid transactions (negative/zero quantity)
Created total transaction value
2. Feature Engineering (RFM Model)
Recency → Days since last purchase
Frequency → Number of purchases
Monetary → Total spending
3. Predictive Modeling
BG/NBD Model → Predicts future purchase frequency
Gamma-Gamma Model → Estimates customer lifetime value
4. Data Cleaning for Model Assumptions
Filtered customers with non-positive monetary values
Ensured compatibility with probabilistic models
5. Customer Segmentation
Segmented customers into:
High-value
Medium-value
Low-value

Results & Insights:
Identified top high-value customers contributing significantly to revenue
Observed strong relationship between purchase frequency and customer value
Predicted future purchases for each customer
Segmented customers for targeted marketing and retention

Visualizations:
The project includes:
CLV distribution
Top customers by CLV
Frequency vs CLV relationship
Predicted purchases vs CLV
Customer segmentation analysis

Key Insights:
A small group of customers contributes to a large portion of total revenue
Customers with higher purchase frequency tend to have higher CLV
Predicted future purchases strongly influence customer value
Segmentation helps prioritize marketing and retention efforts

Tech Stack:
Python
Pandas, NumPy
Lifetimes (BG/NBD, Gamma-Gamma models)
Matplotlib

Output:
CLV predictions for all customers
Customer segmentation labels
CSV file with final results

Business Impact:
This project demonstrates how companies can:
Forecast revenue at the customer level
Identify high-value customers
Optimize retention strategies
Improve marketing ROI through segmentation

How to Run
Open the notebook in Google Colab
Run all cells step-by-step
View results and visualizations
Download the generated CSV file
