# 💳 Credit Card Fraud Detection

## Description

Credit Card Fraud Detection is a machine learning project focused on identifying fraudulent credit card transactions using a real-world, highly imbalanced dataset. The project applies data preprocessing, exploratory data analysis (EDA), feature scaling, and classification techniques to distinguish fraudulent activities from legitimate transactions. A Logistic Regression model was developed as a baseline solution to detect fraud patterns and support financial transaction security.

## Problem Statement

Credit card fraud poses significant financial risks to both consumers and financial institutions. Due to the highly imbalanced nature of transaction data, detecting fraudulent activities accurately remains a challenging task. This project aims to build a machine learning model capable of identifying fraudulent transactions while minimizing false positives and false negatives.

## Dataset

The dataset contains anonymized transaction records with:

* Features V1 to V28 (PCA-transformed variables)
* Time
* Amount
* Class (0 = Legitimate Transaction, 1 = Fraudulent Transaction)

## Key Features

* Exploratory Data Analysis (EDA)
* Fraud vs Non-Fraud Distribution Analysis
* Correlation Heatmap Visualization
* Data Preprocessing and Feature Scaling
* Logistic Regression Classification Model
* Performance Evaluation using Classification Metrics
* Fraud Detection Prediction

## Methodology

1. Data Collection and Exploration
2. Class Distribution Analysis
3. Correlation Analysis
4. Feature Scaling using StandardScaler
5. Data Preparation and Feature Engineering
6. Logistic Regression Model Training
7. Model Evaluation and Validation

## Results

* Successfully trained a Logistic Regression model for fraud detection.
* Evaluated performance using Confusion Matrix and Classification Report.
* Achieved effective fraud identification despite class imbalance.
* Established a strong baseline model for future improvements and advanced fraud detection techniques.

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## How to Run

```bash
git clone <repository-link>
cd Credit_Card_Fraud_Detection
pip install -r requirements.txt
jupyter notebook
```

## Future Improvements

* Implement Random Forest and XGBoost models.
* Address class imbalance using SMOTE and resampling techniques.
* Perform hyperparameter tuning for improved performance.
* Deploy the model as a web application.
* Explore deep learning approaches for fraud detection.

