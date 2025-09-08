# 📘 Day 8: Projections & Least Squares  

## 📌 Agenda  
- Projection Matrices  
- Least Squares Solution (Normal Equation)  
- Linear Regression using NumPy & scikit-learn  
- Visualization & Applications in ML  

---

## 🧾 Key Concepts  

### 🔹 Projection Matrices  
- A projection matrix projects a vector onto the column space of a matrix \( X \).  
- Formula:  
  P = X(XᵀX)⁻¹Xᵀ  
- Properties:  
  - P² = P (idempotent)  
  - Pᵀ = P (symmetric)  

---

### 🔹 Least Squares Solution  
- Objective: Minimize the squared error ||y − Xθ||².  
- Formula (Normal Equation):  
  θ = (XᵀX)⁻¹Xᵀy  
- Geometric Interpretation: y is projected onto the column space of X.  

---

### 🔹 Linear Regression Relations  
- Predictions:  ŷ = X_b θ  
- Residuals:  r = y − ŷ  

---

### 🔹 Visualization  
- **Data points (blue):** Original data  
- **Regression line (red):** Best-fit line using least squares  
- **Residuals (green):** Error between actual \( y \) and predicted \( \hat{y} \)  

---

### 🔹 Applications in Machine Learning  

1. **Linear Regression:**  
   - Projection matrices give the best linear fit minimizing error.  
   - Basis for many regression-based models.  

2. **Dimensionality Reduction:**  
   - Project data onto lower-dimensional subspaces while retaining information.  

3. **Noise Reduction:**  
   - Projection keeps the signal in the subspace, removing orthogonal noise.  

4. **Optimization & Estimation:**  
   - Used in least squares estimation, curve fitting, and statistical inference.  


