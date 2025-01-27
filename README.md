# Data-Science-Assignment-eCommerce-Transactions-Dataset

# eCommerce Transactions Data Analysis

## Overview

This repository contains the analysis and predictive models built on the provided eCommerce transactions dataset consisting of three files: `Customers.csv`, `Products.csv`, and `Transactions.csv`. The project includes performing Exploratory Data Analysis (EDA), building a Lookalike Model, and segmenting customers using clustering techniques. The goal is to generate actionable business insights, create personalized recommendations, and improve customer segmentation strategies.

---

## Project Structure

- **Customers.csv**: Contains customer details such as CustomerID, CustomerName, Region, and SignupDate.
- **Products.csv**: Contains product details such as ProductID, ProductName, Category, and Price.
- **Transactions.csv**: Contains transaction details such as TransactionID, CustomerID, ProductID, TransactionDate, Quantity, TotalValue, and Price.

---

## Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights

- **Goal**: Perform an in-depth exploratory data analysis (EDA) to uncover trends, patterns, and business insights.
- **Deliverables**: 
  - A Jupyter Notebook containing the EDA code.
  - A PDF report (`EDA_Report.pdf`) summarizing 5 key business insights from the analysis.

**Key Insights**:
- The insights are focused on customer behavior, transaction trends, and product preferences.

### Task 2: Lookalike Model

- **Goal**: Build a Lookalike Model to recommend similar customers based on their profile and transaction history.
- **Approach**: Uses cosine similarity to compare customers based on their transaction behaviors.
- **Deliverables**: 
  - A CSV file (`Lookalike.csv`) containing top 3 lookalike customers with their similarity scores for the first 20 customers (`CustomerID: C0001` to `C0020`).
  - A Jupyter Notebook explaining the model development and logic.

### Task 3: Customer Segmentation / Clustering

- **Goal**: Perform customer segmentation using clustering techniques to group customers based on their profile and transaction data.
- **Approach**: KMeans clustering (or other clustering techniques) is used, and the Davies-Bouldin index (DB index) is calculated to evaluate the clusters.
- **Deliverables**:
  - A report on clustering results, including the number of clusters, DB index value, and clustering metrics.
  - A Jupyter Notebook containing the clustering code and visualizations.

---


