# Day 54 – PCA (Dimensionality Reduction Coding)

## Overview
This notebook demonstrates **Principal Component Analysis (PCA)** using the **Wine dataset** from scikit-learn.  
PCA is used for reducing high-dimensional data to lower dimensions while preserving as much variance as possible.

## Steps Covered
1. Loaded the **Wine dataset** (real dataset from sklearn).
2. Standardized features using **StandardScaler**.
3. Applied **PCA** with 2 components.
4. Visualized the reduced dimensions with class coloring.
5. Checked explained variance and feature loadings.

## Why PCA?
- Reduces data complexity while maintaining structure.
- Helps visualize high-dimensional data.
- Useful for speeding up machine learning models.
- Minimizes noise and redundancy in correlated features.

## Results
- First two components explained **~55–60% of total variance**.  
- PCA visualization showed distinct grouping of wine types.  
- PCA loadings revealed feature importance per component.


