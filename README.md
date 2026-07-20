# CodeAlpha_task1
# 💳 Credit Scoring Model using Machine Learning

A complete end-to-end Machine Learning project that predicts an individual's **creditworthiness** based on historical financial and personal information. This project demonstrates the complete ML workflow, including data preprocessing, exploratory data analysis, feature engineering, model building, hyperparameter tuning, and model evaluation using multiple classification algorithms.

---

## 📌 Project Objective

The objective of this project is to build a predictive model that classifies loan applicants as **Good Credit** or **Bad Credit** based on their financial and demographic information.

The model helps financial institutions automate credit risk assessment, reduce default risk, and support informed loan approval decisions.

---

## 📂 Dataset

**Dataset:** German Credit Dataset

The dataset contains **1000 customer records** with **20 input features** and **1 target variable**.

### Features Include

- Status of existing checking account
- Loan duration
- Credit history
- Loan purpose
- Credit amount
- Savings account status
- Employment duration
- Installment rate
- Personal status and gender
- Other debtors/guarantors
- Residence duration
- Property
- Age
- Other installment plans
- Housing
- Existing credits
- Job
- Number of dependents
- Telephone
- Foreign worker status

### Target Variable

- **Good Credit**
- **Bad Credit**

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

# 📊 Project Workflow

```
Problem Understanding
        │
        ▼
Data Collection
        │
        ▼
Data Exploration
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Feature Engineering
        │
        ▼
Encoding & Feature Scaling
        │
        ▼
Train-Test Split
        │
        ▼
Machine Learning Models
        │
        ▼
Model Evaluation
        │
        ▼
Hyperparameter Tuning
        │
        ▼
Feature Importance Analysis
        │
        ▼
Model Saving
```

---

# 🔍 Exploratory Data Analysis

Performed comprehensive exploratory analysis including:

- Target variable distribution
- Age distribution
- Credit amount distribution
- Loan duration analysis
- Housing status analysis
- Savings account analysis
- Loan purpose analysis
- Job category analysis
- Credit amount vs Credit Risk
- Age vs Credit Risk
- Correlation Heatmap
- Pair Plot
- Outlier Detection using Boxplots

---

# ⚙️ Feature Engineering

New features were created to improve model performance.

- Age Group
- Loan Category
- Long-Term Loan Indicator

Additionally,

- Target Variable Encoding
- One-Hot Encoding
- Feature Scaling using StandardScaler

were applied during preprocessing.

---

# 🤖 Machine Learning Models

The following classification algorithms were implemented and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

# 📈 Model Evaluation Metrics

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report
- ROC Curve
- ROC-AUC Score

---

# 🎯 Hyperparameter Tuning

The Random Forest model was optimized using **GridSearchCV** with 5-fold Cross Validation.

Optimized Parameters:

- Number of Trees
- Maximum Depth
- Minimum Samples Split
- Minimum Samples Leaf
- Maximum Features

---

# 📌 Feature Importance

Random Forest Feature Importance was used to identify the most influential variables affecting customer creditworthiness.

Some of the important features include:

- Credit Amount
- Loan Duration
- Checking Account Status
- Credit History
- Age

---

# 📁 Project Structure

```
Credit-Scoring-Model
│
├── data
│   └── german_credit_data.csv
│
├── notebooks
│   └── Credit_Scoring_Model.ipynb
│
├── models
│   ├── credit_scoring_model.pkl
│   └── scaler.pkl
│
├── outputs
│   ├── Confusion_Matrix.png
│   ├── ROC_Curve.png
│   ├── Feature_Importance.png
│   └── Credit_Predictions.csv
│
├── requirements.txt
│
├── README.md
│
└── app.py (Optional)
```

---

# 📌 Key Learning Outcomes

- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Categorical Encoding
- Feature Scaling
- Binary Classification
- Model Comparison
- Hyperparameter Tuning
- Feature Importance Analysis
- Model Serialization using Joblib
