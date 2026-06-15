# Loan Approval Prediction Model

## Overview

This project focuses on predicting loan approval status using Machine Learning techniques. The objective is to analyze applicant information and determine whether a loan application is likely to be approved based on various factors such as income, credit history, loan amount, employment status, and other relevant features.

Two machine learning algorithms were implemented and evaluated:

* Linear Regression
* Decision Tree Classifier

## Dataset

The dataset contains information about loan applicants and includes features such as:

* Applicant Income
* Co-applicant Income
* Loan Amount
* Loan Term
* Credit History
* Gender
* Marital Status
* Education
* Self Employment Status
* Property Area

The target variable is the loan approval status.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook
* Matplotlib

## Methodology

1. Data Collection and Loading
2. Data Cleaning and Preprocessing
3. Feature Selection and Encoding
4. Train-Test Split
5. Model Training
6. Performance Evaluation
7. Accuracy Comparison

## Models Implemented

### 1. Linear Regression

Linear Regression was used as a baseline model to understand the relationship between applicant features and loan approval outcomes.

**Accuracy Achieved:** 50%

### 2. Decision Tree Classifier

A Decision Tree Classifier was implemented to capture non-linear relationships within the dataset and improve classification performance.

**Accuracy Achieved:** 61%

## Results

| Model                    | Accuracy |
| ------------------------ | -------- |
| Linear Regression        | 50%      |
| Decision Tree Classifier | 61%      |

The Decision Tree Classifier outperformed the Linear Regression model, demonstrating its ability to better handle complex decision boundaries in loan approval prediction tasks.

## Future Improvements

* Hyperparameter Tuning
* Feature Engineering
* Ensemble Methods (Random Forest, XGBoost)
* Cross Validation
* Deployment as a Web Application using Flask or Streamlit

## Conclusion

This project demonstrates the application of machine learning techniques for loan approval prediction. Among the models tested, the Decision Tree Classifier achieved the highest accuracy of 61%, making it the better-performing model for this dataset.

## Author

Gourang A M

Software Engineer | AI & Machine Learning Enthusiast

Skills: Python, Machine Learning, FastAPI, Django, Pandas, NumPy, AWS Cloud Foundations
