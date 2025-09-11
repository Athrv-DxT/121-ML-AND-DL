# Day 11: Matrix Calculus Basics  

## 📌 Agenda  
- Introduction to Gradients & Jacobians  
- Manual computation for scalar and vector functions  
- Gradient Descent Visualization  
- Applications in Machine Learning  

---

## 🧾 Key Concepts  

### 🔹 Gradient  
- The gradient of a scalar function measures the rate of change of the function with respect to each variable.  
- Formula:  
  ∇f(x) = [ ∂f/∂x₁ , ∂f/∂x₂ , ..., ∂f/∂xₙ ]ᵀ  
- Example: For f(x, y) = x² + y²,  
  ∇f(x, y) = [ 2x , 2y ]ᵀ  

---

### 🔹 Jacobian  
- For a vector-valued function f: ℝⁿ → ℝᵐ, the Jacobian is the matrix of first-order partial derivatives.  
- Formula:  
  J = [ ∂fᵢ / ∂xⱼ ]  
- Example: For f(x, y) = [ x² + y , x*y ],  
  J = [ [2x, 1], [y, x] ]  

---

### 🔹 Gradient Descent  
- Iterative optimization algorithm to minimize functions.  
- Formula:  
  xₖ₊₁ = xₖ − α ∇f(xₖ)  
  where α = learning rate  

---

### 🔹 Application in ML: Linear Regression  
- Loss function (Mean Squared Error):  
  L(w) = (1/m) Σ (y - Xw)²  
- Gradient w.r.t. weights:  
  ∇w = −(2/m) Xᵀ (y − Xw)  
- Used in gradient-based optimization algorithms for training ML models.  

---

## 🔹 Usage in ML  

1. **Training Models:**  
   - Gradients are used in backpropagation for training neural networks.  

2. **Optimization:**  
   - Gradient descent and its variants (SGD, Adam) rely on these concepts.  

3. **Regression & Classification:**  
   - Computing loss gradients helps minimize errors in prediction models.  

4. **Deep Learning:**  
   - Automatic differentiation tools like TensorFlow/PyTorch compute gradients internally using these formulas.  

---
