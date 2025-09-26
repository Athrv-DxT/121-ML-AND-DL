# Day 26: Introduction to Machine Learning (California Housing Dataset)

## Topics Covered
- Overview of Machine Learning basics
- Data loading & exploration
- Data visualization
- Linear Regression model
- Model evaluation using metrics

## Dataset
used the **California Housing dataset**, containing features like:
- MedInc: Median Income
- HouseAge: Average Age of Houses
- AveRooms: Average Rooms per Household
- Population, AveOccup, Latitude, Longitude, etc.
- Target: MedHouseVal (Median House Value)

## Key Formulas
- **Mean Squared Error (MSE):**  
  MSE = (1/n) Σ (yᵢ - ŷᵢ)²  

- **R² Score (Coefficient of Determination):**  
  R² = 1 - (Σ(yᵢ - ŷᵢ)² / Σ(yᵢ - ȳ)²)

Where yᵢ = actual value, ŷᵢ = predicted value, ȳ = mean of actual values.

## Steps Performed
1. Data loading and summary statistics
2. Correlation heatmap & target distribution visualization
3. Train-test splitting (80-20)
4. Linear Regression model training
5. Model evaluation using MSE & R²
6. Visualization of actual vs predicted house values

## Results
- **MSE:** Lower value indicates better model fit  
- **R² Score:** Closer to 1 indicates stronger model performance  

## Applications in ML
- Understanding model interpretability
- Building regression models for real-world datasets
- Basis for advanced algorithms (Decision Trees, Random Forests, etc.)

---
