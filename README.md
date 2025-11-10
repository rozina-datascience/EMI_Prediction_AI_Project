# EMI_Prediction_AI_Project
Machine Learning project that predicts EMI eligibility and maximum EMI amount using classification and regression models. Includes data preprocessing, model evaluation, and MLflow tracking.
# 💳 EMI Prediction AI Project

## 📌 Project Overview
This project aims to predict whether a customer is eligible for an EMI (Equated Monthly Installment) and to estimate the **maximum EMI amount** they can afford. It combines **classification** and **regression** models to provide a dual-stage financial prediction system.

---

## 🎯 **Objective**
To build a machine learning system that:
1. Predicts if a customer is **eligible for EMI** based on financial and demographic features.  
2. Estimates the **maximum EMI amount** for eligible customers.

---

## 📂 **Dataset Details**
- The dataset contains customer details such as:
  - Age, income, loan amount, and credit score  
  - Employment status, dependents, and existing EMI data  
- The data was cleaned, encoded, and scaled before modeling.  
- Split into:
  - **Classification dataset:** For EMI eligibility prediction  
  - **Regression dataset:** For maximum EMI prediction

---

## ⚙️ **Methodology (Steps 1–7)**

### **Step 1: Project Overview**
Defined business goal and ML objectives.

### **Step 2: Data Understanding & Preparation**
- Loaded and explored the dataset.  
- Handled missing values and duplicates.  
- Encoded categorical columns using LabelEncoder and OneHotEncoder.

### **Step 3: Data Splitting**
- Split into training and testing datasets for both classification and regression tasks.

### **Step 4: Model Training**
- Classification models tested:
  - Logistic Regression  
  - Random Forest  
  - XGBoost  
- Regression models tested:
  - Linear Regression  
  - Random Forest Regressor  
  - XGBoost Regressor

### **Step 5: Model Evaluation**
- **Classification metrics:** Accuracy, precision, recall, and F1-score  
- **Regression metrics:** R² score, MAE, RMSE  

### **Step 6: Model Deployment Demo**
A function `predict_emi_eligibility()` was created to:
- Accept new applicant data  
- Predict EMI eligibility  
- Predict the possible maximum EMI amount  

### **Step 7: Reporting and Documentation**
- Created a project summary and visualization plots.  
- Logged key performance metrics in MLflow (optional).  
- Added README and requirements files for deployment readiness.

---

## 🧰 **Tools & Libraries Used**
- **Python 3**
- **pandas**, **numpy**, **scikit-learn**
- **matplotlib**, **seaborn**
- **xgboost**
- **MLflow** (for experiment tracking)
- **Google Colab** (for development)

---

## 📊 **Results & Insights**
- **Best Classification Model:** Random Forest Classifier  
  - Accuracy: ~94%  
- **Best Regression Model:** Random Forest Regressor  
  - R² Score: ~0.87  
- **Sample Prediction Output:**
