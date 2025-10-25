# Day 55 – t-SNE (Visualization Coding)

## Overview
This notebook demonstrates **t-Distributed Stochastic Neighbor Embedding (t-SNE)** using the **Digits dataset** from scikit-learn.  
t-SNE is a nonlinear dimensionality reduction technique mainly used for **visualizing high-dimensional data** in 2D or 3D.

## Steps Covered
1. Loaded the **Digits dataset** from sklearn.  
2. Standardized the data using **StandardScaler**.  
3. Applied **t-SNE** for 2D visualization.  
4. Visualized clusters of digits using Seaborn.  

## Why t-SNE?
- Captures complex, nonlinear relationships in data.  
- Ideal for visualizing high-dimensional embeddings.  
- Commonly used in NLP, image recognition, and deep learning models to visualize hidden layers.

## Results
- Digits dataset projected into 2D space.  
- Clear clustering observed for different digit classes.  
- Showcases how t-SNE groups similar data points closely together.
