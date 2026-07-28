# credit-card-fraud-detection
Machine Learning project to detect fraudulent credit card transactions using classification models, SMOTE for class imbalance, and hyperparameter tuning.

Project Overview

This project builds a machine learning model to identify fraudulent credit card transactions. Since fraud detection datasets are highly imbalanced, SMOTE (Synthetic Minority Over-sampling Technique) was applied to balance the training data before model training.

Multiple classification algorithms were evaluated and compared using Precision, Recall, F1-Score, and ROC-AUC to identify the best-performing model.

Dataset
Source: Kaggle
Transactions: 284,807
Fraudulent Transactions: 492
Legitimate Transactions: 284,315

The dataset is extremely imbalanced, making fraud detection a challenging classification problem.

Project Workflow
Data Collection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Scaling
      ↓
Train-Test Split
      ↓
SMOTE
      ↓
Model Training
      ↓
Model Comparison
      ↓
Hyperparameter Tuning
      ↓
Final Evaluation
Exploratory Data Analysis

Performed:

Dataset summary
Missing value analysis
Class imbalance analysis
Amount distribution
Time distribution
Correlation heatmap
Outlier detection
Models Used
Logistic Regression
Decision Tree
Random Forest
XGBoost
Evaluation Metrics
Accuracy
Precision
Recall
F1-Score
ROC-AUC
Best Model

Random Forest achieved the best overall balance between Precision and Recall.

Example:

Model	Accuracy	Precision	Recall	F1-Score	ROC-AUC
Random Forest	0.9977	0.422	0.857	0.566	0.981


Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
Imbalanced-learn
Folder Structure
Credit-Card-Fraud-Detection/
│
├── Credit Card Fraud Detection.ipynb
├── README.md
├── requirements.txt
├── images/
│   ├── class_distribution.png
│   ├── correlation_heatmap.png
│   ├── roc_curve.png
│   └── confusion_matrix.png
└── dataset_link.txt
Future Improvements
Deep Learning models
AutoML
Explainability using SHAP
Real-time fraud detection
conculsion:
Random Forest was selected as the final model because it achieved the highest F1-score and ROC-AUC among all evaluated models. Applying SMOTE significantly improved the model's ability to detect fraudulent transactions in this highly imbalanced dataset.
