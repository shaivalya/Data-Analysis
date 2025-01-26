eCommerce Transactions Dataset 
This repository contains the solution to an eCommerce Transactions dataset analysis assignment. The assignment is divided into three main tasks:

Exploratory Data Analysis (EDA) and Business Insights.
Building a Lookalike Model for customer recommendations.
Customer Segmentation using Clustering techniques.
Dataset Description
The dataset consists of three CSV files:

Customers.csv: Contains customer information.
Products.csv: Contains product details.
Transactions.csv: Contains transaction records made by customers.
File Structure:
Customers.csv:

CustomerID: Unique identifier for each customer.
CustomerName: Name of the customer.
Region: Continent where the customer resides.
SignupDate: Date when the customer signed up.
Products.csv:

ProductID: Unique identifier for each product.
ProductName: Name of the product.
Category: Product category.
Price: Price of the product in USD.
Transactions.csv:

TransactionID: Unique identifier for each transaction.
CustomerID: ID of the customer who made the transaction.
ProductID: ID of the product sold.
TransactionDate: Date of the transaction.
Quantity: Quantity of the product purchased.
TotalValue: Total value of the transaction.
Price: Price of the product sold.
Project Tasks
Task 1: Exploratory Data Analysis (EDA) and Business Insights
Perform an Exploratory Data Analysis (EDA) on the dataset.
Derive at least 5 business insights from the EDA.
The insights were derived from the dataset's structure, such as customer demographics, transaction patterns, product performance, etc.

Task 2: Lookalike Model
Build a Lookalike Model that recommends 3 similar customers based on their profile and transaction history.
The model uses both customer and product information.
The model assigns a similarity score to each recommended customer.
Output the top 3 lookalikes for customers C0001 to C0020 in the "Lookalike.csv" file, which contains a map: Map<cust_id, List<cust_id, score>>.
Task 3: Customer Segmentation / Clustering
Perform customer segmentation using clustering techniques.
Use both profile information (from Customers.csv) and transaction data (from Transactions.csv).
Choose any clustering algorithm with the number of clusters between 2 and 10.
Calculate the clustering evaluation metric, including the DB Index.
Visualize the clusters using appropriate plots.
Files and Directories
eda.ipynb: Jupyter notebook containing the code for Task 1 (EDA).
lookalike_model.ipynb: Jupyter notebook containing the code for Task 2 (Lookalike Model).
clustering.ipynb: Jupyter notebook containing the code for Task 3 (Customer Segmentation).
Lookalike.csv: CSV file containing the top 3 lookalike customers and their similarity scores for each of the first 20 customers.
EDA_Report.pdf: PDF report containing business insights derived from the EDA.
Clustering_Report.pdf: PDF report containing the results and evaluation metrics of the clustering task.
README.md: This README file with project details.
Requirements
To run the code, you need the following Python libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn
scipy
datetime
sklearn

Output
The Jupyter notebooks will output the business insights, the top 3 lookalike customers for the first 20 customers, and the clustering results along with visualizations.
The Lookalike.csv file will contain the lookalike customers with their similarity scores.
The reports EDA_Report.pdf and Clustering_Report.pdf will be generated after running the corresponding notebooks.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Thanks to the creators of the eCommerce Transactions dataset.
The insights and models in this project were derived using Python libraries such as pandas, scikit-learn, and seaborn.

