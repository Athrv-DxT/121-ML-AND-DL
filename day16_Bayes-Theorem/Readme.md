# 📘 Day 16: Bayes Theorem & Applications

## 📌 Agenda
- Bayes Theorem basics  
- Law of Total Probability  
- Multiple hypotheses / normalization  
- Bayesian inference (Beta-Binomial) example  
- Prior sensitivity analysis  

---

## 🧾 Key Concepts

### 🔹 Bayes Theorem
- Bayes formula (posterior from prior and likelihood):  
  P(A|B) = (P(B|A) * P(A)) / P(B)

---

### 🔹 Law of Total Probability
- Compute evidence when multiple causes possible:  
  P(B) = Σ_i P(B|A_i) * P(A_i)

---

### 🔹 Multiple Hypotheses (normalized posterior)
- For hypotheses A1..An:  
  P(A_i|B) = (P(B|A_i) * P(A_i)) / Σ_j P(B|A_j) * P(A_j)

---

### 🔹 Bayesian Inference (Beta-Binomial for coin flips)
- Prior: Beta(alpha, beta)  
- Likelihood: Binomial( n, p ) from observed Heads/Tails  
- Posterior: Beta(alpha + Heads, beta + Tails)  
- Posterior mean:  
  E[p | Data] = (alpha + Heads) / (alpha + beta + n)

---

### 🔹 Prior Sensitivity
- Changing prior (alpha,beta) affects posterior when data is limited:
  - Weak prior (e.g., Beta(1,1)) → data dominates  
  - Strong prior (e.g., Beta(50,50)) → prior dominates until lots of data

---
