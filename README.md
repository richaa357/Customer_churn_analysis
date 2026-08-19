# 📊 Customer Churn Analysis

## 📌 Overview

Customer Churn Analysis is a Machine Learning project that analyzes
customer behavior and predicts whether a customer is likely to leave
a telecom service.

The project follows a complete Machine Learning workflow, including
data cleaning, exploratory data analysis, feature relevance analysis,
categorical encoding, feature scaling, model training, evaluation,
and feature importance analysis.

---

## 🎯 Problem Statement

Customer churn is a major challenge for telecom companies.

The objective of this project is to analyze customer information and
predict whether a customer will:

- `0` → Stay with the company
- `1` → Churn / Leave the company

The analysis can help identify customers who are more likely to leave
and understand the factors associated with customer churn.

---

## 🎯 Objectives

The main objectives of this project are:

- Understand the customer churn dataset
- Perform data cleaning and preprocessing
- Analyze missing values
- Identify relevant features using domain knowledge
- Perform Exploratory Data Analysis (EDA)
- Convert categorical data into numerical form
- Split the dataset into training and testing sets
- Apply feature scaling
- Train a classification model
- Evaluate model performance
- Analyze important features
- Draw meaningful conclusions from the data

---

## 📂 Dataset

The project uses the **Telco Customer Churn dataset**.

The dataset contains information about telecom customers,
their services, account information, and whether they churned.

### Important Features

| Feature | Description |
|---|---|
| `customerID` | Unique customer identifier |
| `gender` | Customer gender |
| `SeniorCitizen` | Whether the customer is a senior citizen |
| `Partner` | Whether the customer has a partner |
| `Dependents` | Whether the customer has dependents |
| `tenure` | Number of months the customer has stayed |
| `PhoneService` | Whether the customer has phone service |
| `MultipleLines` | Multiple phone lines |
| `InternetService` | Type of internet service |
| `OnlineSecurity` | Whether online security is subscribed |
| `OnlineBackup` | Whether online backup is subscribed |
| `DeviceProtection` | Whether device protection is subscribed |
| `TechSupport` | Whether technical support is subscribed |
| `StreamingTV` | Whether streaming TV is subscribed |
| `StreamingMovies` | Whether streaming movies is subscribed |
| `Contract` | Contract type |
| `PaperlessBilling` | Whether paperless billing is enabled |
| `PaymentMethod` | Customer payment method |
| `MonthlyCharges` | Monthly customer charges |
| `TotalCharges` | Total charges paid by customer |
| `Churn` | Whether the customer left the company |

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google-colab

---

# 🔄 Project Workflow

```text
Data Loading
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Missing Value Handling
     ↓
Feature Relevance Analysis
     ↓
Exploratory Data Analysis
     ↓
Categorical Encoding
     ↓
Train-Test Split
     ↓
Feature Scaling
     ↓
Model Training
     ↓
Prediction
     ↓
Model Evaluation
     ↓
Feature Importance

## 📊 Model Analysis & Visualizations

### 1. Churn Distribution

The count plot shows the distribution of customers who churned and
customers who stayed with the company.

![Churn Distribution](github.com/richaa357/Customer_churn_analysis/blob/main/images/1st.png)

---

### 2. Actual vs Predicted Churn

The heatmap represents the confusion matrix and compares the actual
churn values with the values predicted by the model.

![Actual vs Predicted Churn](github.com/richaa357/Customer_churn_analysis/blob/main/images/2nd.png)

---

### 3. Top 10 Important Features

The bar plot shows the top 10 features based on their importance in
the Logistic Regression model.

![Top 10 Important Features](github.com/richaa357/Customer_churn_analysis/blob/main/images/3rd.png)

---

### 4. Feature Coefficients

The bar plot shows the coefficients of the features used by the
Logistic Regression model.

Positive coefficients indicate a stronger tendency toward churn,
while negative coefficients indicate a lower tendency toward churn.

![Feature Coefficients](github.com/richaa357/Customer_churn_analysis/blob/main/images/4th.png)

     ↓
Conclusion
