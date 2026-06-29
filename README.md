# 💳 Credit Risk Classification using Machine Learning

## 📌 Project Overview

This project builds a machine learning model to predict a customer's **Credit Score** (**Poor**, **Standard**, or **Good**) using financial, banking, and credit-related information. It demonstrates an end-to-end machine learning workflow, including exploratory data analysis, preprocessing, feature engineering, model training, hyperparameter tuning, and evaluation.

---

## 🎯 Objective

The objective is to classify customers into different credit score categories to help financial institutions assess creditworthiness and support informed lending decisions.

---

## 📂 Repository Structure

```
Credit-Risk-Classification/
│
├── data/
│   ├── raw_dataset.zip
│   ├── Credit_dataset.csv
│   └── README.md
│
├── notebooks/
│   ├── credit risk prediction.ipynb
│   ├── model training and evaluation.ipynb
│   └── README.md
│
├── images/
│   ├── heatmap_correlation.png
│   ├── feature_importance.png
│   ├── roc-curve.png
│   ├── Model_Comparison.csv
│   ├── outliers.png
│   └── README.md
│
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

The dataset contains customer financial and credit information, including:

* Age
* Annual Income
* Monthly In-hand Salary
* Number of Bank Accounts
* Number of Credit Cards
* Interest Rate
* Number of Loans
* Outstanding Debt
* Credit Utilization Ratio
* Payment Behaviour
* Occupation
* Credit History
* Loan Types
* Monthly Balance
* EMI Information

### Target Variable

**Credit_Score**

* Poor
* Standard
* Good

---

## 🔍 Exploratory Data Analysis

EDA included:

* Dataset overview
* Summary statistics
* Missing value analysis
* Duplicate analysis
* Numerical feature distributions
* Categorical feature distributions
* Correlation heatmap
* Target class distribution
* Outlier detection using boxplots

---

## 🛠 Data Preprocessing

The preprocessing pipeline included:

* Removing irrelevant columns
* Handling missing values
* Cleaning invalid entries
* Encoding categorical variables
* Multi-label encoding for loan types
* Feature engineering
* Outlier treatment
* Feature scaling

---

## ⚙️ Feature Engineering

The following features were created:

* Debt_to_Income
* EMI_to_Salary
* Loans_per_History

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Extra Trees Classifier

RandomizedSearchCV was used for hyperparameter tuning.

---

## 📈 Model Evaluation

Performance was evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Classification Report
* Confusion Matrix
* ROC Curve
* Feature Importance

---

## 🏆 Results

| Model               |                            Accuracy |
| ------------------- | ----------------------------------: |
| Logistic Regression |                              60.14% |
| Decision Tree       |                              71.01% |
| Random Forest       |                              79.50% |
| Extra Trees         |                              79.17% |

The Random Forest model achieved the best performance among the evaluated models before and after tuning.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository.
2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebooks.

4. Run them in the following order:

* `credit risk prediction.ipynb`
* `model training and evaluation.ipynb`

---

## 📌 Future Improvements

* Experiment with gradient boosting algorithms such as XGBoost, LightGBM, or CatBoost.
* Address class imbalance using techniques such as SMOTE.
* Deploy the trained model as a web application.
* Build an interactive dashboard for credit score prediction.

---

## 👩‍💻 Author

**Avni Srivastava**

Machine Learning | Data Science | Python

