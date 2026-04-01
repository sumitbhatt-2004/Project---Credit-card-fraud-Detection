# 💳 Credit Card Fraud Detection System

### 🔍 Project Overview
This project is a Machine Learning solution designed to detect fraudulent credit card transactions in real-time. In the banking sector, identifying fraudulent activity quickly is crucial to prevent financial loss. The model analyzes transaction patterns to distinguish between legitimate and suspicious activities.

### 🚀 Key Features
* **Anomaly Detection:** High-speed identification of fraudulent patterns.
* **Handling Class Imbalance:** Used techniques like **SMOTE** (Synthetic Minority Over-sampling Technique) or **Under-sampling** to handle the rare nature of fraud cases.
* **XGBoost Classifier:** Optimized for high-performance and fast inference.
* **Evaluation Beyond Accuracy:** Focused on **Precision-Recall** and **AUPRC** (Area Under Precision-Recall Curve) because simple accuracy is misleading for imbalanced data.

### 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, XGBoost, Matplotlib, Seaborn
* **Tools:** Cursor AI / VS Code / Kaggle

### 📂 Dataset Description
The dataset contains transactions made by credit cards. Due to privacy reasons, most features are transformed using **PCA (Principal Component Analysis)**:
* **V1, V2, ... V28:** Principal components obtained with PCA.
* **Time:** Seconds elapsed between each transaction and the first transaction in the dataset.
* **Amount:** Transaction amount.
* **Class:** 1 for Fraud, 0 for Legitimate (Target Variable).

### 📊 Model Performance
* **Algorithm:** XGBoost / Random Forest
* **Key Metric:** Focus on **Recall** (to ensure we catch as many frauds as possible).

---
### 🤝 Connect with Me
* **LinkedIn:** [https://www.linkedin.com/in/sumit-bhatt-785982392]
