
# Bank Customer Churn Prediction

An end-to-end data science project that analyzes bank customer behavior and builds a machine learning model to predict which customers are likely to leave the bank.

Customer churn is a major issue for financial institutions because acquiring a new customer is significantly more expensive than retaining an existing one. By identifying customers who are at risk of leaving, banks can take early action through targeted retention strategies.

This project walks through the full data science workflow — from raw data exploration to model building, explainability, and business recommendations.

---

# Project Overview

The goal of this project is to build a predictive system that can estimate the probability of a customer churning based on their demographics, financial behavior, and product usage.

The notebook covers:

* Data exploration and cleaning
* Exploratory data analysis (EDA)
* Feature engineering
* Data preprocessing
* Machine learning model training
* Model evaluation and comparison
* Model explainability using SHAP
* Customer churn probability prediction
* Customer segmentation
* Business insights and recommendations

The final output is not just a model, but insights that could realistically help a bank improve customer retention.

---

# Dataset

The dataset contains **10,000 bank customers** and includes demographic and financial attributes such as:

* Credit score
* Age
* Country
* Gender
* Account balance
* Number of bank products
* Credit card ownership
* Active membership status
* Estimated salary
* Tenure with the bank

The target variable is:

**Churn (0 = stayed, 1 = left the bank)**

---

# Tech Stack

The project was built using the following tools:

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* SHAP (for model explainability)

---

# Project Workflow

### 1. Data Loading

The dataset is imported and inspected to understand its structure, features, and distributions.

### 2. Data Cleaning

Irrelevant columns are removed and the dataset is checked for missing values, duplicates, and data type issues.

### 3. Exploratory Data Analysis

EDA is used to understand patterns in churn behavior across different features such as geography, age, tenure, and customer engagement.

### 4. Feature Engineering

Categorical variables are encoded and features are prepared for machine learning models.

### 5. Data Preprocessing

The data is split into training and testing sets and scaled where necessary.

### 6. Model Training

Multiple models are trained to predict churn.

### 7. Model Evaluation

Models are evaluated using metrics such as:

* Accuracy
* ROC-AUC
* Recall
* Confusion Matrix

### 8. Model Explainability

SHAP values are used to understand which features influence the model’s predictions.

### 9. Customer Segmentation

Customers are grouped based on churn probability to help identify high-risk segments.

### 10. Business Insights

The analysis highlights behavioral patterns and potential drivers of churn.

### 11. Recommendations

Actionable suggestions are proposed that a bank could use to improve customer retention.

---

# Key Insights

Some notable observations from the analysis:

* Churn rates vary significantly across countries.
* Customer engagement (active membership) strongly affects retention.
* Age and number of bank products also influence churn likelihood.
* Some customers maintain zero balance accounts but still remain active users.

These insights can help financial institutions design targeted retention strategies.

---

# Repository Structure

```
bank-customer-churn-prediction
│
├── bank-customer-churn-prediction.ipynb
├── README.md
└── dataset 
```

---

# How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/bank-customer-churn-prediction.git
```

2. Install the required libraries

```
pip install pandas numpy scikit-learn xgboost matplotlib seaborn shap
```

3. Open the notebook

```
jupyter notebook
```

4. Run the notebook cells sequentially.

---

# Author

**Abdul Moez Abbasi**

