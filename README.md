# Creditworthiness Prediction Using Machine Learning

## Project Overview

The **Credit Score Prediction** project uses Machine Learning classification algorithms to predict whether a loan applicant is likely to default on a loan.

The project analyzes financial and personal information such as annual income, employment experience, loan amount, interest rate, home ownership, and previous credit default history.

The goal is to build a classification model that helps assess credit risk and supports better lending decisions.

## Objectives

- Analyze applicants' financial and credit-related information.
- Perform data cleaning and exploratory data analysis (EDA).
- Apply feature engineering to improve model performance.
- Build and compare multiple Machine Learning classification models.
- Evaluate models using standard classification metrics.
- Save the best-performing model for future predictions.

### Features Description

| Feature | Description |
|---|---|
| person_age | Age of the applicant |
| person_income | Annual income of the applicant |
| person_home_ownership | Home ownership status |
| person_emp_length | Employment experience in years |
| loan_intent | Purpose of the loan |
| loan_grade | Loan risk grade |
| loan_amnt | Loan amount |
| loan_int_rate | Loan interest rate |
| loan_status | Target variable (0 or 1) |
| loan_percent_income | Loan amount as a percentage of income |
| cb_person_default_on_file | Previous default history |
| cb_person_cred_hist_length | Length of credit history |

### Target Variable

- `0` – Loan not defaulted
- `1` – Loan defaulted

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Algorithms

The following classification algorithms are implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

## Project Workflow

1. Import required libraries.
2. Load and understand the dataset.
3. Perform data cleaning and preprocessing.
4. Handle missing values and duplicate records.
5. Perform Exploratory Data Analysis (EDA).
6. Create additional features using feature engineering.
7. Separate independent and dependent variables.
8. Split the dataset into training and testing sets.
9. Encode categorical features and scale numerical features.
10. Train classification models.
11. Evaluate and compare model performance.

## Model Evaluation

The models are evaluated using the following metrics:

- **Accuracy:** Measures the overall percentage of correct predictions.
- **Precision:** Measures how many predicted defaults are actually defaults.
- **Recall:** Measures how many actual defaults are correctly identified.
- **F1-Score:** Balances precision and recall.
- **ROC-AUC:** Measures the model's ability to distinguish between default and non-default applicants.

## Installation and Setup

### 1. Clone the Repository

```bash
git https://github.com/sachinsky63/CodeAlpha_Credit_Score_Model.git
```

### 2. Navigate to the Project Directory

```bash
cd Creditworthiness-Prediction
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run Jupyter Notebook

```bash
jupyter notebook
```

Open `Credit_score_Prediction.ipynb` and execute the cells.

## Model Output

The project compares Logistic Regression, Decision Tree, and Random Forest using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.


## Conclusion

This project demonstrates how Machine Learning classification algorithms can be used to analyze financial information and predict loan default risk.

It provides practical experience in data preprocessing, exploratory data analysis, feature engineering, model training, and model evaluation.

## Author

**Sachin Kumar Yadav**

- GitHub: [sachinsky63](https://github.com/sachinsky63)
- LinkedIn: [Sachin Kumar Yadav](https://www.linkedin.com/in/sachin-kumar-yadav-sky/)
