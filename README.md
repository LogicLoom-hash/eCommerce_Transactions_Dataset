# eCommerce Transactions Analysis
This repository contains the analysis and modeling for an eCommerce Transactions dataset. The project involves performing Exploratory Data Analysis (EDA), building a Lookalike Model, and performing Customer Segmentation using clustering techniques.

## Overview
You are provided with an eCommerce Transactions dataset consisting of three files: Customers.csv, Products.csv, and Transactions.csv. The tasks are aimed at deriving actionable insights, building predictive models, and understanding customer segments.

## Files Description

Customers.csv
CustomerID: Unique identifier for each customer.
CustomerName: Name of the customer.
Region: Continent where the customer resides.
SignupDate: Date when the customer signed up.

Products.csv
ProductID: Unique identifier for each product.
ProductName: Name of the product.
Category: Product category.
Price: Product price in USD.

Transactions.csv
TransactionID: Unique identifier for each transaction.
CustomerID: ID of the customer who made the transaction.
ProductID: ID of the product sold.
TransactionDate: Date of the transaction.
Quantity: Quantity of the product purchased.
TotalValue: Total value of the transaction.
Price: Price of the product sold.

## Assignment Tasks
# Task 1: Exploratory Data Analysis (EDA) and Business Insights
Perform EDA on the provided dataset.
Derive at least 5 business insights from the EDA.

Deliverables:
A Jupyter Notebook/Python script (Shravani_Yadav_EDA.ipynb) containing the EDA code.
A PDF report (Shravani_Yadav_EDA.pdf) with business insights (maximum 500 words).

# Task 2: Lookalike Model
Build a Lookalike Model that recommends 3 similar customers based on their profile and transaction history.

Deliverables:
The top 3 lookalikes with their similarity scores for the first 20 customers in Customers.csv.
A CSV file (Shravani_Yadav_Lookalike.csv) with the lookalike recommendations.
A Jupyter Notebook/Python script (Shravani_Yadav_Lookalike.ipynb) explaining the model development.

# Task 3: Customer Segmentation / Clustering
Perform customer segmentation using clustering techniques, using both profile and transaction information.

Deliverables:

A report (Shravani_Yadav_Clustering.pdf) on the clustering results, including:
The number of clusters formed.
DB Index value.
Other relevant clustering metrics.
A Jupyter Notebook/Python script (Shravani_Yadav_Clustering.ipynb) containing the clustering code.


## Evaluation Criteria
EDA and Business Insights: Quality and relevance of insights.
Lookalike Model: Model accuracy, logic, and quality of recommendations.
Customer Segmentation: Clustering logic, metrics, and visual representation of clusters.

## Conclusion
This project demonstrates the application of data analysis, machine learning, and clustering techniques to derive insights and build models from an eCommerce Transactions dataset.
