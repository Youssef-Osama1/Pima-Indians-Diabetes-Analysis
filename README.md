# Pima Indians Diabetes Analysis

This project involves analyzing the Pima Indians Diabetes dataset to predict the likelihood of diabetes in individuals. It includes Exploratory Data Analysis (EDA), data preprocessing, and machine learning modeling using various classifiers.

---

## **Overview**

1. Performed comprehensive EDA to understand the data distribution and relationships.
2. Cleaned and preprocessed the dataset to handle missing and erroneous values.
3. Built three models: 
   - Logistic Regression
   - Random Forest
   - XGBoost
4. Compared models based on accuracy and ROC-AUC scores, finding **XGBoost** as the best-performing model with a **test accuracy of 81%**.

---

## **Dataset**

The dataset consists of medical diagnostic measurements and a binary outcome (`0` or `1`) indicating diabetes presence.

- **Source**: [Kaggle - Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- **Features**:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
  - Outcome (Target Variable: 0 = No Diabetes, 1 = Diabetes)

---

## **Project Steps**

### **1. Exploratory Data Analysis**
- Visualized feature distributions and relationships with the target variable.
- Examined correlations between variables using a heatmap.
- Checked for class imbalance in the target variable.

### **2. Data Preprocessing**
- Handled missing or erroneous values (e.g., replacing zero values in BMI, Glucose, and Insulin).
- Standardized features using `StandardScaler`.

### **3. Model Building**
- **Logistic Regression**: Baseline model with and without polynomial features.
- **Random Forest**: Improved accuracy by tuning hyperparameters.
- **XGBoost**: Achieved the highest accuracy and best performance metrics.

### **4. Evaluation**
- Compared models based on accuracy, classification reports, and ROC-AUC scores.

---

## **Results**

| Model                | Test Accuracy | ROC-AUC Score |
|----------------------|---------------|---------------|
| Logistic Regression  | 73%           | 0.76          |
| Random Forest        | 78%           | 0.79          |
| XGBoost              | **81%**       | **0.82**      |

---
