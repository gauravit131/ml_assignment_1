# ml_assignment_1

# Machine Learning Assignment 1

This repository contains solutions for Machine Learning Assignment 1.
Each question is implemented in a separate Jupyter Notebook for clarity and better organization.

## 📂 Repository Structure
ml_assignment_1/
│
├── Q1_RandomForest_BreastCancer.ipynb
├── Q2_LogisticRegression_Diabetes.ipynb
├── Q3_XGBoost_Titanic.ipynb
├── Q4_DecisionTree_Diabetes.ipynb
│
├── diabetes.csv
├── titanic.csv
└── README.md

Question 1 — Random Forest Classifier

**Dataset:** Breast Cancer Dataset (sklearn)

Task:

* Build Random Forest model to classify tumors as malignant or benign.

Evaluation Metrics:

* Accuracy
* Confusion Matrix
* Precision, Recall, F1-score
* ROC-AUC Score

Question 2 — Logistic Regression (Diabetes Prediction)

**Dataset:** Pima Indians Diabetes Dataset

Steps:

* Load dataset into pandas DataFrame
* Assign column names
* Check missing/zero values
* Train-test split (80/20)
* Feature scaling
* Train Logistic Regression
* Evaluate using standard metrics
* Interpret model coefficients

Question 3 — XGBoost Classifier (Titanic Survival)

**Dataset:** Titanic Dataset

Steps:

* Data loading and preprocessing
* Train-test split
* Feature scaling
* Train XGBoost model
* Model evaluation
* Feature importance interpretation

Question 4 — Decision Tree Classifier (Diabetes)

**Dataset:** Pima Indians Diabetes Dataset

Tasks:

* Handle missing/unrealistic values
* Train Decision Tree model
* Evaluate performance
* Train restricted depth model (max_depth=3)
* Compare results
* Display feature importance

---

## ⚙️ Libraries Used

* numpy
* pandas
* matplotlib
* scikit-learn
* xgboost
