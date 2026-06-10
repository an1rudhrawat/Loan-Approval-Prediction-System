# Loan Approval Prediction System

## 📌 Overview

The Loan Approval Prediction System is a beginner-friendly machine learning project developed to predict whether a loan application is likely to be approved based on an applicant's financial, demographic, and employment information.

The purpose of this project is to understand and implement a complete machine learning pipeline, covering data cleaning, exploratory data analysis (EDA), preprocessing, feature engineering, model training, and performance evaluation.

---

## 🚀 Features

- Data cleaning and handling missing values
- Exploratory Data Analysis (EDA) with informative visualizations
- Understanding the relationship between applicant attributes and loan approval
- Encoding categorical variables
- Feature scaling using StandardScaler
- Correlation analysis using heatmaps
- Training and comparing multiple classification models
- Performance evaluation using classification metrics

---

## 📊 Dataset Features

The dataset contains applicant-related information, including:

- Gender
- Marital Status
- Education Level
- Employment Status
- Applicant Income
- Co-applicant Income
- Credit Score
- Debt-to-Income Ratio (DTI)
- Loan Purpose
- Property Area
- Employer Category

### Target Variable

**Loan Approved**
- Yes → Loan Approved
- No → Loan Rejected

---

## 🧠 Machine Learning Models Used

The project implements and compares different classification algorithms:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Gaussian Naive Bayes

Models are evaluated using:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Confusion Matrix

---

## 🛠️ Technologies and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔄 Machine Learning Workflow

1. Data collection and inspection
2. Handling missing values
3. Exploratory Data Analysis (EDA)
4. Data preprocessing and encoding
5. Feature scaling
6. Train-test data splitting
7. Model training
8. Model evaluation and comparison
9. Feature engineering experiments

---

## 📁 Project Structure

```
Loan-Approval-Prediction-System/
│
├── CreditWise_loan_system.ipynb      # Complete machine learning workflow
├── loan_approval_data.csv            # Dataset
├── README.md                         # Project documentation
```

---

## 🎯 Learning Objective

This project was created as part of my machine learning learning journey to gain hands-on experience with real-world datasets and understand how different machine learning algorithms behave under different preprocessing techniques.

Through this project, I strengthened my understanding of:

- Data cleaning and preprocessing
- Exploratory Data Analysis
- Feature encoding and scaling
- Classification algorithms
- Model evaluation techniques
- Comparing multiple machine learning approaches

---

## 🔮 Future Improvements

- Apply hyperparameter tuning using GridSearchCV
- Use cross-validation for more reliable model evaluation
- Experiment with advanced ensemble methods such as Random Forest and Gradient Boosting
- Develop a web application for real-time loan approval prediction
