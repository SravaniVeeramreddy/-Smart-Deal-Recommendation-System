# Smart Deal Recommendation System

A machine learning-powered solution designed to predict whether a customer will redeem a promotional deal or coupon. This project involves end-to-end data cleaning, transformation, feature engineering, and modeling using multiple classification algorithms to support smart marketing decisions.


## 📌 Introduction

This project targets intelligent deal targeting by analyzing customer behavior based on demographic and transaction features. It leverages machine learning to help businesses decide whom to send offers to, increasing redemption rates and marketing efficiency.


## 🚀 Key Features

- ✅ Load and clean customer data  
- ✅ Visualize and impute missing values  
- ✅ Encode categorical variables using Label Encoding  
- ✅ Detect and remove outliers with IQR  
- ✅ Create age × income and discount × coupon interaction features  
- ✅ Normalize skewed features with PowerTransformer  
- ✅ Handle class imbalance with SMOTE  
- ✅ Train multiple models:
  - Logistic Regression (with GridSearchCV)
  - Random Forest
  - XGBoost
- ✅ Evaluate using:
  - Accuracy
  - ROC AUC Score
  - Confusion Matrix
  - Classification Report


## 🛠 Technologies Used

| Technology         | Purpose                                    |
|-------------------|---------------------------------------------|
| Python            | Core language for implementation            |
| Pandas, NumPy     | Data cleaning and manipulation               |
| Matplotlib, Seaborn | Visual exploration and plotting           |
| Scikit-learn      | Preprocessing, modeling, evaluation          |
| XGBoost           | Gradient boosting model                      |
| imbalanced-learn (SMOTE) | Handle class imbalance               |
| Jupyter Notebook  | Interactive experimentation and development |



## ⚙ Workflow Overview

1. **Data Loading**  
   Load customer-deal data (`smart_deal_recommendations.csv`)

2. **Preprocessing**
   - Drop duplicates and irrelevant columns  
   - Fill missing values with median/mode  
   - Encode categorical features  
   - Remove outliers using IQR  
   - Normalize numeric features

3. **Feature Engineering**  
   - Add interaction features (e.g., `age × income`, `discount × coupon`)  
   - Remove low-variance features  
   - Create polynomial features

4. **Balancing Classes**  
   - Use **SMOTE** to oversample the minority class

5. **Modeling**  
   - Train/test split  
   - Feature selection using RFE  
   - Tune hyperparameters (Logistic Regression)  
   - Compare with Random Forest and XGBoost

6. **Evaluation**  
   - Evaluate with Accuracy, AUC, Confusion Matrix, Classification Report  
   - Visualize confusion matrix


## 📈 Model Performance (Example)

| Model              | Accuracy | ROC AUC Score |
|-------------------|----------|---------------|
| Logistic Regression | 85%     | 0.87          |
| Random Forest       | 89%     | 0.90          |
| XGBoost             | 91%     | 0.92          |

---

## 👩‍💻 Contributor

**V.Venkata Sravani**  

## *📩 Feel free to reach out for any questions or collaboration opportunities!*
