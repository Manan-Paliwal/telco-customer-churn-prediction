# Telco Customer Churn Prediction

An end-to-end machine learning project for predicting customer churn using the IBM Telco Customer Churn dataset.

The project covers data preprocessing, exploratory analysis, feature engineering, model training, evaluation, and business interpretation using Python and Scikit-learn.

---

## Problem Statement

Customer churn is a major challenge for telecommunications companies. Identifying customers who are likely to discontinue their service can help businesses take proactive retention measures.

The goal of this project is to build a machine learning model that predicts whether a customer is likely to churn based on demographic information, account details, and service usage patterns.

---

## Business Problem

Customer churn is a major challenge for telecommunication companies.

The objective is to predict customers who are likely to leave the company so that proactive retention strategies can be implemented.

---

## Machine Learning Workflow

1. Business Understanding
2. Data Collection
3. Data Cleaning
4. Exploratory Data Analysis
5. Feature Engineering
6. Data Preprocessing
7. Train-Test Split
8. Feature Scaling
9. Model Training
10. Model Evaluation
11. Business Interpretation

---

## Dataset

**Dataset:** IBM Telco Customer Churn Dataset

**Number of Records:** 7,043

**Target Variable:** Churn

---

## Data Preparation

The following preprocessing steps were performed:

* Replaced blank values with missing values
* Converted `TotalCharges` to numeric
* Filled missing values
* Removed `customerID`
* Applied Label Encoding
* Performed Feature Scaling using StandardScaler

---

## Machine Learning Model

* Logistic Regression

---

## Model Evaluation

The model was evaluated using:

* Accuracy
* Confusion Matrix
* Classification Report

---

## Business Insights

The trained model can help businesses:

* Identify customers at risk of churn
* Improve customer retention
* Reduce revenue loss
* Support data-driven business decisions

---

## Skills Learned

* Business Understanding
* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Data Preprocessing
* Train-Test Split
* Feature Scaling
* Logistic Regression
* Model Evaluation
* Business Interpretation

---

## Project Structure

```text
telco-customer-churn-prediction/

├── data/
├── images/
├── notebooks/
├── outputs/
├── reports/
├── README.md
├── LICENSE
├── requirements.txt
└── .gitignore
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Future Improvements

* Compare multiple machine learning models.
* Perform hyperparameter tuning.
* Deploy the trained model as a web application.
* Monitor model performance using new data.

---

## Author

**Manan Paliwal**

AI & Machine Learning Student

Birla Institute of Technology, Mesra
