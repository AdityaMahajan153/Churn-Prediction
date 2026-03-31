# 📊 Customer Churn Prediction using Machine Learning

## 📌 Overview

This project focuses on predicting customer churn using machine learning techniques. Customer churn refers to the phenomenon where customers stop using a company’s service. The goal is to identify customers likely to churn so that businesses can take preventive actions.

---

## 🎯 Objectives

* Analyze customer data to identify patterns leading to churn
* Perform data preprocessing and feature engineering
* Build classification models to predict churn
* Evaluate model performance using appropriate metrics

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Models:** Logistic Regression, Random Forest Classifier

---

## 📂 Project Structure

```
CustomerChurnPrediction/
│── train.csv                  # Training dataset
│── test.csv                   # Testing dataset (optional)
│── notebook.ipynb             # Model development
│── ChurnRiskScorePrediction.pkl  # Saved model
│── README.md
```

---

## 🔄 Workflow

### 1. Data Preprocessing

* Handled missing values
* Removed irrelevant columns (e.g., customer ID)
* Converted categorical variables into numerical format

### 2. Exploratory Data Analysis (EDA)

* Visualized churn distribution
* Analyzed relationships between features and churn
* Used correlation heatmap to understand feature dependencies

### 3. Feature Engineering

* Selected relevant features influencing churn
* Transformed categorical data using encoding techniques

### 4. Model Training

* Logistic Regression (baseline model)
* Random Forest Classifier (advanced model)

### 5. Model Evaluation

* Accuracy score
* Confusion Matrix
* Precision, Recall, and F1-score

---

## 📊 Features Used

* Customer demographics
* Account information
* Service usage details
* Billing and payment information

---

## 📈 Results

* Random Forest performed better than Logistic Regression
* Model successfully identified patterns in customer behavior
* Key features influencing churn were identified using feature importance

---

## ▶️ How to Run the Project

### 1. Install dependencies

```
pip install numpy pandas matplotlib seaborn scikit-learn
```

### 2. Run the notebook

* Open the notebook file
* Run all cells step-by-step
