# 📘 Day 15: Expectation & Variance

## 📌 Agenda  
- Expectation (Mean) Basics  
- Variance & Standard Deviation  
- Variance via Expectation Formula  
- Law of Large Numbers Demonstration  
- Expectation of Discrete Random Variables  
- Expectation of Continuous Random Variables  

---

## 🧾 Key Concepts  

### 🔹 Expectation (Mean)  
The expectation or mean of a random variable X is:  

E[X] = (1/n) Σ xᵢ  

---

### 🔹 Variance  
Variance measures the spread of the data around the mean.  

- Population Variance:  
  Var(X) = (1/n) Σ (xᵢ − μ)²  

- Sample Variance:  
  s² = (1/(n−1)) Σ (xᵢ − x̄)²  

- Standard Deviation:  
  σ = √Var(X)  

---

### 🔹 Variance Using Expectation Formula  

Var(X) = E[X²] − (E[X])²  

---

### 🔹 Law of Large Numbers  

As the sample size n increases, the sample mean approaches the true mean:  

lim (n → ∞) (1/n) Σ xᵢ = E[X]  

---

### 🔹 Discrete Random Variable Expectation  

For discrete values xᵢ with probabilities pᵢ:  

E[X] = Σ xᵢ pᵢ  

---

### 🔹 Continuous Random Variable Expectation  

For a continuous PDF f(x):  

E[X] = ∫ x·f(x) dx over (−∞, ∞)  

---

## 🔹 Python Functions Used  

np.mean(data)               # Expectation
np.var(data)                # Variance (Population)
np.var(data, ddof=1)        # Variance (Sample) ddof= delta degrees of freedom
np.std(data)                # Standard Deviation
np.trapezoid(f, x)          # Numerical Integration for Continuous Expectation

