# Churn-analysis-using-machine-learning-
# Customer Churn Prediction

## Overview
This project predicts customer churn using machine learning models. The dataset contains customer demographics, account details, and usage patterns. The goal is to build models that can classify whether a customer will churn or not.

## Dataset
The dataset consists of various features such as:
- Customer demographic information
- Subscription details
- Service usage
- Monthly and total charges
- Churn status (target variable)

## Preprocessing Steps
1. Dropped irrelevant columns (e.g., `customerID`).
2. Handled missing values in `TotalCharges` by converting it to float and filling missing values with the median.
3. Encoded categorical variables using Label Encoding.
4. Scaled numerical features (`TotalCharges`, `MonthlyCharges`, `tenure`) using StandardScaler.

## Machine Learning Models Used
The following models were implemented to predict churn:
1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**
4. **Support Vector Machine (SVM)**
5. **Naïve Bayes**
6. **K-Nearest Neighbors (KNN)**
7. **K-Means Clustering**
8. **Mean Shift Clustering**
9. **Hierarchical Clustering**
10. **Linear Regression** (for experimental purposes, not ideal for classification)

## Model Evaluation
Each model's performance was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

## Results
The best-performing model achieved an accuracy of **78%**. Other models were evaluated for comparison.

## Installation & Usage
1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the Jupyter Notebook or Python script to train and evaluate models.

## Conclusion
This project provides insights into customer churn prediction and demonstrates the effectiveness of different ML algorithms. Further improvements can be made with hyperparameter tuning and feature engineering.

---
Let me know if you need any modifications! 🚀

