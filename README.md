# Customer Churn Prediction

## 📖 Overview  
This project focuses on predicting **customer churn** — identifying customers who are likely to discontinue a service or subscription.  
The notebook walks through an end-to-end machine learning workflow including **data preprocessing**, **exploratory data analysis (EDA)**, **feature engineering**, and **model evaluation** to support business decision-making and customer retention strategies.

---

## 🧩 Workflow Summary

### 1. Data Preprocessing  
- Load and inspect the customer dataset  
- Handle missing or inconsistent values  
- Encode categorical features (e.g., gender, contract type, payment method)  
- Normalize or scale numerical features for improved model performance  

### 2. Exploratory Data Analysis (EDA)  
- Explore churn distribution and feature relationships  
- Visualize churn rate by customer segments (e.g., tenure, payment type, internet service)  
- Correlation heatmap to identify key drivers of churn  

### 3. Feature Engineering  
- Create new binary or categorical features from existing attributes (e.g., contract length groups, service type combinations)  
- Drop irrelevant or redundant features  
- Handle imbalance in the target variable using **SMOTE** or **class weights**  

### 4. Model Training  
Several machine learning algorithms were tested and compared:  
- **Logistic Regression**  
- **Decision Tree (CART)**  
- **Random Forest**  
- **K-Nearest Neighbors (KNN)**  
- **Support Vector Machine (SVM)**  
- **Gradient Boosting / XGBoost / LightGBM**

---

## 5. Model Evaluation
Models were assessed using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **ROC-AUC Curve**

---

## 💡 Key Insights  
- Customers with **month-to-month contracts** and **electronic payment methods** have higher churn rates.  
- **Tenure**, **contract type**, and **technical support availability** are strong predictors of churn.  
- Ensemble models such as **Random Forest** and **XGBoost** outperform simple linear models.  

---

## 🛠️ Technologies Used  
- **Python 3**  
- **Pandas**, **NumPy** – data manipulation  
- **Matplotlib**, **Seaborn** – visualization  
- **Scikit-learn** – model building and evaluation  
- **XGBoost**, **LightGBM** – gradient boosting  
- **Jupyter Notebook** – documentation and execution  

---
