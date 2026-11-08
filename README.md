# Exploratory-Data-Analysis

🛒 E-Commerce Data Analysis | Exploratory Data Analysis (EDA)

📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on an E-Commerce dataset to discover meaningful business insights, understand customer purchasing behavior, analyze product performance, and explore sales trends.

Using Python and its data visualization libraries, this project explores different aspects of E-Commerce transactions through statistical analysis and visualizations.

The main goal is to transform raw transactional data into meaningful insights that can support data-driven business decisions.

🎯 Project Objectives

Identify the top 10 best-selling products.

Analyze sales performance across different countries.

Explore monthly revenue trends.

Understand the distribution of product quantities.

Identify the top 10 highest-value customers.

Examine relationships between numerical variables using correlation analysis.

🛠️ Tools & Technologies

Python – Programming Language

Pandas – Data Analysis and Manipulation

NumPy – Numerical Computing

Matplotlib – Data Visualization

Seaborn – Statistical Data Visualization

Kaggle Notebook – Development Environment

📊 Exploratory Data Analysis (EDA)

1. Top 10 Best-Selling Products

In this analysis, products were grouped by their descriptions, and the total quantity sold was calculated for each product.

A bar chart was used to visualize the top 10 best-selling products.

Key Insight:

WORLD WAR 2 GLIDERS ASSTD DESIGNS appears as the highest-selling product.

The visualization helps identify products with strong customer demand.

Business Recommendation:

Businesses can use this information to maintain sufficient inventory of popular products and improve stock management strategies.

2. Top 10 Countries by Sales

This analysis focuses on identifying the top 10 countries based on total sales revenue.

Total sales were calculated by multiplying Quantity by UnitPrice. Then, sales were grouped by country and sorted in descending order.

A bar chart was used to compare country-wise sales performance.

Key Insights:

The United Kingdom generates significantly higher sales than other countries.

The Netherlands, EIRE, Germany, France, and Australia are among the other contributing markets.

The business shows a strong sales concentration in the United Kingdom.

Business Recommendation:

Maintain strong customer relationships in the United Kingdom while exploring opportunities to increase sales in other countries.

3. Monthly Revenue Trend

This analysis explores how revenue changes over time.

The InvoiceDate column was converted into datetime format, and monthly revenue was calculated by grouping total sales by month.

A line chart was used to visualize monthly revenue trends.

Key Insights:

Revenue shows noticeable fluctuations across different months.

Significant revenue peaks appear around May 2011 and December 2011.

Monthly analysis helps identify high-performing sales periods.

Business Recommendation:

Analyze peak sales periods to understand customer purchasing behavior and develop better inventory and sales strategies.

4. Quantity Distribution

A histogram was used to understand the distribution of product quantities in the dataset.

This visualization helps identify where most quantity values are concentrated and highlights unusual positive and negative values.

Key Insights:

Most quantity observations are concentrated within a relatively small range.

Some extreme positive and negative values are present.

Negative quantities may indicate product returns or cancelled transactions.

Extremely high positive quantities may represent bulk purchases.

Business Recommendation:

Investigate unusual transaction values to better understand purchasing behavior and product return patterns.

5. Top 10 Customers

This analysis identifies the top 10 customers based on their total purchase value.

Customer-wise total sales were calculated by grouping the data using CustomerID and sorting the results in descending order.

Key Insights:

Customer ID 14646 is the highest-value customer, with total sales of approximately 202,119.21.

Customer ID 14911 ranks second, with approximately 108,180.29 in total sales.

A small group of customers contributes a significant amount of revenue.

Business Recommendation:

Focus on customer retention strategies, personalized offers, and loyalty programs to maintain relationships with high-value customers.

6. Correlation Heatmap

Correlation analysis was performed to understand the relationships between three numerical variables:

Quantity

UnitPrice

TotalSales

A Seaborn heatmap was used to visualize the correlation coefficients.

Key Insights:

Variable RelationshipCorrelationQuantity vs TotalSales0.91UnitPrice vs TotalSales0.40Quantity vs UnitPrice-0.0012 

Quantity and TotalSales show a strong positive correlation.

UnitPrice and TotalSales show a moderate positive correlation.

Quantity and UnitPrice have almost no linear correlation.

Business Recommendation:

Understanding these relationships can help businesses evaluate the factors associated with revenue generation and improve sales strategies.

📈 Key Findings & Business Insights

Based on the overall EDA, the following insights were identified:

Product Performance: WORLD WAR 2 GLIDERS ASSTD DESIGNS is the highest-selling product by quantity.

Geographical Sales: The United Kingdom dominates the country-wise sales performance.

Revenue Trends: Monthly revenue fluctuates, with notable peaks around May and December 2011.

Quantity Patterns: The dataset contains unusual positive and negative quantity values.

Customer Behavior: Customer ID 14646 is the highest-value customer.

Correlation: Quantity has a strong positive correlation with TotalSales (0.91).

📝 Conclusion

This E-Commerce Exploratory Data Analysis project provides valuable insights into product performance, geographical sales distribution, monthly revenue trends, customer purchasing behavior, and relationships between numerical variables.

Through Python-based statistical analysis and data visualization, the project demonstrates how EDA can help transform transactional data into meaningful business insights.

This project also strengthened my practical understanding of data analysis, visualization, and analytical thinking.


⭐ If you find this project useful, don't forget to give it a star!

#Python #EDA #DataAnalysis #Ecommerce #Pandas #Matplotlib #Seaborn #DataVisualization
