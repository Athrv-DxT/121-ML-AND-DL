# Day 81 – Perceptron (Neural Networks Intro)

## 📌 Concepts Covered
- What is a Perceptron?
- Perceptron learning rule
- Binary classification using Perceptron
- Decision boundary visualization

---

## 🧠 Perceptron Formula

A perceptron computes a weighted sum and applies a step activation:

**y = f(w · x + b)**  
where:  
- **w** = weights  
- **x** = input  
- **b** = bias  
- **f(z)** = 1 if **z ≥ 0**, else 0  

---

## 🧠 Weight Update Rule

**w = w + η (y-true – y-pred) x**  
**b = b + η (y-true – y-pred)**  

where:  
- **η** = learning rate  
- **yᵗʳᵘᵉ** = actual label  
- **yᵖʳᵉᵈ** = predicted label  

---

## 🔧 Implementation Steps
- Use Iris dataset (binary)
- Scale features using StandardScaler
- Train Perceptron model
- Plot decision boundary


