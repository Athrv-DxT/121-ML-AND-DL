# Day 9: Positive Definite Matrices  

## 📌 Agenda  
- Understanding Positive Definite (PD) Matrices  
- Covariance Matrices in Machine Learning  
- Cholesky Decomposition  
- Visualization with heatmap

---

## 🧾 Key Concepts  

### 🔹 Positive Definite Matrices  
- A symmetric matrix **A** is **positive definite** if:  
  xᵀ A x > 0 for all x ≠ 0  

- **Properties:**  
  1. All eigenvalues λᵢ > 0  
  2. Determinant det(A) > 0  
  3. Diagonal entries aᵢᵢ > 0  

---

### 🔹 Covariance Matrices  
- A covariance matrix Σ is always **symmetric** and **positive semi-definite**.  
- Formula for covariance between two variables X and Y:  
  Cov(X,Y) = E[(X - μₓ)(Y - μᵧ)]  

- In matrix form for n samples:  
  Σ = (1 / n) * (X - μ)ᵀ(X - μ)  

---

### 🔹 Cholesky Decomposition  
- Factorizes a positive definite matrix A into:  
  A = L Lᵀ  
  where L is a **lower triangular** matrix.  

- Used in optimization, sampling, and solving linear systems efficiently.  

---

### 🔹 Applications in ML  

1. **Gaussian Processes:**  
   Covariance matrices in Gaussian Processes must be positive definite to ensure valid probability distributions.  

2. **Optimization Algorithms:**  
   Many optimization methods rely on PD Hessian matrices for convergence guarantees.  

3. **Numerical Stability:**  
   Cholesky decomposition helps solve linear systems stably and efficiently without directly computing inverses.  

---
