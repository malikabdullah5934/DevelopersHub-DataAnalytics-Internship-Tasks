# Data Science Mini Projects

This repository contains five small-scale machine learning and data analysis projects focusing on data exploration, visualization, and predictive modeling. Each task uses a real-world dataset and applies relevant techniques to achieve the objective.

---

## **Task 1: Exploring and Visualizing the Iris Dataset**
### **Objective**
Understand how to read, summarize, and visualize a dataset.

### **Approach**
- Loaded dataset using `pandas` and inspected it using `.shape`, `.columns`, `.head()`.
- Created:
  - **Scatter Plot** to analyze variable relationships.
  - **Histogram** to examine feature distribution.
  - **Box Plot** to detect outliers and spread.
- Used `matplotlib` and `seaborn` for visualization.

### **Results & Insights**
- Clear separation observed between some iris species in petal dimensions.
- Setosa species forms a distinct cluster compared to Versicolor and Virginica.
- Minimal outliers present.

---

## **Task 2: Credit Risk Prediction**
### **Objective**
Predict whether a loan applicant is likely to default.

### **Approach**
- Loaded Kaggle Loan Prediction dataset.
- Handled missing values with median/mode imputation.
- Performed EDA on loan amount, education, and applicant income.
- Trained **Logistic Regression** and **Decision Tree** classifiers.
- Evaluated models using **Accuracy** and **Confusion Matrix**.

### **Results & Insights**
- Decision Tree achieved slightly higher accuracy (~78%) compared to Logistic Regression (~75%).
- Education level and applicant income strongly influenced default likelihood.
- Most defaults occurred among applicants with lower incomes.

---

## **Task 3: Customer Churn Prediction**
### **Objective**
Identify customers likely to leave the bank.

### **Approach**
- Cleaned dataset and encoded categorical variables:
  - Geography (One-Hot Encoding)
  - Gender (Label Encoding)
- Trained **Logistic Regression** and **Random Forest Classifier**.
- Analyzed feature importance.

### **Results & Insights**
- Random Forest achieved ~86% accuracy.
- Key factors influencing churn:
  - Number of products
  - Customer tenure
  - Balance
- Customers with lower tenure and fewer products were more likely to leave.

---

## **Task 4: Predicting Insurance Claim Amounts**
### **Objective**
Estimate medical insurance charges based on personal data.

### **Approach**
- Trained a **Linear Regression** model on the Medical Cost dataset.
- Visualized relationships between BMI, age, smoking status, and charges.
- Evaluated model performance using **MAE** and **RMSE**.

### **Results & Insights**
- MAE ≈ 4100, RMSE ≈ 6000.
- Smokers and higher BMI individuals had significantly higher charges.
- Age also positively correlated with charges.

---

## **Task 5: Personal Loan Acceptance Prediction**
### **Objective**
Predict which customers will accept a personal loan offer.

### **Approach**
- Explored dataset focusing on age, job type, and marital status.
- Trained **Logistic Regression** and **Decision Tree** classifiers.
- Analyzed results for business insights.

### **Results & Insights**
- Decision Tree achieved ~82% accuracy.
- Likelihood of acceptance higher among:
  - Middle-aged customers
  - Customers with professional/managerial jobs
  - Married customers with higher incomes

---

## **Tools & Libraries Used**
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## **General Insights**
Across projects:
- **EDA (Exploratory Data Analysis)** is crucial for understanding data patterns and distributions.
- **Handling missing values** appropriately can significantly improve model performance.
- **Feature importance analysis** provides actionable business insights beyond raw predictions.

---
