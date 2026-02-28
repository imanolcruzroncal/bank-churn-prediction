🏦 Bank Customer Churn Prediction

Machine Learning project focused on predicting customer churn in the banking sector using classification models under class imbalance conditions.

📌 Project Overview

Customer retention is significantly more cost-effective than customer acquisition. This project aims to predict whether a bank customer is likely to leave the institution based on historical behavioral and financial data.

The primary objective was to build a classification model that maximizes the F1-score (minimum required: 0.59) while also evaluating model performance using the ROC-AUC metric.

This project simulates a real-world churn prediction scenario under imbalanced class distribution (~80% non-churn vs ~20% churn).

📊 Dataset

10,000 customer records

Numerical and categorical features

Target variable: Exited (1 = churn, 0 = retained)

Key Features:

CreditScore

Geography

Gender

Age

Tenure

Balance

NumOfProducts

IsActiveMember

🧠 Methodology

1️⃣ Exploratory Data Analysis (EDA)
2️⃣ Missing value treatment (median imputation for Tenure)
3️⃣ Categorical encoding (Ordinal Encoding)
4️⃣ Train / Validation / Test split
5️⃣ Model comparison:

🌲 RandomForestClassifier

📈 LogisticRegression
6️⃣ Class imbalance handling:

⚖️ Class weighting

🔁 Oversampling
7️⃣ Hyperparameter tuning
8️⃣ Final evaluation on test set

🤖 Final Model

RandomForestClassifier

max_depth = 6

n_estimators = 40

class_weight = 'balanced'

📈 Model Performance (Test Set)

🎯 F1-score: 0.59

📊 ROC-AUC: 0.76

The model demonstrates solid discriminative power and balanced performance between precision and recall under imbalanced data conditions.

💼 Business Impact

This model can function as an early warning system to:

🚨 Identify high-risk customers

🎯 Prioritize retention campaigns

💰 Reduce unnecessary intervention costs

📈 Improve customer lifetime value

🛠 Technologies Used

🐍 Python

🐼 Pandas

🔢 NumPy

🤖 Scikit-learn

📓 Jupyter Notebook

🚀 How to Run

Clone the repository:

git clone <your-repository-url>
cd bank-churn-prediction

Install dependencies:

pip install -r requirements.txt

Launch Jupyter Notebook:

jupyter notebook
👨‍💻 Author

Abraham Imanol Cruz Roncal
Industrial Engineer
Master’s in Engineering Management
Data Science & Machine Learning Enthusiast
