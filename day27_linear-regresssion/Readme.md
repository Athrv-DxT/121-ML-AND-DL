# Day 27 → Linear Regression (Simple & Multiple)

## Concepts Covered
- **Simple Linear Regression**: One independent variable → One dependent variable  
  Formula:  
  **y = β₀ + β₁x + ε**

- **Multiple Linear Regression**: Multiple independent variables → One dependent variable  
  Formula:  
  **y = β₀ + β₁x₁ + β₂x₂ + ... + βₙxₙ + ε**

## Steps in Code
1. Load **California Housing Dataset**.
2. Split data into **train** & **test** sets.
3. Train **LinearRegression model** using sklearn.
4. Evaluate using **MSE** & **R² Score**.
5. Visualize:
   - Regression line for Simple Regression
   - Feature coefficients for Multiple Regression  

## Evaluation Metrics
- **MSE**: Measures average squared error.
- **R² Score**: Proportion of variance explained by the model.
