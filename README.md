# Data-Science-Assignment-eCommerce-Transactions-Dataset-

## Overview

This project performs **customer segmentation** on eCommerce data using **clustering techniques**. The goal is to analyze customer behavior based on transaction history and profile information. The data comes from three CSV files:

- **Customers.csv**: Contains customer details such as `CustomerID`, `CustomerName`, and `Region`.
- **Products.csv**: Contains product information including `ProductID`, `ProductName`, and `Price`.
- **Transactions.csv**: Contains transaction data such as `TransactionID`, `CustomerID`, `ProductID`, and `TransactionDate`.

## Project Goals

- **Exploratory Data Analysis (EDA)**: Understand customer demographics, transaction behavior, and product distribution.
- **Clustering**: Perform customer segmentation using clustering algorithms like KMeans.
- **Evaluation Metrics**: Calculate clustering metrics, including the **Davies-Bouldin Index** and **Silhouette Score** to assess the clustering quality.
- **Visualization**: Visualize the clustered data with relevant plots to provide business insights.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Installation

To install the required libraries, run the following command:

```bash
pip install -r requirements.txt

