# Day 7: Rank & Null Space  

## 📌 Agenda  
- Matrix Rank  
- Null Space Concept  
- Applications in Machine Learning  

## 🧾 Key Concepts  

### 🔹 Matrix Rank  
- Rank of a matrix is the dimension of its column space (or row space).  
- Formula: rank(A) = number of linearly independent columns in A.  
- **Importance in ML:** Determines the amount of useful information in data, helps in solving systems of equations, and affects matrix invertibility.  

---

### 🔹 Null Space  
- Null space (or kernel) of a matrix A is the set of all vectors x such that A·x = 0.  
- **Importance in ML:** Identifies redundant features in data, helps in dimensionality reduction, and plays a role in optimization problems.  

---

### 🔹 Applications in ML  
- **Feature Selection:** Helps remove redundant features, reducing dimensionality.  
- **Data Compression:** Finds low-rank approximations for large datasets (e.g., PCA, SVD).  
- **Optimization Problems:** Null space helps identify constraints in linear optimization tasks.  
- **Control Systems & Signal Processing:** Used in system controllability and filtering techniques.  
