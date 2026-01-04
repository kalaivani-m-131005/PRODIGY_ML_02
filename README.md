PRODIGY_ML_02
Customer Segmentation using K-Means Clustering
📌 Project Overview
This project is part of my Machine Learning internship at Prodigy InfoTech. The goal is to create a K-Means clustering algorithm to group customers of a retail store based on their purchase history, specifically focusing on Annual Income and Spending Score.

📊 Dataset
The dataset used is the Mall Customers Dataset from Kaggle.

Features used:

Annual Income (k$): Total yearly income of the customer.

Spending Score (1-100): A score assigned by the mall based on customer behavior and spending nature.

🛠️ Technologies Used
Python

Pandas (Data Loading)

Matplotlib / Seaborn (Data Visualization)

Scikit-Learn (K-Means Implementation)

🚀 Implementation Steps
Data Preparation: Loading the Mall_Customers.csv and selecting relevant features (Income and Spending Score).

Finding Optimal Clusters: Using the Elbow Method to determine the best number of clusters (k=5).

Model Training: Applying the KMeans algorithm to the dataset.

Visualization: Plotting a scatter plot to show the 5 different customer segments and their centroids.

📈 Results
The model successfully grouped customers into 5 distinct categories:

High Income, High Spending (Target Customers)

High Income, Low Spending (Careful)

Average Income, Average Spending (Standard)

Low Income, High Spending (Careless)

Low Income, Low Spending (Sensible)
