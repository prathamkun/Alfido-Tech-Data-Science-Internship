# 🏦 Loan Prediction using Machine Learning

A Machine Learning project that predicts whether a loan application will be **approved or rejected** based on applicant details such as income, education, marital status, credit history, loan amount, and other financial attributes.

This project demonstrates the complete **Machine Learning pipeline**, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison using multiple classification algorithms.

---

## 📌 Project Overview

Financial institutions receive thousands of loan applications every day. Evaluating each application manually is time-consuming and prone to human error.

The goal of this project is to build an intelligent classification model that predicts loan approval status using historical applicant data.

---

## 🎯 Objectives

* Perform data cleaning and preprocessing
* Handle missing values
* Encode categorical variables
* Explore relationships between features using EDA
* Detect outliers and data distribution
* Scale numerical features
* Train multiple machine learning models
* Compare model performance
* Select the best model for deployment

---

## 📂 Dataset Information

* **Dataset:** Loan Prediction Dataset
* **Total Records:** 614
* **Features:** 11
* **Target Variable:** Loan_Status

### Features

* Gender
* Married
* Dependents
* Education
* Self_Employed
* ApplicantIncome
* CoapplicantIncome
* LoanAmount
* Loan_Amount_Term
* Credit_History
* Property_Area

### Target

* Loan_Status

  * 1 → Approved
  * 0 → Rejected

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Missing Value Analysis
* Correlation Heatmap
* Loan Status Distribution
* Applicant Income Distribution
* Loan Amount Distribution
* Applicant Income Box Plot
* Loan Amount Box Plot

Key findings:

* Credit History has the strongest influence on loan approval.
* Applicant Income is highly right-skewed.
* Loan Amount contains several outliers.
* The dataset is slightly imbalanced in favor of approved loans.

---

## ⚙️ Data Preprocessing

The following preprocessing steps were applied:

* Removed Loan_ID
* Handled missing values using Median and Mode imputation
* Label Encoding of categorical variables
* Train-Test Split (80:20)
* Standard Feature Scaling
* Class Weight Balancing for imbalanced classes

---

## 🤖 Machine Learning Models

### 1. Logistic Regression

A simple linear classification model used as the baseline.

### Results

* Accuracy: **80.49%**
* Precision: **84.27%**
* Recall: **88.24%**
* F1 Score: **86.21%**
* ROC-AUC: **80.96%**

---

### 2. Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees for improved prediction performance.

### Results

* Accuracy: **83.74%**
* Precision: **84.00%**
* Recall: **94.00%**
* F1 Score: **89.00%**
* ROC-AUC: **79.60%**

---

## 📈 Model Comparison

| Metric    | Logistic Regression | Random Forest |
| --------- | ------------------: | ------------: |
| Accuracy  |              80.49% |    **83.74%** |
| Precision |          **84.27%** |        84.00% |
| Recall    |              88.24% |    **94.00%** |
| F1 Score  |              86.21% |    **89.00%** |
| ROC-AUC   |          **80.96%** |        79.60% |

---

## 🏆 Best Model

Based on overall performance:

✅ **Random Forest Classifier**

Reasons:

* Highest Accuracy
* Highest Recall
* Better F1 Score
* Better overall classification performance

---


## 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/yourusername/Loan-Prediction-ML.git
```

### Navigate to the Project

```bash
cd Loan-Prediction-ML
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open **Loan_Prediction.ipynb** in:

* Google Colab
* Jupyter Notebook

Run all cells sequentially.

---

## 📷 Project Outputs

* Data Cleaning
* Feature Engineering
* Correlation Heatmap
* Distribution Plots
* Box Plots
* Logistic Regression Results
* Random Forest Results
* ROC Curve
* Confusion Matrix
* Classification Report

---

## 🔮 Future Improvements

* Hyperparameter tuning using GridSearchCV
* XGBoost and LightGBM implementation
* Cross-validation
* SHAP-based feature importance
* Deploy as a Flask/FastAPI web application
* Build an interactive Streamlit dashboard

---

## 👨‍💻 Author

**Prathamesh Borkar**



University of Mumbai

GitHub: https://github.com/prathamkun



---

## 📜 License

This project is created for educational and internship purposes.

Feel free to use, modify, and learn from the code.
