# Day 33: Random Forests

## Concept
Random Forest is an **ensemble learning method** that builds multiple decision trees and combines their results to improve accuracy and reduce overfitting.  

It works by:
- Bagging (Bootstrap Aggregation)
- Random feature selection at each split

## Formula

For a Random Forest classifier, the final prediction is made using **majority voting**:

**ŷ = mode(h₁(x), h₂(x), …, hₖ(x))**

For regression tasks, the final prediction is the **average of predictions**:

**ŷ = (1/K) Σ hᵢ(x)**

Where:
- **hᵢ(x)** → Prediction from the *i-th* decision tree  
- **K** → Total number of trees in the forest  

## Key Parameters
- `n_estimators`: Number of trees in the forest  
- `max_depth`: Maximum depth of each tree  
- `max_features`: Number of features to consider when looking for the best split  
- `oob_score`: Out-of-Bag score for validation  

## Applications
- Classification & Regression
- Feature importance analysis
- Handling missing values & noisy datasets
