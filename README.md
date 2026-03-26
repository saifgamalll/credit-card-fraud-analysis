# Credit Card Fraud Detection & Analysis

## 🎯 Project Overview
This project focuses on identifying fraudulent credit card transactions. The primary challenge was handling a highly imbalanced dataset where fraud accounted for less than 0.2% of total transactions.

## 🛠️ Key Analytical Steps
* **Exploratory Data Analysis (EDA):** Identified key correlations between transaction amounts, time of day, and geographical anomalies.
* **Data Preprocessing:** Handled missing values and normalized features using StandardScaler.
* **Handling Imbalance:** Applied SMOTE (Synthetic Minority Over-sampling Technique) to ensure the model could accurately learn fraud patterns.
* **Evaluation:** Focused on **Recall** and **F1-Score** to minimize "False Negatives" (missed fraud).

## 📈 Results
Achieved a **95% Recall rate**, ensuring that the vast majority of fraudulent activities were flagged for review.
