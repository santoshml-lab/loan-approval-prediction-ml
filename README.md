
![Feature Importance](https://github.com/santoshml-lab/loan-approval-prediction-ml/blob/main/feature_importance%20.png)
Loan Approval Prediction ML Pipeline
Overview
This project builds a machine learning pipeline to predict whether a loan will be Approved or Rejected using applicant financial data.
The pipeline automatically preprocesses the data, selects the best model, and generates feature importance insights.
Features
Automatic data preprocessing
Categorical encoding
Missing value handling
Automatic task detection (classification/regression)
Model comparison (Random Forest, Gradient Boosting, AdaBoost, Logistic Regression)
Best model selection
Feature importance visualization
Dataset Features
The dataset includes the following attributes:
no_of_dependents
education
self_employed
income_annum
loan_amount
loan_term
cibil_score
residential_assets_value
commercial_assets_value
luxury_assets_value
bank_asset_value
Target Variable:
loan_status (Approved / Rejected)
Model Performance
Best Model: RandomForestClassifier
Accuracy: ~98%
Key important feature:
CIBIL Score (most influential factor)
Output
The pipeline generates:
Feature importance graph
CSV report for feature importance
Tech Stack
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Imbalanced-learn (SMOTE)
How to Run
Clone the repository
Install dependencies
Run the notebook or pipeline script
pip install pandas numpy scikit-learn matplotlib imbalanced-learn
Result Visualization
Feature importance graph is generated after training.
Author
Machine Learning project for learning and experimentation.
