# 📘 Day 14: Random Variables & Distributions  

## 📌 Agenda  
- Discrete Random Variables (PMF)  
- Continuous Random Variables (PDF)  
- Expectation & Variance  
- Simulations & Visualizations  

---

## 🧾 Key Concepts  

### 🔹 Discrete Random Variable (PMF)  
- A **Discrete Random Variable** takes countable values with associated probabilities.  
- Formula:  
  P(X = x) = f(x),   Σ f(x) = 1  

---

### 🔹 Continuous Random Variable (PDF)  
- A **Continuous Random Variable** takes real values within an interval.  
- Probability is computed over an interval using integrals.  
- Formula:  
  P(a ≤ X ≤ b) = ∫[a to b] f(x) dx  

---

### 🔹 Expectation & Variance  
- **Expectation (Mean):**  
  E[X] = Σ x · P(X=x)   (Discrete)  
  E[X] = ∫ x · f(x) dx   (Continuous)  

- **Variance:**  
  Var(X) = E[X²] - (E[X])²  

---

### 🔹 Common Distributions  

1. **Bernoulli Distribution**  
   P(X = x) = p^x (1-p)^(1-x),   x ∈ {0,1}  

2. **Binomial Distribution**  
   P(X = k) = C(n,k) p^k (1-p)^(n-k)  

3. **Normal Distribution**  
   f(x) = 1 / √(2πσ²) · e^(-(x-μ)² / 2σ²)  

4. **Uniform Distribution**  
   f(x) = 1 / (b - a),   a ≤ x ≤ b  

---

### 🔹 Applications in Machine Learning  

1. **Probabilistic Modeling** – Bayesian inference, Naive Bayes, HMMs  
2. **Uncertainty Quantification** – Model confidence & error estimation  
3. **Data Simulation** – Synthetic data generation for ML algorithms  
4. **Stochastic Optimization** – Random sampling in gradient methods  

---
