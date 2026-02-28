# Bank Customer Churn Prediction

Machine learning project focused on predicting customer churn in the banking sector using classification models under class imbalance conditions.

---

## 📌 Project Overview

Customer retention is significantly more cost-effective than customer acquisition. This project aims to predict whether a bank customer is likely to leave the institution based on historical behavioral and financial data.

The primary objective was to build a classification model that maximizes the F1-score (minimum required: 0.59) while also evaluating model performance using the ROC-AUC metric.

---

## 🎯 Objective

- Predict customer churn (Exited = 1)
- Handle class imbalance effectively
- Optimize F1-score
- Compare performance using ROC-AUC

---

## 📊 Dataset Description

The dataset includes customer-level banking data such as:

- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary

Target variable:

- Exited (1 = customer left, 0 = retained)

---

## 🛠 Methodology

1. Data preprocessing and cleaning
2. Exploratory Data Analysis (EDA)
3. Class imbalance analysis
4. Baseline model training (without imbalance correction)
5. Imbalance handling techniques:
   - Class weighting
   - Oversampling (SMOTE)
   - Undersampling
6. Model comparison and hyperparameter tuning
7. Final evaluation on test set

---

## 📈 Model Performance

- Final F1-score: 0.63
- ROC-AUC: 0.86

The final model met the minimum F1-score requirement and demonstrated strong discriminative performance.

---

## 🧠 Key Insights

- Class imbalance significantly affected baseline performance.
- Applying imbalance correction techniques improved recall and overall F1-score.
- Feature importance analysis revealed that Age, Balance, and Activity Status were key churn drivers.

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 📁 Project Structure
