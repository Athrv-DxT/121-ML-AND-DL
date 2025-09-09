# Day 10: Quadratic Forms & Loss Surfaces Visualization  

## 📌 Agenda  
- Quadratic Forms  
- Loss Surface Equations  
- Practical Usage in Machine Learning  

---

## 🧾 Key Concepts  

### 🔹 Quadratic Forms  
- Mathematical representation:  
  Q(x) = xᵀ A x  
- General quadratic function:  
  f(x) = xᵀ A x + bᵀ x + c  
- Where A is a symmetric matrix, x is a vector, and c is a constant term.  

---

### 🔹 Loss Function for Regression  
- Mean Squared Error (MSE) Loss:  
  L(w) = ½ (Xw − y)ᵀ (Xw − y)  
- Where:  
  - X = Input features  
  - w = Weights  
  - y = Target values  

---

### 🔹 Convexity Condition  
- If A ≻ 0 (A is positive definite), then:  
  Q(x) = xᵀ A x is **convex** → guarantees a unique global minimum.  

---

### 🔹 Gradient & Optimization  
- Gradient of L(w):  
  ∇L(w) = Xᵀ(Xw − y)  
- Setting gradient = 0 → Optimal weights w*:  
  w* = (XᵀX)⁻¹ Xᵀ y  

---

### 🔹 Applications in ML  
1. **Linear Regression:** Loss function is quadratic → Convex optimization.  
2. **PCA:** Eigenvalue problems use quadratic forms for variance maximization.  
3. **SVMs:** Quadratic programming solves the margin maximization problem.  
4. **Neural Networks:** Loss surface analysis aids in optimization & training stability.  

---
