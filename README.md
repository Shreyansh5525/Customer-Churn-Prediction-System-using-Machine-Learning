# 📊 Customer Churn Prediction System using Machine Learning

## 📌 Project Overview
Customer Churn Prediction is a Machine Learning classification project developed to predict whether a telecom customer will leave the company (churn) or continue using the service.

This project is based on the real-world telecom dataset:

✅ `Telco_customer_churn.xlsx`

The system helps businesses reduce customer loss and improve retention strategies.

---

## 🎯 Objective
The main objectives of this project are:

- To analyze customer behavior using telecom data  
- To preprocess and clean the dataset  
- To handle missing values effectively  
- To encode categorical features into numerical form  
- To build a classification model for churn prediction  
- To evaluate the model using accuracy and classification metrics  

---

## 📂 Dataset Information
Dataset Used: **Telco Customer Churn Dataset**

- File Name: `Telco_customer_churn.xlsx`
- Total Features: 33 Columns  
- Target Column: `Churn Label` (Yes/No)  

Target Encoding:

- Yes → 1 (Customer Churned)  
- No → 0 (Customer Stayed)  

---

## 🛠 Technologies & Tools Used
This project is implemented using:

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-Learn  
- Pickle (for saving the model)

---

## ⚙️ Project Workflow

### ✅ Step 1: Load Dataset
The dataset is loaded from an Excel file using Pandas.

### ✅ Step 2: Data Preprocessing
- Removed irrelevant columns like CustomerID and location details  
- Filled missing values using median (numerical) and mode (categorical)  

### ✅ Step 3: Feature Encoding
- Converted categorical features using One-Hot Encoding  
- Encoded target column `Churn Label` into numeric values  

### ✅ Step 4: Train-Test Split
The dataset is divided into:

- 80% Training Set  
- 20% Testing Set  

### ✅ Step 5: Model Training
A **Random Forest Classifier** is trained for predicting churn customers.

### ✅ Step 6: Model Evaluation
Performance is evaluated using:

- Accuracy Score  
- Classification Report (Precision, Recall, F1-score)  
- Confusion Matrix  

### ✅ Step 7: Model Saving
The trained model is saved as:

```bash
telco_churn_model.pkl

```

👨‍💻 Author
Shreyansh Kumar.
