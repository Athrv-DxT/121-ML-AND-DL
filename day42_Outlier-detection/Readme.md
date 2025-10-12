# 📘 Day 42 – Outlier Detection

## 📌 Concepts Covered:
- **Z-Score Method**
- **IQR (Interquartile Range) Method**
- **Advanced:** Isolation Forest & DBSCAN  

---

## 🧾 Z-Score Method
- Detects outliers based on standard deviation from the mean.  
- Points with `|Z| > 3` are typically considered outliers.  

**Formula:**  
**Z = (x - μ) / σ**  

Where:  
- `x` = data point  
- `μ` = mean of the dataset  
- `σ` = standard deviation  

---

## 🧾 IQR Method
- Detects outliers based on the spread between Q1 and Q3.  
- Points outside **[Q1 - 1.5×IQR, Q3 + 1.5×IQR]** are considered outliers.  

**Formula:**  
**IQR = Q3 - Q1**  
**Lower Bound = Q1 - 1.5 × IQR**  
**Upper Bound = Q3 + 1.5 × IQR**  

---

## ⚙️ Advanced Outlier Detection

### 🔹 Isolation Forest
- An **ensemble-based anomaly detection algorithm**.  
- Randomly partitions data to isolate anomalies — anomalies require fewer splits.  
- Ideal for **high-dimensional datasets**.

**Concept:**  
Anomalies are points that are easier to isolate.

---

### 🔹 DBSCAN (Density-Based Spatial Clustering)
- Groups points into clusters based on **density**.  
- Points that don’t belong to any dense region are labeled as **outliers (-1)**.  

**Parameters:**  
- `eps`: Neighborhood radius  
- `min_samples`: Minimum points to form a cluster  

