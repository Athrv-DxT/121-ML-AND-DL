# 📘 Week 2: Probability & Statistics for Machine Learning (Days 8–14)

This week focused on building strong fundamentals in Probability and Statistics for Machine Learning.  
We covered descriptive statistics, probability theory, distributions, and Python implementations with ML applications.

---

## 📅 Day-wise Topics  

- **Day 8:** Descriptive Statistics & Data Summarization  
- **Day 9:** Probability Theory & Rules  
- **Day 10:** Conditional Probability & Bayes' Theorem  
- **Day 11:** Joint, Marginal & Conditional Distributions  
- **Day 12:** Expectation, Variance & Covariance  
- **Day 13:** Probability Basics – Events, Conditional Probability & Simulations  
- **Day 14:** Random Variables & Distributions (Discrete & Continuous)  

---

## 🧾 Key Concepts & ML Applications  

### 🔹 Day 8: Descriptive Statistics & Data Summarization
- **Measures of Central Tendency:** Mean, Median, Mode  
- **Measures of Dispersion:** Variance, Standard Deviation, Range  
- **Shape of Data:** Skewness, Kurtosis  

**Formulas:**  
- Mean:  μ = (Σ xᵢ) / n  
- Variance:  σ² = (Σ (xᵢ - μ)²) / n  
- Standard Deviation:  σ = √σ²  

**ML Applications:**  
- Feature Scaling, Outlier Detection, Data Preprocessing  

---

### 🔹 Day 9: Probability Theory & Rules
- **Probability Definition:** Likelihood of an event  
- **Rules:** Addition, Multiplication, Complement  

**Formulas:**  
- P(A) = Number of favorable outcomes / Total outcomes  
- P(A ∪ B) = P(A) + P(B) − P(A ∩ B)  
- P(A ∩ B) = P(A) × P(B|A)  

**ML Applications:**  
- Probabilistic Models like Naive Bayes, Risk Modeling, Stochastic ML algorithms  

---

### 🔹 Day 10: Conditional Probability & Bayes' Theorem
- **Conditional Probability:** Probability of A given B  

**Formulas:**  
- P(A|B) = P(A ∩ B) / P(B)  
- Bayes' Theorem:  P(A|B) = [ P(B|A) × P(A) ] / P(B)  

**ML Applications:**  
- Bayesian Networks, Spam Filtering, Medical Diagnosis  

---

### 🔹 Day 11: Joint, Marginal & Conditional Distributions
- **Joint Distribution:** Probability of two events together  
- **Marginal Distribution:** Probability of one variable regardless of the other  
- **Conditional Distribution:** Probability given some conditions  

**Formulas:**  
- Joint: P(X, Y)  
- Marginal: P(X) = Σ P(X,Y)  
- Conditional: P(X|Y) = P(X,Y) / P(Y)  

**ML Applications:**  
- Multivariate Models, HMMs, Probabilistic Graphical Models  

---

### 🔹 Day 12: Expectation, Variance & Covariance
- **Expectation:** Mean of a random variable  
- **Variance:** Spread of a random variable  
- **Covariance:** Relationship between two variables  

**Formulas:**  
- E[X] = Σ xᵢ · P(xᵢ)  
- Var(X) = E[X²] − (E[X])²  
- Cov(X,Y) = E[(X−E[X])(Y−E[Y])]  

**ML Applications:**  
- Feature Correlation, PCA, Portfolio Optimization  

---

### 🔹 Day 13: Probability Basics – Events & Simulations
- **Events:** Outcomes in probability space  
- **Simulations:** Monte Carlo simulations for approximations  

**Formulas:**  
- P(A) = |A| / |Sample Space|  
- Law of Large Numbers: As n → ∞, empirical probability → true probability  

**ML Applications:**  
- Probabilistic Sampling, Reinforcement Learning, Risk Estimation  

---

### 🔹 Day 14: Random Variables & Distributions
- **Random Variables:** Discrete & Continuous RVs  
- **Probability Mass Function (PMF):** For discrete variables  
- **Probability Density Function (PDF):** For continuous variables  

**Formulas:**  
- PMF:  P(X=x) = f(x),   Σ f(x) = 1  
- PDF:  P(a ≤ X ≤ b) = ∫[a to b] f(x) dx  
- Expectation:  
  E[X] = Σ x · P(X=x)   (Discrete)  
  E[X] = ∫ x · f(x) dx   (Continuous)  

**ML Applications:**  
- Generative Models, Gaussian Mixture Models, Probabilistic Inference  

---
