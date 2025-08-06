🛍️ Customer Segmentation Using K-Means Clustering
This project implements a K-Means Clustering algorithm to group retail store customers based on their purchase behavior. The goal is to identify distinct customer segments that can help in targeted marketing, personalized offers, and business growth.

📦 Dataset
Source: Kaggle - Customer Segmentation Tutorial

File: Mall_Customers.csv

Description: This dataset contains basic demographic information and shopping behavior of customers at a mall.

📌 Features Used:
CustomerID: Unique ID for each customer

Gender: Male/Female

Age: Customer's age

Annual Income (k$): Estimated annual income

Spending Score (1-100): Score assigned by the store based on customer behavior and spending nature

🎯 Objective
Use unsupervised learning to identify meaningful customer groups

Apply K-Means Clustering

Visualize and interpret the formed clusters

Help the retail store understand different customer profiles for better decision-making

⚙️ Techniques Used
Data Preprocessing: Handling missing data (if any), scaling features

Elbow Method: To find the optimal number of clusters

KMeans Clustering: Applied using sklearn.cluster.KMeans

Visualization: 2D and 3D visualizations using Matplotlib and Seaborn

📚 Libraries Used
pandas – for data loading and manipulation

numpy – for numerical operations

matplotlib – for plotting clusters and elbow method

seaborn – for enhanced visualization

sklearn – for KMeans clustering and preprocessing
