# Day 38 – Feature Scaling

## 📌 Concepts Covered:
- **Normalization (Min-Max Scaling)**
- **Standardization (Z-score Scaling)**

---

## 🧾 Normalization (Min-Max Scaling)

- Used when features have different ranges.  
- Scales data to a fixed range, typically [0, 1].  

**Formula:**  
**X' = (X - X_min) / (X_max - X_min)**  

**When to Use:**  
- When the data **isn't normally distributed**.  
- Suitable for algorithms like **KNN, Neural Networks, Logistic Regression**.

---

## 🧾 Standardization (Z-score Scaling)

- Centers data around the mean with unit variance.  

**Formula:**  
**Z = (X - μ) / σ**  

**When to Use:**  
- When data **follows a normal distribution**.  
- Common in algorithms like **SVM, PCA, Linear Regression**.

---

## 🧠 Advanced Concept: Robust Scaling

- Handles **outliers** by using median and interquartile range (IQR).  

**Formula:**  
**X' = (X - Median) / IQR**

**When to Use:**  
- When the dataset has significant **outliers**.  

---

