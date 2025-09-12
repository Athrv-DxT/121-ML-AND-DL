# 📘 Day 12: Recap of Linear Algebra from Day 01 to Day 11 + Mini Project

## 📌 Agenda  
- Matrix Addition, Multiplication & Transpose  
- Rank & Null Space  
- Eigenvalues & Eigenvectors  
- Cholesky, LU, QR, and SVD Decomposition  
- Mean Squared Error (MSE) Loss  
- Gradients & Jacobians  
- Mini Project using above concepts

---

## 🧾 Key Concepts  

### 🔹 Matrix Operations  
- Matrix Addition:  C = A + B  
- Matrix Multiplication:  C = A × B  
- Transpose:  Aᵀ  

---

### 🔹 Rank & Null Space  
- Rank of a matrix:  rank(A) = dimension of column space  

---

### 🔹 Eigenvalues & Eigenvectors  
- For A v = λ v  
- λ are eigenvalues, v are eigenvectors  

---

### 🔹 Decompositions  

1. **Cholesky Decomposition:**  
   A = L Lᵀ  

2. **LU Decomposition:**  
   A = L U  

3. **QR Decomposition:**  
   A = Q R  

4. **Singular Value Decomposition (SVD):**  
   A = U Σ Vᵀ  

---

### 🔹 Mean Squared Error (MSE) Loss  
- Formula:  MSE = (1/n) Σ (yᵢ − ŷᵢ)²  

---

### 🔹 Gradients & Jacobians  
- Gradient of f(x, y):  ∇f = [∂f/∂x, ∂f/∂y]  
- Jacobian for vector-valued function F(x): J = [∂Fᵢ/∂xⱼ]  

---

### 🔹 Applications in Machine Learning  
1. **Optimization:** Gradient Descent uses gradients to minimize loss.  
2. **PCA & Dimensionality Reduction:** Based on eigenvalues & SVD.  
3. **Regression Models:** MSE as loss function.  
4. **Numerical Computations:** LU, QR, and SVD for solving systems efficiently.  

---
