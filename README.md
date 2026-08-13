# Relational Database to Machine Learning Analytics Pipeline

## 📌 Project Overview
This project simulates an enterprise-level data workflow. Instead of using isolated CSV files, it writes a custom SQL query to extract and aggregate live transaction data from separate relational tables. The data is then fed into a modular Python pipeline that cleans, encodes, scales, and evaluates 5 machine learning classification algorithms alongside a continuous linear regression model.

## 🛠️ Skills & Technologies Demonstrated
- **Data Engineering & Retrieval:** SQL (JOINs, GROUP BY, Aggregate Functions, COALESCE).
- **Data Pipeline & Manipulation:** Python, Pandas, NumPy.
- **Feature Engineering:** StandardScaler, One-Hot Encoding, Median Imputation, Stratified Train-Test-Split.
- **Algorithms benchmarked:** Logistic Regression, Decision Trees, Random Forest, Support Vector Machines (SVM), K-Nearest Neighbors (KNN), and Linear Regression.

## 🚀 How It Works
1. **Relational Extraction:** Combines user demographic data with transactional history to calculate total spending, count of orders, and return rates per customer.
2. **Pre-processing:** Automates data cleaning by handling missing values, encoding text fields, and applying `StandardScaler` to normalize dimensions for distance-heavy models like KNN and SVM.
3. **Model Battleground:** Benchmarks multiple classification models simultaneously using classification reports (Precision, Recall, F1-Score) to see which algorithm handles the data best.
