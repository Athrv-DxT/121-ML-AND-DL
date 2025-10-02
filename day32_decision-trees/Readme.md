# Day 32 – Decision Trees 🌳

### 📝 Concept
Decision Trees are supervised learning models used for **classification and regression**.  
They split the dataset into subsets based on feature values using measures of impurity.

---

### 📌 Formulas

- **Entropy:**  **Entropy(S) = - Σ pᵢ log₂(pᵢ)**  
- **Information Gain:**  **IG(S, A) = Entropy(S) - Σ (|Sᵥ| / |S|) × Entropy(Sᵥ)**  
- **Gini Index:**  **Gini(S) = 1 - Σ (pᵢ)²**

---

### ⚡ Key Notes
- Splitting stops when:
  - All samples belong to one class  
  - Or max depth/pruning criteria is reached  
- Trees are prone to **overfitting** → solved by pruning or limiting depth.  
- **Feature importance** can be extracted after training.  
