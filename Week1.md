# 📘 Week 1: Linear Algebra for Machine Learning (Days 1–7)

This week focused on the fundamental linear algebra concepts required for Machine Learning, covering vector spaces, norms, eigenvalues, SVD, orthogonality, rank, and more.  
We explored theory, Python implementations, and real-world ML applications.

---

## 📅 Day-wise Topics  

- **Day 1:** Matrix Fundamentals, Vector Spaces, Basis, Dimension  
- **Day 2:** Norms (L1, L2, p-Norms), Applications in ML  
- **Day 3:** Eigenvalues, Eigenvectors & PCA Basics  
- **Day 4:** Diagonalization & Eigen Decomposition  
- **Day 5:** Singular Value Decomposition (SVD)  
- **Day 6:** Orthogonality & QR Decomposition  
- **Day 7:** Rank & Null Space  

---

## 🧾 Key Concepts & ML Applications  

### 🔹 Day 1 & 2: Vector Spaces & Norms
- **Vector Spaces:** Collections of vectors where scaling & addition hold true. Examples: ℝ², ℝ³, polynomial functions.  
- **Basis & Dimension:** Minimum set of independent vectors spanning a space; dimension = number of basis vectors.  
- **Norms:**  
  - L1 Norm → Manhattan distance  
  - L2 Norm → Euclidean distance  
  - p-Norm → Generalized norm  

**ML Applications:**  
- **Regularization:** L1 → Lasso, L2 → Ridge regression for reducing overfitting.  
- **Error Measurement:** Norms used as loss functions (e.g., MSE uses L2 norm).  
- **Feature Scaling:** Normalization ensures stable gradient descent optimization.  

---

### 🔹 Day 3: Eigenvalues, Eigenvectors & PCA Basics
- **Eigenvalues:** Indicate scaling factors in linear transformations.  
- **Eigenvectors:** Directions along which scaling happens.  
- **PCA:** Uses eigen decomposition to find directions of maximum data variance.

**ML Applications:**  
- **Dimensionality Reduction:** PCA speeds up training and reduces noise.  
- **Data Visualization:** Projects high-dimensional data to 2D or 3D.  
- **Stability Analysis:** Used in numerical optimization algorithms.  

---

### 🔹 Day 4: Diagonalization & Eigen Decomposition
- **Diagonalization:** Express A as A = P D P⁻¹, where D is diagonal with eigenvalues, P contains eigenvectors.  
- **Eigen Decomposition:** Factorizes a matrix into eigenvalues & eigenvectors.

**ML Applications:**  
- **Simplifies Matrix Computations:** Faster exponentiation & power calculations.  
- **Feature Transformation:** PCA uses this for dimensionality reduction.  
- **System Modeling:** Used in optimization and dynamic systems analysis.  

---

### 🔹 Day 5: Singular Value Decomposition (SVD)
- Factorizes A into U Σ Vᵀ where Σ contains singular values sorted by importance.  

**ML Applications:**  
- **Image Compression:** Keeps top singular values for reduced storage.  
- **Recommendation Systems:** Collaborative filtering via latent factor analysis.  
- **Noise Reduction:** Smaller singular values often represent noise; removing them denoises data.  
- **PCA Computation:** PCA internally uses SVD for efficiency.  

---

### 🔹 Day 6: Orthogonality & QR Decomposition
- **Orthogonality:** Vectors at right angles (dot product = 0); orthonormal vectors have unit length too.  
- **QR Decomposition:** Factorizes A into Q (orthogonal) and R (upper triangular).  

**ML Applications:**  
- **Least Squares Regression:** QR decomposition solves Ax=b efficiently without direct matrix inverse.  
- **Gradient Optimization:** Orthogonal projections used in optimization algorithms.  
- **Numerical Stability:** Used in iterative solvers and ML algorithms requiring matrix inversion.  

---

### 🔹 Day 7: Rank & Null Space
- **Rank:** Number of linearly independent columns/rows in a matrix → info content of data.  
- **Null Space:** All solutions to A·x = 0 → indicates redundancy in data.  

**ML Applications:**  
- **Feature Selection:** Remove dependent/redundant features to reduce model complexity.  
- **Low-Rank Approximation:** Large datasets compressed for faster training.  
- **Optimization Problems:** Null space helps find feasible solution directions in constrained ML models.  

---
