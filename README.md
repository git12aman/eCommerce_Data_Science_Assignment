# eCommerce Transactions Dataset Analysis

## Overview
This repository contains the analysis and modeling of an eCommerce Transactions dataset, which includes customer, product, and transaction information. The project is divided into three main tasks: Exploratory Data Analysis (EDA), Lookalike Model development, and Customer Segmentation using clustering techniques.

## Dataset Description
The dataset consists of three CSV files:
1. **Customers.csv**: Contains customer information including ID, name, region, and signup date.
2. **Products.csv**: Contains product details including ID, name, category, and price.
3. **Transactions.csv**: Contains transaction records including transaction ID, customer ID, product ID, transaction date, quantity, total value, and price.

## Tasks
### Task 1: Exploratory Data Analysis (EDA)
- Performed EDA to understand the dataset and derive business insights.
- Insights are documented in a PDF report.

### Task 2: Lookalike Model
- Developed a Lookalike Model to recommend similar customers based on their profiles and transaction history.
- Generated a CSV file containing the top 3 lookalikes for the first 20 customers.

### Task 3: Customer Segmentation / Clustering
- Implemented customer segmentation using clustering techniques.
- Calculated clustering metrics, including the DB Index, and visualized the clusters.
- Results are documented in a PDF report.

## Files Included
- `FirstName_LastName_EDA.ipynb`: Jupyter Notebook for EDA.
- `FirstName_LastName_EDA.pdf`: PDF report with business insights.
- `FirstName_LastName_Lookalike.ipynb`: Jupyter Notebook for Lookalike Model development.
- `FirstName_LastName_Lookalike.csv`: CSV file with lookalike recommendations.
- `FirstName_LastName_Clustering.ipynb`: Jupyter Notebook for customer segmentation.
- `FirstName_LastName_Clustering.pdf`: PDF report on clustering results.

## Installation
To run the notebooks, ensure you have the following libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
