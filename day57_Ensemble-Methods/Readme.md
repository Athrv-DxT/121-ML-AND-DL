# 📘 Day 57 – Ensemble Models (Stacking and Voting)

## 🧩 Concepts Covered
- Combining multiple models for improved accuracy
- **Voting Classifier** – majority or weighted voting between base models
- **Stacking Classifier** – meta-model learns how to best combine base model predictions
- Performance comparison on the Iris dataset

---

## 🧠 Concept Summary

**Ensemble Learning** combines predictions from multiple models to improve performance and generalization.

### Types:
1. **Voting:** Combines model outputs by majority (hard) or probability average (soft).  
2. **Stacking:** Uses a meta-model to learn the best combination of base models.

---

## ⚙️ Steps:
1. Load **Iris Dataset**.  
2. Split data and scale features.  
3. Train base models:
   - Logistic Regression  
   - Random Forest  
   - Gradient Boosting  
4. Apply:
   - **VotingClassifier** for ensemble averaging  
   - **StackingClassifier** for meta-learning  
5. Compare accuracies.
