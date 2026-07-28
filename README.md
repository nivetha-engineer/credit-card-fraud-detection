# credit-card-fraud-detection
A Machine Learning project that detects fraudulent credit card transactions using an imbalanced dataset. The project focuses on data preprocessing, exploratory data analysis (EDA), handling class imbalance, model training, hyperparameter tuning, and performance evaluation.

---

## 📌 Project Overview

Credit card fraud detection is a highly imbalanced binary classification problem where fraudulent transactions represent only a small fraction of all transactions. The goal of this project is to build a robust machine learning model capable of accurately identifying fraudulent transactions while minimizing false positives.

---

## 🎯 Objectives

- Understand the characteristics of fraudulent transactions.
- Perform comprehensive Exploratory Data Analysis (EDA).
- Handle the highly imbalanced dataset.
- Train multiple machine learning models.
- Tune model hyperparameters.
- Evaluate models using appropriate metrics for imbalanced classification.

---

## 📂 Dataset

- **Dataset:** Credit Card Fraud Detection Dataset
- **Source:** Kaggle
- **Features:** 31
  - **Time**
  - **Amount**
  - **V1 – V28** (PCA transformed features)
  - **Class** (Target)
    - 0 → Legitimate Transaction
    - 1 → Fraudulent Transaction

> **Note:** The features V1–V28 are principal components obtained using PCA to protect customer privacy.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## 📊 Exploratory Data Analysis

The project includes:

- Dataset overview
- Missing value analysis
- Duplicate value checking
- Class distribution visualization
- Correlation heatmap
- Distribution plots
- Boxplots for outlier analysis
- Transaction Amount analysis
- Time feature analysis

---

## 🤖 Machine Learning Models

The following models were trained and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

---

## ⚙ Hyperparameter Tuning

RandomizedSearchCV was used to optimize the Random Forest model for improved performance.

---

## 📈 Evaluation Metrics

Since the dataset is highly imbalanced, multiple evaluation metrics were used instead of relying only on accuracy.

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report

---

## 📁 Project Structure

```
Credit-Card-Fraud-Detection/
│
├── Credit Card Fraud Detection.ipynb
├── creditcard.csv
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Credit-Card-Fraud-Detection.git
```

2. Navigate to the project directory

```bash
cd Credit-Card-Fraud-Detection
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open:

```
Credit Card Fraud Detection.ipynb
```

---

## 📌 Key Learnings

- Working with highly imbalanced datasets
- Exploratory Data Analysis (EDA)
- Feature analysis
- Machine Learning model comparison
- Hyperparameter tuning
- Model evaluation using appropriate classification metrics

---

## 📌 Conclusion

This project demonstrates the complete machine learning workflow for detecting fraudulent credit card transactions using an imbalanced dataset. Through exploratory data analysis, preprocessing, model training, hyperparameter tuning, and evaluation with appropriate classification metrics, the project highlights the importance of handling class imbalance in real-world fraud detection problems. It also reinforces that metrics such as Precision, Recall, F1-Score, and ROC-AUC provide more meaningful insights than accuracy alone for imbalanced datasets.

---

## 📬 Contact

**Nivetha**

- GitHub: https://github.com/nivetha-engineer

If you found this project helpful, consider giving it a ⭐ on GitHub!

