# 📘 Day 13: Probability Basics  

## 📌 Agenda  
- Events and Probability  
- Conditional Probability  
- Simulations using Python  
- Law of Total Probability  

---

## 🧾 Key Concepts  

### 🔹 Basic Probability  
- Probability of an event \( A \):  
  P(A) = Number of favorable outcomes / Total number of outcomes  

---

### 🔹 Complementary Events  
- Probability of the complement of \( A \):  
  P(A') = 1 − P(A)  

---

### 🔹 Union & Intersection  
- Probability of union:  
  P(A ∪ B) = P(A) + P(B) − P(A ∩ B)  

- Probability of intersection:  
  P(A ∩ B) = P(A|B) × P(B)  

---

### 🔹 Conditional Probability  
- Formula:  
  P(A|B) = P(A ∩ B) / P(B)  

---

### 🔹 Law of Total Probability  
- Formula:  
  P(A) = P(B₁)P(A|B₁) + P(B₂)P(A|B₂) + ... + P(Bₙ)P(A|Bₙ)  

---

### 🔹 Simulations in Python  
- Example: Coin Toss Simulation  
- Estimated Probability:  
  P(Heads) ≈ Number of Heads / Total Tosses  

---

### 🔹 Applications in Machine Learning  
1. **Bayesian Inference** – Used in probabilistic models.  
2. **Naive Bayes Classifier** – Relies on conditional probability.  
3. **Uncertainty Quantification** – Essential in predictive modeling.  
4. **Monte Carlo Simulations** – Estimate probabilities using random sampling.  
