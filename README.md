# Customer Segmentation using Machine Learning

## Overview

This project uses K-Means Clustering to segment customers into different groups based on demographic information, purchasing behavior, and spending patterns.

Customer segmentation helps businesses understand their customers better and develop targeted marketing strategies for different customer groups.

The project was developed using Python, Pandas, Matplotlib, and Scikit-learn.


## Dataset

Dataset Source:

https://raw.githubusercontent.com/YBIFoundation/ProjectDataSet/main/ShopSmart%20Customer%20Segmentation.csv

### Features Included

* Age
* Annual Income
* Spending Score
* Total Purchases
* Average Order Value
* Days Since Last Purchase


## Data Exploration

The following analysis was performed:

* Displayed dataset records using `head()`
* Examined dataset structure using `info()`
* Generated summary statistics using `describe()`
* Checked for missing values using `isnull().sum()`


## Data Visualization

### Annual Income Distribution

Generated a histogram to analyze the distribution of customer annual income.

### Spending Score Distribution

Generated a histogram to understand customer spending behavior.

### Income vs Spending Analysis

Created a scatter plot to visualize the relationship between Annual Income and Spending Score.


## Data Preparation

### Feature Selection

The following features were selected for clustering:

* Age
* Annual Income
* Spending Score
* Total Purchases
* Average Order Value
* Days Since Last Purchase

### Feature Scaling

Applied StandardScaler to standardize feature values before clustering.


## Model Building

### Machine Learning Algorithm

* K-Means Clustering

### Segmentation Process

* Imported KMeans from Scikit-learn
* Created a K-Means model with 4 clusters
* Trained the model using scaled customer data
* Assigned cluster labels to customers

### Number of Clusters

* 4 Customer Segments


## Results

Successfully grouped customers into 4 distinct clusters based on purchasing behavior and demographic characteristics.

Each cluster represents customers with similar spending habits and engagement patterns.


## Project Screenshots

### Dataset Preview

Dataset Preview

### Dataset Information

Dataset Information

### Summary Statistics

Summary Statistics

### Missing Values Check

Missing Values Check

### Annual Income Distribution

Income Histogram

### Spending Score Distribution

Spending Score Histogram

### Income vs Spending Scatter Plot

Scatter Plot

### Clustered Customer Data

Cluster Results


## Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab


## Learning Outcomes

Through this project, I learned:

* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Selection
* Feature Scaling using StandardScaler
* Unsupervised Machine Learning
* K-Means Clustering
* Customer Segmentation Techniques
* Business Applications of Machine Learning


## Author

Yash Agarwal

B.Tech Computer Science Engineering, JIIT
