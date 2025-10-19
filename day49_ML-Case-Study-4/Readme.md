# Day 49 Case Study: Predicting Student Performance

## Project Overview
This project aims to **predict whether a student will pass or fail** based on various factors such as study habits, past failures, absences, and personal information. It is designed as a **step-by-step machine learning case study**, covering data exploration, preprocessing, visualization, model building, and evaluation.

The dataset used is the **Student Performance Dataset** from the UCI Machine Learning Repository.

---

## Dataset
- **Source:** [UCI ML Repository - Student Performance Dataset]
- **File:** `student-mat.csv` (Math grades)
- **Features Include:**
  - `school` – student’s school
  - `sex` – gender
  - `age` – age in years
  - `studytime` – weekly study time
  - `failures` – number of past class failures
  - `absences` – number of school absences
  - `G1, G2, G3` – grades for 1st, 2nd, 3rd periods
  - `pass_fail` – target column (1 = Pass, 0 = Fail)

---

## Steps in the Case Study

1. **Import Libraries**
   - pandas, numpy, matplotlib, seaborn
   - sklearn for machine learning and evaluation

2. **Load and Explore Dataset**
   - Check first few rows, missing values, and target distribution
   - Visualize pass vs fail counts

3. **Preprocess Data**
   - Encode categorical variables using `LabelEncoder`
   - Separate features (`X`) and target (`y`)

4. **Train-Test Split**
   - Split data into training (80%) and testing (20%) sets

5. **Build and Train Model**
   - Decision Tree Classifier

6. **Make Predictions and Evaluate**
   - Accuracy score
   - Confusion matrix
   - Classification report (precision, recall, F1-score)

7. **Feature Importance**
   - Visualize which features contribute most to predicting student success

---

