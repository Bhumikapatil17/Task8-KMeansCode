📌 Project Title:

K-Means Clustering on Iris Dataset – Unsupervised Machine Learning

📘 Overview

This project demonstrates unsupervised learning using the K-Means clustering algorithm.
The popular Iris dataset is used to perform clustering, visualize groupings, and evaluate the quality of clusters using Silhouette Score.

K-Means is one of the most widely used clustering techniques in Machine Learning, helping group similar data points without needing labels.

🎯 Objectives

Apply the K-Means clustering algorithm

Use the Elbow Method to find the optimal number of clusters (K)

Visualize clusters using PCA (2D projection)

Evaluate model performance using Silhouette Score

Understand key concepts of unsupervised learning

🛠️ Tools & Libraries Used

Python 3

Pandas

NumPy

Matplotlib

Scikit-learn (sklearn)

KMeans

StandardScaler

Silhouette Score

PCA

Iris Dataset Loader

📊 Dataset Used
Iris Dataset (Built-in Scikit-learn Dataset)

Contains 150 samples of iris flowers with 4 features each:

Sepal Length

Sepal Width

Petal Length

Petal Width

There are 3 natural classes, but clustering is performed without labels.

🧠 Project Workflow
1. Load Dataset

Use sklearn’s built-in Iris dataset.

2. Data Preprocessing

Extract features

Standardize using StandardScaler

3. Determine Optimal K (Elbow Method)

Plot WCSS (Within-Cluster Sum of Squares) for K=1 to 10.

4. Apply K-Means Algorithm

Fit the model using K = 3 (optimal for Iris).

5. Visualize Clusters

Reduce dimensions to 2D using PCA and plot.

6. Evaluate Model

Compute Silhouette Score to measure clustering quality.

📈 Results

The Elbow method suggests K = 3 clusters.

PCA visualization shows distinct cluster separation.

Silhouette Score indicates good clustering quality.
