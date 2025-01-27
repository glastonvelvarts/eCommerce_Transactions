# eCommerce Customer Segmentation and Lookalike Modeling

## Overview
This project aims to perform customer segmentation and lookalike modeling for an eCommerce dataset. The dataset includes customer information, transaction data, and product details. The goal is to derive actionable business insights, build predictive models, and perform exploratory data analysis (EDA). The project consists of the following tasks:

1. **Exploratory Data Analysis (EDA)**
   - Analyze the data to derive key business insights.

2. **Lookalike Model**
   - Build a model to recommend similar customers based on transaction history and profile information.

3. **Customer Segmentation / Clustering**
   - Use clustering techniques (like GMM) to segment customers based on their profile and transaction data.

## Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- Perform an initial exploration of the dataset.
- Derive at least 5 key business insights from the data.

### Task 2: Lookalike Model
- Build a model that takes a customer's information as input and recommends 3 similar customers.
- Use customer and product data to calculate similarity scores.
- The model generates a CSV file `Glaston_Velvarts_Lookalike.csv` with the customer ID and their 3 lookalikes with similarity scores.

### Task 3: Customer Segmentation / Clustering
- Perform customer segmentation using clustering algorithms.
- Use both profile and transaction data for clustering.
- Evaluate the performance of the clustering models using metrics like the DB Index and Silhouette Score.
- Visualize clusters using relevant plots (e.g., PCA for dimensionality reduction).
- Save the clustering results to `Glaston_Velvarts_Clustering.csv`.

## Files

The project contains the following files:
- `Customers.csv`: Contains customer profile data (e.g., CustomerID, CustomerName, Region, SignupDate).
- `Products.csv`: Contains product information (e.g., ProductID, ProductName, Category, Price).
- `Transactions.csv`: Contains transaction records (e.g., TransactionID, CustomerID, ProductID, Quantity, TotalValue).
- `Glaston_Velvarts_Lookalike.csv`: Output file containing the top 3 lookalikes for each customer based on similarity.
- `Glaston_Velvarts_Clustering.csv`: Output file containing customer segmentation clusters.
- `Glaston_Velvarts_EDA.csv`: Output file containing the exploratory data analysis results.


## Installation

Clone the repository:
```bash
git clone https://github.com/yourusername/ecommerce-customer-segmentation.git
cd ecommerce-customer-segmentation
