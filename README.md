Assignment 3 – Predicting Policyholder Churn with Machine Learning
Week: 7

Duration: 2 weeks
Dataset: policyholder_churn.csv (created earlier in your Week 7 materials)
Deliverables: 1 Jupyter Notebook + 2–3-page brief report (PDF)
Weight: 15 % of course grade

Learning Objectives
By completing this assignment, students will be able to:
Apply supervised machine-learning methods for churn prediction in insurance data.
Perform data preprocessing, encoding, and scaling of mixed features.
Train and compare classification models (logistic regression, decision tree, random forest, and SVM).
Evaluate predictive performance using cross-validation and resampling methods.
Interpret model output in an actuarial context (e.g., retention strategy and risk-based pricing).

Dataset Description
The file policyholder_churn.csv contains 6 000 observations with the following columns:
Variable	Description
age	Policyholder age (18–80)
tenure_years	Years with the insurer
num_claims	Number of claims filed
policy_type	Type of insurance (Life / Health / Motor)
annual_premium	Annual premium amount
churn	Binary target (1 = policy lapsed, 0 = retained)


Assignment Tasks
Part A — Data Preparation (10 pts)
Load and inspect the dataset.
Handle missing values (if any).
Encode categorical features using one-hot or label encoding.
Standardize numerical variables.
Split data into train and test sets (70 % / 30 %).

Part B — Model Training (40 pts)
Fit four classification models:
Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (RBF kernel)
Use 5-fold cross-validation to estimate accuracy and ROC-AUC for each model.
Display results in a summary table.

Part C — Model Comparison & Interpretation (25 pts)
Compare models by their mean ROC-AUC and standard deviation.
Discuss bias-variance trade-offs for each method.
Identify key drivers of churn (e.g., premium levels, tenure).
Interpret the best model from an actuarial perspective (e.g., customer retention policy).

Part D — Resampling & Validation (15 pts)
Use bootstrap resampling (100 iterations) to estimate the confidence interval for the best model’s accuracy.
Compare bootstrap results with cross-validation estimates.
Briefly explain the advantages of resampling methods in insurance analytics.

Part E — Reporting (10 pts)
Summarize results in a 2–3 page PDF report including:
Tables of model accuracy and AUC
Plots (ROC curves, feature importance)
Short discussion of managerial implications for policyholder retention.
Suggested Structure for Notebook
Import libraries and dataset
Data cleaning and EDA
Encoding and scaling
Train/test split and cross-validation
Model training and comparison
Bootstrap validation
Interpretation and summary
