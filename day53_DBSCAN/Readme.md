# Day 53 – DBSCAN Clustering (Density-Based Clustering Coding)

## Overview
This notebook demonstrates **DBSCAN Clustering** on the **Wine dataset** (available directly from `sklearn.datasets`).  
It groups wines based on chemical composition and identifies noise points (outliers).

## Steps Covered
1. Loaded the real-world **Wine dataset** from scikit-learn.
2. Scaled the features using **StandardScaler**.
3. Applied **DBSCAN algorithm** (`eps=1.8`, `min_samples=5`).
4. Reduced dimensionality using **PCA** for visualization.
5. Visualized the clusters and analyzed noise/outliers.

## Why DBSCAN?
- Works well with **arbitrary-shaped clusters**.  
- Detects **outliers** automatically.  
- No need to specify the number of clusters in advance.

## Libraries Used
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- scikit-learn  

## Results
- Successfully identified natural clusters in the wine data.  
- Detected several **noise samples** not belonging to any group.  


