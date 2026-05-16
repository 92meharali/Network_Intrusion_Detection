# Network Intrusion Detection using Classical ML

## Overview
This repository contains a comprehensive Machine Learning pipeline for Network Intrusion Detection. The project compares multiple classical machine learning models (Logistic Regression, Random Forest, XGBoost) to classify network traffic anomalies using standard datasets like **NSL-KDD** and **CIC-IDS2017**.

## Features
- **Exploratory Data Analysis (EDA):** Deep dive into network traffic features to understand data distributions.
- **Data Preprocessing:** Robust handling of categorical variables (Label Encoding) and numerical scaling (StandardScaler).
- **Model Training:** Training and evaluating Logistic Regression, Random Forest, and XGBoost classifiers.
- **Feature Engineering:** Analysis of feature importance extracted from tree-based models to understand key network anomaly indicators.

## Technologies Used
- Scikit-Learn (Classical ML Models, Preprocessing, Metrics)
- XGBoost (Gradient Boosting)
- Pandas (Data Manipulation)
- Matplotlib & Seaborn (Visualization)

## How to Use
1. Clone the repository.
2. Install dependencies: `pip install pandas scikit-learn xgboost matplotlib seaborn`.
3. Run `Network_Intrusion_Detection.ipynb`. The notebook handles the downloading of the NSL-KDD dataset automatically.
