# 🧠 Day 46 – Machine Learning Case Study: Customer Churn Prediction

## 📌 Objective
The goal of this case study is to predict whether a customer will **churn (leave the service)** or **stay**, based on their demographic and service usage data.  
This project applies **Supervised Learning (Classification)** techniques using the **Telco Customer Churn** dataset.

---

## 🧾 Dataset Description
**Dataset Name:** Telco Customer Churn  
**Source:** Kaggle  
**Rows:** 7043  
**Columns:** 21  


---

## ⚙️ Workflow
1. **Data Import & Exploration**  
   - Loaded and explored dataset using `pandas` and `matplotlib`.  
   - Handled missing values and type conversions.

2. **Preprocessing**  
   - Label encoding for categorical variables.  
   - Split dataset into training and testing sets (80/20).

3. **Model Building**  
   - Used **Random Forest Classifier** for classification.  
   - Tuned hyperparameters and evaluated results.

4. **Evaluation Metrics**
   - Accuracy Score  
   - Classification Report  
   - Confusion Matrix  
   - Feature Importance Visualization


---

## 🔍 Key Insights
- Customers with **Month-to-Month contracts** are more likely to churn.  
- **Longer tenure** indicates higher retention.  
- High **MonthlyCharges** and lack of **TechSupport** also correlate with churn.

---

## 🧩 Visualizations
1. Confusion Matrix Heatmap  
2. Feature Importance Plot  


---

## 🏁 Conclusion
This case study successfully demonstrates an end-to-end machine learning workflow for **Customer Churn Prediction**, achieving around **82% accuracy**.  
It showcases data preprocessing, model training, and business insight extraction — reflecting real-world ML application scenarios.

---

