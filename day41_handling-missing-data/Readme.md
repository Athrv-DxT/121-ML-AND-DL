# 📘 Day 41: Handling Missing Data (Imputation Coding)

## 📌 Agenda
- Understanding Missing Data  
- Visualizing Missingness  
- Simple Imputation (Mean, Median, Mode)  
- Advanced Imputation (KNN, Iterative/MICE)  
- Evaluating Impact on Model Performance  

---

## 🧾 Key Concepts

### 🔹 What is Missing Data?
Missing data occurs when no value is stored for a variable in an observation.  
It can arise due to data entry errors, sensor failure, or incomplete surveys.

**Types of Missingness:**
1. **MCAR (Missing Completely at Random):** Missingness is independent of any variable.  
2. **MAR (Missing at Random):** Missingness depends on other observed variables.  
3. **MNAR (Missing Not at Random):** Missingness depends on the unobserved variable itself.

---

## 🔹 Visualizing Missing Data
Before imputing, it’s crucial to **visualize missing patterns**.
