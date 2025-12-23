# 🚨 Fraud Detection using Machine Learning

This project focuses on detecting fraudulent financial transactions using machine learning techniques. A synthetic dataset is generated to simulate real-world transaction behavior, including both legitimate and fraudulent activities. Multiple supervised and unsupervised models are trained and evaluated to identify fraud patterns effectively.

---

## 📌 Objectives
- Simulate real-world transaction data with class imbalance
- Perform exploratory data analysis and feature visualization
- Train and compare multiple machine learning models
- Evaluate performance using standard classification metrics
- Identify the most effective model for fraud detection

---

## 🗂️ Dataset Description
A synthetic dataset of **100,000 transactions** is generated with the following features:

- **Transaction Amount**
- **Time of Day**
- **Device ID**
- **IP Address Risk Score**
- **Fraud Label (0 = Normal, 1 = Fraud)**

Fraudulent transactions account for approximately **1%** of the dataset, reflecting real-world imbalance.

---

## ⚙️ Models Implemented
- **Logistic Regression** (Supervised)
- **Random Forest Classifier** (Supervised)
- **Isolation Forest** (Unsupervised Anomaly Detection)

---

## 🧪 Workflow
1. Synthetic data generation
2. Exploratory Data Analysis (EDA)
3. Feature scaling using StandardScaler
4. Train-test split with stratification
5. Model training
6. Performance evaluation using:
   - Classification Report
   - Confusion Matrix
   - Accuracy, Precision, Recall, F1-score

---

## 📊 Results & Observations
- **Random Forest** demonstrated strong performance on imbalanced data
- **Logistic Regression** provided stable and interpretable results
- **Isolation Forest** successfully detected anomalies without labels
- Feature importance analysis highlighted transaction amount and IP risk as strong indicators of fraud

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:**  
  - NumPy  
  - Pandas  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  

---

## ⭐ Technical Highlights
- Implemented an end-to-end fraud detection pipeline using **Scikit-learn**, covering data generation, preprocessing, model training, and evaluation.
- Designed and evaluated multiple models (**Logistic Regression, Random Forest, Isolation Forest**) to handle **highly imbalanced transaction data**.
- Applied **feature scaling (StandardScaler)** and **stratified train-test splitting** to ensure robust model performance.
- Achieved strong fraud detection capability using ensemble methods, demonstrating improved recall on minority (fraud) class samples.
- Performed extensive **EDA and feature analysis** using Pandas, Matplotlib, and Seaborn to identify key fraud-indicative attributes.

---

## 📜 Conclusion
This project demonstrates a practical and scalable approach to fraud detection using machine learning. It highlights the importance of feature analysis, model selection, and evaluation when working with highly imbalanced datasets commonly found in financial systems.
