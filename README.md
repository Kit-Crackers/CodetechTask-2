Name: Richa Singh

Company: Codetech IT Solutions

ID: CT08EMC

Domain: Data Analysis

Duration: 17Dec2024-17Jan2024

# Customer Segmentation And Analysis 

## Overview 

![Screenshot 2024-12-21 105203](https://github.com/user-attachments/assets/ccb4ae1d-3d0e-449a-9eb3-30d3385eb6e8)

![Screenshot 2024-12-21 105217](https://github.com/user-attachments/assets/da7c2dfd-c310-4eca-ae35-9ae39337faca)


## Objective

The objective of this project is to perform customer segmentation analysis on a retail dataset to identify distinct customer segments based on purchasing behavior. By clustering customers into different groups, the goal is to better understand customer preferences and behaviors, which can help businesses improve marketing strategies, sales tactics, and customer relationship management.

## Key Activities

- **Data Cleaning and Preprocessing**: The dataset was cleaned by removing missing values in critical columns such as `CustomerID`, `InvoiceNo`, and `UnitPrice`. The total purchase amount for each transaction was calculated using the `Quantity` and `UnitPrice` columns.
  
- **Feature Engineering**: Two key features were created for customer segmentation:
  - **Total Spend**: The total purchase amount for each customer.
  - **Purchase Frequency**: The number of unique invoices (or purchases) for each customer.

- **Clustering**: K-means clustering was applied to segment customers based on the two features (`Total Spend` and `Purchase Frequency`), with the aim of identifying distinct customer groups.

- **Cluster Analysis**: The characteristics of each customer segment were analyzed by calculating the mean values of the features for each cluster.

- **Visualization**: A scatter plot was created to visualize the customer segments based on the two features (`Total Spend` and `Purchase Frequency`).

## Technology Used

- **Python**: The core programming language used for data analysis and clustering.
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations.
- **Scikit-learn**: For applying the K-means clustering algorithm.
- **Matplotlib**: For data visualization (scatter plot).
- **Jupyter Notebook/IDE**: For running and developing the code.

## Dataset

The dataset used for this project is the **Online Retail** dataset, which contains transactional data from a UK-based online retailer. The dataset includes customer information, products purchased, and transaction amounts.

You can download the dataset from Kaggle:
- [Online Retail Dataset on Kaggle](https://www.kaggle.com/datasets/qiita/online-retail)


