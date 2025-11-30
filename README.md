📌 Customer Churn Prediction using Logistic Regression

This project predicts whether a telecom customer will churn (leave the service) or not using a complete machine learning pipeline. The model uses Logistic Regression along with techniques like label encoding, scaling, and SMOTE for handling imbalance.

🚀 Project Workflow

1. Load & Explore Dataset

Dataset: Telco Customer Churn

Handled missing values

Checked class imbalance

2. Preprocessing

Label Encoding for categorical columns

Standard Scaling

SMOTE applied to balance churn (Yes/No)

3. Model Used

📌 Logistic Regression

Chosen because:

Works well for binary classification

Fast, interpretable, baseline model

4. Evaluation Metrics

Accuracy

Precision, Recall, F1-score

Confusion Matrix

📊 Results

Accuracy: 82.9%

Confusion Matrix:
[[804 217]
 [137 912]]

✔ What this means

High recall for churn (87%)

Balanced precision & recall

Strong business impact: identifies customers likely to leave

📂 Technologies Used

Python

Pandas

Scikit-learn

Imbalanced-learn (SMOTE)

Logistic Regression

🧠 Key Learnings

Handling categorical data

Managing class imbalance

Evaluating classification models

Improving recall in churn prediction

📜 Code

Full cleaned and structured code is included in the notebook/script.
