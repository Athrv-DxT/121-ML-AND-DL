# Day 34 – Bagging & Boosting

## 📌 Concepts Covered:
- **Bagging (Bootstrap Aggregating)**  
- **Boosting: AdaBoost & Gradient Boosting**  

---

## 🧾 Bagging (Bootstrap Aggregating)

- Bagging builds multiple models independently and averages their predictions.  
- Reduces variance and helps avoid overfitting.  

**Formula (Bagging prediction):**  
**ŷ = (1 / B) Σ fᵢ(x)**  
where `B` = number of bootstrap models, and `fᵢ(x)` = prediction of model *i*.  

---

## 🧾 AdaBoost (Adaptive Boosting)

- Sequentially builds weak learners (usually decision stumps).  
- Each classifier is assigned a weight depending on accuracy.  
- Misclassified points get **higher weights** in the next round.  

**Weight update rule:**  
**wᵢ ← wᵢ * exp(αₜ * I(yᵢ ≠ hₜ(xᵢ)))**  

where:  
- `wᵢ` = weight of sample *i*  
- `αₜ = (1/2) * ln((1 - εₜ) / εₜ)` (classifier weight)  
- `εₜ` = error rate of classifier *t*  

---

## 🧾 Gradient Boosting

- Models are built sequentially to correct errors of previous models.  
- Each new model fits the **residuals (errors)** of the last.  

**Update rule:**  
**Fₘ(x) = Fₘ₋₁(x) + η * hₘ(x)**  

where:  
- `η` = learning rate  
- `hₘ(x)` = weak learner at step *m*  
- `Fₘ(x)` = boosted model after step *m*  

---

## 🔑 Key Differences

- **Bagging:** Parallel training, reduces variance.  
- **Boosting:** Sequential training, reduces bias & variance.  

---
