# Credit-Card-Fraud-Detection---ML
---

# Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

The goal of this project is to develop a **machine learning model** that can accurately detect fraudulent credit card transactions using historical data. By analyzing transaction patterns, the model distinguishes between **normal** and **fraudulent activity**, helping financial institutions flag suspicious behavior early and reduce potential risks.

### ⚡ Key Challenges

* **Imbalanced Dataset** – Fraud cases are a very small fraction of total transactions (\~0.02%).
* **High Precision Requirement** – To minimize false positives (valid transactions wrongly flagged as fraud).
* **High Recall Requirement** – To detect as many fraud cases as possible and avoid missing fraudulent activity.

---

## 🛠️ Tech Stack

* **Programming Language**: Python
* **Libraries**: NumPy, Pandas, Matplotlib, Seaborn, scikit-learn
* **Model Used**: Random Forest Classifier

---

## 📂 Dataset

* **Source**: [Credit Card Fraud Detection Dataset (Kaggle)](https://www.kaggle.com/mlg-ulb/creditcardfraud)
* **Details**:

  * `Time`: Seconds elapsed since the first transaction in the dataset.
  * `V1–V28`: Anonymized features created via PCA to protect confidentiality.
  * `Amount`: Transaction amount.
  * `Class`: Target variable (`0 = Normal`, `1 = Fraud`).
* **Size**: 284,807 transactions, 31 features.

---

## 🔎 Exploratory Data Analysis (EDA)

1. **Class Distribution** – Fraudulent transactions are only \~0.02% of total transactions.
2. **Transaction Amounts** – Fraudulent transactions often have higher average amounts.
3. **Correlation Matrix** – Most features are weakly correlated, but some like `V2` and `V5` show significant relationships with transaction amounts.


