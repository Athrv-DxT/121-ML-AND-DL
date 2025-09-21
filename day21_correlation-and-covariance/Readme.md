# 📘 Day 21: Correlation & Covariance + Correlation Matrices Coding

## 📌 Agenda
- Understanding Covariance
- Understanding Correlation
- Covariance vs Correlation  
- Coding Correlation Matrices  

---

## 🧾 Key Concepts

### 🔹 Covariance
- Measures **direction** of the linear relationship between two variables.
- Formula: Cov(X, Y) = Σ (Xi - X̄)(Yi - Ȳ) / (n - 1)
- Positive → Variables move in the **same direction**.
- Negative → Variables move in the **opposite direction**.
- Magnitude not standardized → Difficult to compare across datasets.

---

### 🔹 Correlation
- Measures **strength & direction** of linear relationship.
- Formula: r = Cov(X, Y) / (σX * σY)
- Ranges from **-1 to 1**.
- Standardized → Easy to interpret and compare.

---

### 🔹 Covariance vs Correlation
- **Covariance**: Only shows direction; units depend on variables.  
- **Correlation**: Shows both **direction and strength**, standardized to [-1,1].  

---

### 🔹 Applications
1. Feature selection in ML.
2. Multicollinearity detection in regression.
3. Portfolio diversification in finance.

