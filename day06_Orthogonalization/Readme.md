# Day 6: Orthogonalization & Gram-Schmidt Process  

## 📌 Agenda  
- Orthogonalization Concept  
- Gram-Schmidt Algorithm  
- Orthonormal Basis Coding & Visualization  
- Practical Applications in Machine Learning  

---

## 🧾 Key Concepts  

### 🔹 Orthogonalization  
- The process of converting a set of vectors into mutually perpendicular (orthogonal) vectors.  
- Helps in simplifying computations and reducing redundancy in data representation.  

---

### 🔹 Gram-Schmidt Algorithm  
- Takes a set of linearly independent vectors and generates an orthonormal basis.  
- Formula:  
  u1 = v1  
  u2 = v2 − proj(u1, v2)  
  u3 = v3 − proj(u1, v3) − proj(u2, v3) ...  
  where proj(ui, vj) = (v·ui / ui·ui) * ui  
- Final step: Normalize each vector to get orthonormal basis.  

---

### 🔹 Orthonormal Basis  
- A set of orthogonal vectors with unit length.  
- Ensures QᵀQ = I (Identity Matrix), which simplifies many matrix computations.  

---

### 🔹 Applications in ML  

1. **Feature Decorrelation:**  
   Gram-Schmidt can transform correlated features into uncorrelated ones, improving model performance in regression or PCA.  

2. **Dimensionality Reduction:**  
   Helps build orthonormal bases for techniques like PCA, making data representation more compact without losing key information.  

3. **QR Decomposition:**  
   Widely used in solving linear regression equations efficiently using matrix factorization (A = Q R).  

4. **Signal Processing & NLP:**  
   Used to generate orthonormal bases for noise reduction and extracting important features in text or audio data.  

---
