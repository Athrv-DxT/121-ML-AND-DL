# Day 36 – Cross Validation (K-Fold CV)

## 📌 Concepts Covered:
- **Cross Validation** and its importance  
- **K-Fold Cross Validation**  
- **Stratified K-Fold Cross Validation**  
- **Performance Visualization using Accuracy Scores**

---

## 🧾 Cross Validation Overview

- Cross Validation helps evaluate model performance by splitting data into multiple folds.  
- It reduces overfitting by ensuring that every data point gets a chance to be in both training and testing sets.  

**Key Idea:**  
Instead of one train-test split, perform multiple splits and average the results.  

**Formula (K-Fold Mean Accuracy):**  
**Accuracy (avg) = (1 / K) Σ Accuracyₖ**  
where `K` = number of folds and `Accuracyₖ` = accuracy for fold *k*.

---

## 🧾 Stratified K-Fold

- A variant of K-Fold used for **classification tasks**.  
- Ensures each fold has the **same class proportion** as the overall dataset.  

**Formula (Mean Stratified Accuracy):**  
**Stratified Accuracy (avg) = (1 / K) Σ Accuracyₖ (with class balance)**

---

## 🧾 Visualization

- After evaluating folds, plot accuracy scores to observe model stability across different splits.  
- Helps identify performance variation between folds.

---

## 🔑 Key Insights

- **K-Fold CV:** Improves reliability of model performance estimates.  
- **Stratified K-Fold:** Handles imbalanced datasets effectively.  
- **Visualization:** Provides clarity on accuracy consistency across folds.

---
