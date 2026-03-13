# MBA-Business-Analytics-project-EDA-Predictive-Modelling
Insight Summary Report

Problem Statement

The goal of this project was to understand customer buying behaviour and identify customers who may stop purchasing from the company in the future. Businesses often lose customers without realizing it early, which can reduce sales and revenue. By analyzing past transaction data, the company can understand how customers behave and take action before customers leave.
The dataset used in this project contains two years of online retail transaction data. It includes information such as invoice number, product name, quantity purchased, transaction date, price per unit, customer ID, and country. Using this dataset, exploratory data analysis (EDA) was performed to understand patterns in customer purchases, product performance, and revenue distribution. In addition, a predictive model was built to identify customers who are at risk of churn.
The main objective of this project was to answer the following questions:
•	Who are the most valuable customers?
•	What patterns exist in customer purchasing behaviour?
•	Which customers are likely to stop buying from the company?
•	How can the business use this information to improve retention and sales?
By answering these questions, the company can make better decisions related to marketing, customer retention, and product promotion.


Key Findings from Exploratory Data Analysis

1. Small Number of Customers Generate Most Revenue
The analysis showed that a small percentage of customers contribute a large share of the total revenue. Many customers make only a few purchases, while a small group spends much more than others.
Business takeaway:
The company should focus on retaining these high-value customers through loyalty programs, personalized offers, and better customer engagement.

2. Majority of Revenue Comes from the United Kingdom
The country analysis showed that most of the sales come from customers in the United Kingdom. Other countries contribute much smaller portions of revenue.
Business takeaway:
The company should continue strong marketing efforts in the United Kingdom while also exploring growth opportunities in other countries.

3. Many Customers Purchase Only Once or Twice
The data shows that a large number of customers place only one or two orders. Only a small group of customers purchase frequently.
Business takeaway:
Encouraging repeat purchases can significantly increase revenue. The company could use email campaigns, discounts, or loyalty programs to motivate customers to buy again.

4. A Few Products Generate a Large Portion of Sales
The product analysis shows that only a small number of products generate most of the revenue. These products are consistently purchased by many customers.
Business takeaway:
The company should promote these popular products more and ensure they remain in stock. They can also use these products in marketing campaigns to attract new customers.

5. Customer Segmentation Shows Different Customer Groups
Using RFM analysis (Recency, Frequency, Monetary), customers were grouped into different segments such as loyal customers, active customers, and customers who may leave soon.
Some customers purchase regularly and spend more money, while others have not purchased recently.
Business takeaway:
The company should treat each customer group differently. Loyal customers should receive rewards, while customers who have not purchased recently should receive re-engagement offers.

1.	Model Used and Results
To predict customer churn, two machine learning models were used:
•	Logistic Regression
•	Random Forest
The dataset was divided into 80% training data and 20% testing data. The models were evaluated using several metrics such as accuracy, precision, recall, F1 score, and ROC-AUC.
After comparing the results, the Random Forest model performed better than Logistic Regression. It showed better performance across most evaluation metrics and was able to capture patterns in customer behaviour more effectively.
The ROC-AUC metric was given the most importance, because it measures how well the model can distinguish between customers who will churn and customers who will remain active.
Because of its better performance, the Random Forest model was selected as the final model for predicting customer churn.

Business Recommendations

1. Focus on Customers Who Are at Risk of Leaving
Customers who have not purchased recently are more likely to stop buying completely. The company should identify these customers and send targeted offers, reminder emails, or discounts to bring them back.

2. Strengthen Loyalty Programs for Valuable Customers
Customers who buy frequently or spend more money are very valuable to the business. The company should create loyalty programs, reward points, or exclusive offers to keep these customers engaged and satisfied.

3. Promote Best-Selling Products
Since a few products generate most of the revenue, the company should promote these products more through advertisements, email marketing, and special offers. Highlighting popular products can also help attract new customers.

Conclusion
This project helped identify important patterns in customer behaviour and sales performance. By using data analysis and predictive modeling, the company can better understand which customers are valuable and which customers are likely to churn.
Using these insights, the business can improve marketing strategies, increase customer retention, and make better decisions that lead to higher sales and long-term growth.


