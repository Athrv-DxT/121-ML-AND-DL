# Day 51 — Clustering Intro: K-Means Coding

## 🧠 Overview
This notebook introduces **Clustering**, an *unsupervised learning technique*, using the **K-Means algorithm**.  
The main goal is to group similar data points without using predefined labels.  
We explore this concept using the **Iris dataset**, one of the most classic datasets for clustering tasks.

---

## 📚 Concepts Covered
- Understanding Clustering and Unsupervised Learning  
- Introduction to the K-Means Algorithm  
- Finding Optimal Number of Clusters (Elbow Method)  
- Data Standardization and PCA Visualization  
- Cluster Analysis and Interpretation  

---

## 🧩 Dataset
**Dataset Used:** *Iris Dataset* from `sklearn.datasets`  
- Features: Sepal Length, Sepal Width, Petal Length, Petal Width  
- Samples: 150  
- Classes (hidden in unsupervised setup): 3 (Setosa, Versicolor, Virginica)

---

## 🧮 Steps Implemented
1. Loaded and explored the dataset  
2. Standardized the data using `StandardScaler`  
3. Used the **Elbow Method** to determine the optimal `k`  
4. Applied **K-Means Clustering** with `k=3`  
5. Visualized results using **PCA (2D projection)**  
6. Analyzed cluster centroids and feature means  

---
