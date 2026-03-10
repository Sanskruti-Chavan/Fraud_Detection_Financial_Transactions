# Fraud Detection in Financial Transactions

## Project Overview

Financial fraud is a major challenge for banks and digital payment systems. This project focuses on detecting suspicious transactions using machine learning techniques. By analyzing transaction patterns, the system identifies anomalies that may indicate fraudulent activity.

The goal is to build a simple fraud detection model using **anomaly detection techniques** and visualize patterns in financial transaction data.

---

## Objectives

* Analyze financial transaction data.
* Identify fraudulent transactions using anomaly detection.
* Handle class imbalance in fraud datasets.
* Visualize transaction patterns and anomalies.
* Build an intern-level machine learning workflow.

---

## Dataset

This project uses the **Credit Card Fraud Detection dataset**, which contains anonymized credit card transactions.

Dataset Source:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The dataset includes:

* Transaction features (V1–V28 anonymized variables)
* Transaction Amount
* Time
* Target variable **Class**

  * 0 → Normal Transaction
  * 1 → Fraudulent Transaction

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## Methodology

### 1. Data Loading

The dataset is loaded using **Pandas** for further analysis.

### 2. Data Exploration

Basic exploratory data analysis (EDA) is performed to understand:

* Dataset size
* Feature distribution
* Fraud vs non-fraud transactions

### 3. Handling Class Imbalance

Fraud datasets are highly imbalanced, so anomaly detection techniques are applied.

### 4. Fraud Detection Model

The **Isolation Forest algorithm** is used to detect anomalous transactions.

Isolation Forest works by:

* Randomly selecting features
* Randomly splitting data points
* Detecting anomalies based on isolation depth

Transactions that are isolated quickly are more likely to be fraudulent.

### 5. Visualization

Data visualizations are created to understand fraud patterns, including:

* Fraud vs Normal transaction distribution
* Transaction amount distribution
* Model prediction results

---

## Results

The anomaly detection model successfully identifies suspicious transactions based on abnormal patterns in the dataset.

This project demonstrates how machine learning can assist financial institutions in detecting potential fraud.

---

## Project Structure

```
fraud-detection-financial-transactions
│
├── Fraud_Detection_Financial_Transactions_Code.pdf
└── README.md
```

---

## Future Improvements

* Implement **Deep Learning models** for fraud detection
* Deploy the model using **Streamlit or Flask**
* Create **real-time fraud monitoring dashboards**
* Improve evaluation using metrics such as Precision, Recall, and NDCG

---

## Author

Name: Sanskruti Chavan
Email: schavan200410@gmail.com
LinkedIn: https://www.linkedin.com/in/sanskruti104-chavan/
Project: Fraud Detection in Financial Transactions
Tools Used: Python, Pandas, NumPy, Matplotlib, Scikit-learn, Jupyter Notebook
