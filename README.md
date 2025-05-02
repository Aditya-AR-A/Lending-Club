
# 📊 Lending Club Loan Default Prediction

## Course-End Project 3 – Deep Learning Model

### 🧾 Project Description

This project aims to develop a deep learning model to predict whether a borrower will default on a loan using Lending Club’s historical data (2007–2015). The dataset is imbalanced and contains various financial features, making it a challenging classification problem. Accurate loan default prediction is crucial for minimizing financial risk in the lending industry.

---

## 📂 Dataset Overview

Each record in the dataset represents a loan application with the following key features:

| Column Name         | Description                                               |
| ------------------- | --------------------------------------------------------- |
| `credit.policy`     | 1 if customer meets underwriting criteria; else 0         |
| `purpose`           | Purpose of the loan (e.g., credit\_card, small\_business) |
| `int.rate`          | Interest rate (e.g., 11% = 0.11)                          |
| `installment`       | Monthly loan installment                                  |
| `log.annual.inc`    | Natural log of annual income                              |
| `dti`               | Debt-to-income ratio                                      |
| `fico`              | FICO credit score                                         |
| `days.with.cr.line` | Days the borrower has had a credit line                   |
| `revol.bal`         | Revolving balance                                         |
| `revol.util`        | Revolving line utilization                                |
| `inq.last.6mths`    | Credit inquiries in last 6 months                         |
| `delinq.2yrs`       | Delinquencies in past 2 years                             |
| `pub.rec`           | Public derogatory records                                 |

---

## 🧠 Project Workflow

### 1. 🔄 Feature Transformation

* Convert categorical features (e.g., `purpose`) into numerical format using one-hot encoding or label encoding.

### 2. 📊 Exploratory Data Analysis (EDA)

* Analyze data distributions, class imbalance, and patterns across features.
* Visualize relationships (e.g., FICO score vs. default rate).
* Identify potential outliers and missing values.

### 3. 🛠️ Feature Engineering

* Check for multicollinearity using correlation matrices.
* Drop features with high correlation to reduce redundancy.
* Standardize numerical values for better model convergence.

### 4. 🤖 Modeling

* Use Keras with TensorFlow backend to build a neural network classifier.
* Handle class imbalance (e.g., via class weights or oversampling techniques).
* Evaluate the model using accuracy, precision, recall, and AUC score.

---

## 📦 Requirements

Install the required libraries using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras
```

---

## 🏁 Project Goals

* Build an end-to-end deep learning pipeline.
* Preprocess and engineer relevant features.
* Evaluate performance on a highly imbalanced dataset.
* Provide insights into key drivers of loan defaults.

---

## 📈 Expected Outcomes

* A trained deep learning model capable of classifying loan defaults.
* Feature insights via EDA and correlation analysis.
* A scalable preprocessing pipeline for similar financial datasets.

---

## 📬 Contact

For queries or feedback, please contact \[Your Name or Email].
