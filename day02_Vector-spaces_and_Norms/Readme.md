# Day 2: Vector Spaces & Norms  

## 📌 Agenda
- Introduction to Vector Spaces  
- Basis and Dimension  
- Linear Independence & Span  
- Norms (L1, L2, ∞ norm)  
- Applications in Machine Learning  

## 🧾 Key Concepts  

### 🔹 Vector Spaces  
- A **vector space** is a collection of vectors that can be scaled and added together, following certain rules (axioms).  
- Examples:  
  - ℝ² → 2D vectors like (x, y)  
  - ℝ³ → 3D vectors like (x, y, z)  
  - Polynomial functions  

### 🔹 Basis and Dimension  
- **Basis**: A set of vectors that are linearly independent and span the entire vector space.  
- **Dimension**: The number of vectors in the basis.  

### 🔹 Linear Independence  
- Vectors are linearly independent if none of them can be written as a linear combination of the others.  

### 🔹 Norms  
Norms measure the **size/length** of a vector.  
- **L1 Norm (Manhattan Distance)**  
  \[
  ||x||_1 = \sum |x_i|
  \]  
- **L2 Norm (Euclidean Distance)**  
  \[
  ||x||_2 = \sqrt{\sum x_i^2}
  \]  
- **Infinity Norm**  
  \[
  ||x||_\infty = \max(|x_i|)
  \]  

### 🔹 Why Norms Matter in ML?  
- Used in **regularization** (L1 → Lasso, L2 → Ridge).  
- Measure error or distance in optimization.  
- Feature scaling and normalization.  

## 💻 Example Code (Python)
```python
import numpy as np

# Example vector
v = np.array([3, 4, -5])

# L1 Norm
l1 = np.linalg.norm(v, 1)

# L2 Norm
l2 = np.linalg.norm(v, 2)

# Infinity Norm
linf = np.linalg.norm(v, np.inf)

print("L1 Norm:", l1)
print("L2 Norm:", l2)
print("Infinity Norm:", linf)
