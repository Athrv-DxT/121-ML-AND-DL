# 📘 Day 18: Hypothesis Testing

## 📌 Agenda
- Understanding Hypothesis Testing
- p-values
- z-test
- t-test (One-sample and Two-sample)
- Visualization of Critical Regions

---

## 🧾 Key Concepts

### 🔹 Hypothesis Testing Basics
- Null Hypothesis (H0): Assumes no effect or no difference  
- Alternative Hypothesis (H1): Assumes a real effect or difference  

---

### 🔹 p-value  
The p-value is the probability of obtaining a result at least as extreme as the one observed, assuming the null hypothesis is true.  

If p-value < α (significance level), we reject H0.  
If p-value ≥ α, we fail to reject H0.  

---

### 🔹 Z-test  
Used when population variance is known or sample size is large (n > 30).  

Formula:  
Z = (X̄ - μ) / (σ / √n)  

Where:  
- X̄ = Sample mean  
- μ = Population mean  
- σ = Population standard deviation  
- n = Sample size  

---

### 🔹 One-sample t-test  
Used when testing if sample mean differs from a known value.  

Formula:  
t = (X̄ - μ) / (s / √n)  

Where:  
- s = Sample standard deviation  

---

### 🔹 Two-sample t-test  
Tests if two independent sample means are different.  

Formula:  
t = (X̄₁ - X̄₂) / √(s₁²/n₁ + s₂²/n₂)  

---

### 🔹 Decision Rule  
- If p-value < α → Reject H0  
- If p-value ≥ α → Fail to reject H0  

---

## 🔹 Python Functions Used

stats.ttest_ind(data1, data2)   # Two-sample t-test
stats.ttest_1samp(data, popmean) # One-sample t-test
stats.norm.cdf(x)                # Z-test p-value calculation
