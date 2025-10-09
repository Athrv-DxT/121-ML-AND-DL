# 📘 Day 39: Feature Selection – Filter & Wrapper Methods

## 📌 Agenda  
- Load Dataset  
- Filter Methods  
  - Correlation  
  - Chi-Square Test  
  - ANOVA F-test  
  - Mutual Information  
- Wrapper Methods  
  - Recursive Feature Elimination (RFE)  
- Embedded / Advanced Methods  
  - Random Forest Feature Importance  
- Model Accuracy Comparison  

---

## 🧾 Key Concepts  

### 🔹 Feature Selection
Feature selection helps improve model performance by selecting the most relevant features and removing redundant or irrelevant ones.  

---

### 🔹 Filter Methods
**Independent of any model**, these use statistical measures to rank features:

1. **Correlation**: Measures linear relationship between features.  
2. **Chi-Square Test**: Compares categorical features with target.  
3. **ANOVA F-test**: Measures relationship between continuous features and categorical target.  
4. **Mutual Information**: Measures dependency between features and target.

---

### 🔹 Wrapper Methods
**Model-dependent**. Select features based on model performance:

- **RFE (Recursive Feature Elimination)**: Recursively removes least important features based on estimator.  

---

### 🔹 Embedded / Advanced Methods
**Feature importance extracted from model training**:

- Tree-based models (Random Forest, XGBoost) provide importance scores.  
- Combines feature selection and model fitting in one step.  

---
