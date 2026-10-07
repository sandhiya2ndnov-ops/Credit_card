# 💳 Credit Card Default Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting whether a credit card customer will **default on their payment in the next month** using Machine Learning.

The project analyzes customer demographic information, credit limits, repayment history, bill amounts and payment amounts to build classification models.

The complete Machine Learning workflow includes:

* Data loading
* Data exploration
* Data preprocessing
* Feature analysis
* Model training
* Model prediction
* Model evaluation
* Comparison of multiple classification algorithms

---

## 🎯 Objective

The main objective of this project is to develop a Machine Learning classification model that can predict whether a customer will default on their credit card payment in the next month.

The target variable is:

```text
default payment next month
```

Where:

```text
0 → No default
1 → Default
```

---

## 📊 Dataset

**Dataset:** `creditcard.csv`

The dataset contains:

```text
30,000 rows
25 columns
```

Important variables include:

| Feature                      | Description              |
| ---------------------------- | ------------------------ |
| `ID`                         | Customer ID              |
| `LIMIT_BAL`                  | Amount of given credit   |
| `SEX`                        | Gender                   |
| `EDUCATION`                  | Education level          |
| `MARRIAGE`                   | Marital status           |
| `AGE`                        | Customer age             |
| `PAY_0`                      | Repayment status         |
| `PAY_2`                      | Repayment status         |
| `PAY_3`                      | Repayment status         |
| `PAY_4`                      | Repayment status         |
| `BILL_AMT1` - `BILL_AMT6`    | Bill statement amounts   |
| `PAY_AMT1` - `PAY_AMT6`      | Previous payment amounts |
| `default payment next month` | Target variable          |

---

## 🔍 Exploratory Data Analysis

The dataset was explored using Pandas, Matplotlib and Seaborn.

The analysis includes:

* Checking the dataset shape
* Viewing sample records
* Checking data types
* Descriptive statistical analysis
* Understanding customer information
* Examining credit limits
* Analyzing repayment status
* Studying bill amounts
* Studying payment amounts
* Analyzing the target variable

---

## 🧹 Data Preprocessing

The project prepares the dataset for Machine Learning by:

1. Loading the dataset using Pandas.
2. Creating a DataFrame.
3. Exploring the dataset.
4. Checking the dataset structure.
5. Preparing input features and target variable.
6. Splitting the dataset into training and testing data.
7. Applying the required preprocessing before model training.

---

## 🎯 Target Variable

The target variable is:

```text
default payment next month
```

This is a binary classification problem.

```text
0 = Customer does not default
1 = Customer defaults
```

The goal is to correctly classify customers into these two categories.

---

## 🤖 Machine Learning Models

The project implements and compares the following Machine Learning algorithms:

### 1. Logistic Regression

Logistic Regression is used as a baseline classification algorithm.

### 2. Decision Tree

A Decision Tree is used to classify customers based on different customer and payment-related features.

### 3. Random Forest

Random Forest combines multiple decision trees to improve classification performance.

The notebook uses:

```text
n_estimators = 100
```

### 4. AdaBoost

AdaBoost combines multiple weak learners to create a stronger classification model.

The notebook uses:

```text
n_estimators = 100
```

### 5. Gradient Boosting

Gradient Boosting is also used for predicting credit card payment default.

The notebook uses:

```text
n_estimators = 100
```

---

## 📈 Model Evaluation

The project evaluates the classification models using:

* Accuracy
* Precision
* Recall
* F1 Score
* Classification Report

The notebook uses Scikit-learn evaluation functions to calculate these metrics.

A model-comparison process is also implemented to compare the performance of all the models.

---

## 🧰 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📁 Project Structure

```text
Credit-Card-Default-Prediction/
│
├── credit card project.ipynb
├── creditcard.csv
├── README.md
└── Credit_Card_Project_Presentation.pptx
```

---

## ▶️ How to Run
 1. Install the required libraries
pip install numpy pandas matplotlib seaborn scikit-learn jupyter`

2. Start Jupyter Notebook

jupyter notebook
 3. Open the project notebook
credit card project.ipynb

 4. Keep `creditcard.csv` in the same folder.

 5. Run all notebook cells from beginning to end.

## 🔄 Machine Learning Workflow
text
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Feature & Target Selection
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Model Comparison

## 📌 Conclusion

This project demonstrates how Machine Learning can be applied to credit card customer data to predict the likelihood of payment default.

Multiple classification algorithms are implemented and evaluated using standard classification metrics.

The project provides practical experience in:

* Data analysis
* Data preprocessing
* Binary classification
* Model training
* Model evaluation
* Machine Learning model comparison

---

