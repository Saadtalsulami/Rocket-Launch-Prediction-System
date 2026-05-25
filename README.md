# Rocket Launch Prediction System

<p align="center">

<img src="https://img.shields.io/badge/Python-3.9+-blue?style=for-the-badge&logo=python"/>
<img src="https://img.shields.io/badge/Machine-Learning-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/XGBoost-Gradient%20Boosting-red?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Random-Forest-green?style=for-the-badge"/>
<img src="https://img.shields.io/badge/SMOTE-Imbalanced%20Learning-purple?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge"/>

</p>

<p align="center">

AI-powered machine learning system for predicting rocket launch mission outcomes using historical aerospace launch data and predictive analytics techniques.

</p>

---

# Project Overview

This project presents a machine learning-based rocket launch prediction system designed to classify launch mission outcomes using historical aerospace data.

The system applies a complete end-to-end machine learning workflow including:

- Data cleaning
- Exploratory data analysis
- Feature engineering
- Imbalanced data handling
- Model training
- Performance evaluation
- Predictive analytics

The implementation demonstrates how machine learning techniques can support aerospace analytics and mission outcome prediction tasks.

---

# Machine Learning Pipeline

1. Data Collection
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Imbalanced Data Handling
6. Model Training
7. Model Evaluation
8. Performance Analysis

---

# Data Preparation

The dataset preprocessing pipeline included:

- Loading the cleaned rocket launch dataset
- Removing irrelevant columns
- Handling missing values
- Selecting operational launch features
- Preparing the target variable for classification

### Selected Features

- Company Name
- Location
- Launch Date
- Rocket Status

### Target Variable

- Mission Status

---

# Exploratory Data Analysis

Exploratory analysis was performed to better understand:

- Dataset structure
- Launch outcome distribution
- Feature relationships
- Class imbalance patterns

The analysis phase included statistical summaries and data visualization techniques.

---

# Feature Engineering

The project applied multiple feature engineering techniques including:

- Date feature extraction
- Year / Month / Day separation
- One-Hot Encoding
- Label Encoding
- Feature scaling using StandardScaler

These transformations improved model learning and predictive performance.

---

# Handling Class Imbalance

To improve classification performance across minority classes, the project utilized:

## SMOTE (Synthetic Minority Oversampling Technique)

SMOTE was applied to generate balanced training samples and reduce prediction bias toward majority classes.

### Benefits

- Improved minority class learning
- Reduced imbalance bias
- Better classification generalization
- Improved recall performance

---

# Machine Learning Models

## Random Forest Classifier

Random Forest was implemented using:

- n_estimators = 200
- class_weight = balanced

### Model Strengths

- Robust ensemble learning
- Reduced overfitting
- Strong classification stability
- Effective feature importance analysis

---

## XGBoost Classifier

XGBoost was implemented as a gradient boosting classifier for advanced predictive analytics.

### Model Strengths

- High predictive performance
- Efficient boosting mechanism
- Strong generalization capability
- Optimized classification learning

---

# Model Evaluation Results

## Evaluation Metrics

The project utilized multiple evaluation metrics including:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

# Model Comparison

| Model | Accuracy |
|---|---|
| Random Forest | ~89% |
| XGBoost | ~88% |

The Random Forest classifier achieved slightly higher overall accuracy, while XGBoost demonstrated strong generalization and boosting performance.

---

# Feature Importance Analysis

Feature importance analysis was performed to identify the most influential variables affecting rocket launch mission outcomes.

The analysis provided insights into historical launch behavior patterns and operational launch characteristics influencing prediction performance.

---

# Results & Insights

### Key Findings

- Most mission outcome classes were predicted successfully.
- SMOTE significantly improved minority class prediction.
- Feature engineering enhanced overall classification performance.
- Ensemble learning models demonstrated strong predictive capabilities.

---

# Potential Applications

Potential real-world applications include:

- Aerospace mission analytics
- Predictive launch risk assessment
- Mission success forecasting
- Aerospace operational analysis
- Historical launch performance evaluation
- AI-driven aerospace decision support systems

---

# Tech Stack

| Category | Technology |
|---|---|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Imbalanced Learning | SMOTE |
| Classification Models | Random Forest, XGBoost |

---

# Project Structure

```bash
rocket-launch-prediction-system/
│
├── datasets/
├── notebooks/
├── outputs/
├── images/
│
├── README.md
└── requirements.txt
