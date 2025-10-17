# 🚗 Case Study: Car Price Prediction using Machine Learning
**Day 47 of 121 Days of Machine Learning & Deep Learning**

---

## 📘 Overview
This case study focuses on predicting the **fuel efficiency (MPG)** of cars using various features such as horsepower, weight, acceleration, and model year.  
The goal is to build regression models that can accurately estimate MPG based on car specifications.

---

## 📊 Dataset Information
We used the **`mpg` dataset** available from Seaborn, which contains:
- `mpg` — Miles per gallon (Target)
- `cylinders` — Number of cylinders
- `displacement` — Engine displacement
- `horsepower` — Engine power
- `weight` — Vehicle weight
- `acceleration` — Acceleration time
- `model_year`, `origin`, `name` — Categorical and numerical identifiers

---

## ⚙️ Workflow

### 1️⃣ Data Preprocessing
- Handled missing values using `dropna()`.
- Encoded categorical features (`origin`, `name`) using `LabelEncoder`.
- Scaled numerical features using `StandardScaler`.

---

### 2️⃣ Model Training

#### 🔹 **Linear Regression**
A simple regression model that fits a line minimizing the **Mean Squared Error (MSE)**.


#### 🔹 **Random Forest Regressor**
An ensemble model that combines multiple decision trees to improve accuracy and reduce overfitting.


---

### 3️⃣ Evaluation Metrics
We used:
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**
- **R² Score**


---

## 📈 Visualization
- **Actual vs Predicted MPG** Scatter Plot
- **Feature Importance** Bar Plot showing key attributes:
  - Horsepower
  - Weight
  - Displacement

---

## 💡 Key Insights
- **Random Forest** performed better due to its ensemble learning nature.
- Weight and horsepower were **negatively correlated** with MPG.
- The model provides a robust baseline for predicting car efficiency in the automotive industry.

