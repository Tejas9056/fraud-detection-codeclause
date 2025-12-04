# 🚀 Fraud Detection in Credit Card Transactions  
### CodeClause Data Science Internship – Entry Level Project

This project focuses on detecting fraudulent credit card transactions using a simple yet effective machine learning model.  
The dataset is highly imbalanced, reflecting real-world fraud scenarios where fraudulent cases are extremely rare.  
This project demonstrates preprocessing, model training, evaluation, and handling imbalance effectively.

## 🔍 **Objective**
To build a classification model that can identify fraudulent transactions from a credit card dataset while dealing with heavy class imbalance.

## 📂 **Dataset Overview**
- The dataset contains credit card transactions labeled as:
  - **Class 0 → Normal transactions**
  - **Class 1 → Fraud transactions**
- Total samples:
  - Class 0: **13,897**
  - Class 1: **56**
- This imbalance makes fraud detection challenging, making the project a practical learning experience.

## 🧠 **Approach & Workflow**
### **1️⃣ Data Loading & Exploration**
- Loaded the dataset using Pandas  
- Checked data distribution, imbalance, and basic statistics  

### **2️⃣ Train–Test Split**
- Used `train_test_split` with **stratification** to maintain the class ratio

### **3️⃣ Feature Scaling**
- Applied **StandardScaler** for normalization

### **4️⃣ Model Training**
- Model used: **Logistic Regression**  
- Reason:
  - Simple  
  - Interpretable  
  - Works well for binary classification  
- Used `class_weight='balanced'` to deal with data imbalance

### **5️⃣ Model Evaluation**
Used:
- **Confusion Matrix**
- **Classification Report**
- **Precision, Recall, F1-score**

## 📊 **Results**
Metric Score 
**Accuracy** 99% 
Fraud Recall (Class 1) = 0.91
F1 Score (Fraud Class) = 0.50 

### ✔ Key Insight:
- Model successfully identified **91% of fraudulent transactions**  
- Only **1 fraud case** was missed  
- This is excellent for an entry-level fraud detection system  

---

## 🛠 **Technologies Used**
- **Python**  
- **Pandas**  
- **NumPy**  
- **Scikit-learn**  
- **Google Colab / Jupyter Notebook**

---

## 🎯 **Learning Outcomes**
- Understanding **imbalanced datasets**
- Implementing **classification models**
- Applying **data preprocessing** and **scaling**
- Evaluating models beyond accuracy  
- Importance of metrics like **recall for fraud detection**
