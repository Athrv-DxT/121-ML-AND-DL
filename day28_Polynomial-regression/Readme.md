# Day 28 → Polynomial Regression

## Concepts Covered
- **Feature Engineering**: Using Polynomial Features for non-linear relationships.
- **Model Training**: LinearRegression on transformed polynomial data.

### Formula
For degree 2 polynomial regression:  
**y = β₀ + β₁x + β₂x² + ε**

## Steps in Code
1. Generate synthetic dataset with quadratic relation.
2. Transform features using **PolynomialFeatures(degree=2)**.
3. Train **LinearRegression model**.
4. Evaluate using **MSE** & **R² Score**.
5. Visualize polynomial regression curve.

## Evaluation Metrics
- **MSE**: Measures average squared error.
- **R² Score**: Proportion of variance explained by the model.
