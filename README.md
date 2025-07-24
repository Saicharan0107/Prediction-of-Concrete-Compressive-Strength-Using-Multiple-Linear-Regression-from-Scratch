# Prediction-of-Concrete-Compressive-Strength-Using-Multiple-Linear-Regression-from-Scratch

This project demonstrates the implementation of **Multiple Linear Regression (MLR)** from scratch (without using libraries like `scikit-learn`) to predict the **compressive strength of concrete** based on its ingredients.

## 📌 Project Overview

Concrete compressive strength depends on ingredients such as cement, water, coarse/fine aggregate, age, etc. This project builds a multiple linear regression model using Python, leveraging **NumPy**, **Pandas**, and **Matplotlib**, and performs the entire modeling pipeline manually.

## 💡 Key Features

- Manual implementation of gradient descent for MLR
- Evaluation using R², MSE, MAE
- Residual analysis and data visualization
- No use of `scikit-learn` or other ML libraries

## 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib

## 📊 Dataset

- Source: [UCI Concrete Compressive Strength Dataset](https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength)
- Features include:
  - Cement
  - Blast Furnace Slag
  - Fly Ash
  - Water
  - Superplasticizer
  - Coarse Aggregate
  - Fine Aggregate
  - Age (days)
- Target: Concrete compressive strength (MPa)

## 🚀 How to Run

1. Clone the repository:
   
   git clone https://github.com/Saicharan0107/concrete-strength-mlr.gitcd concrete-strength-mlr
2. Install dependencies:
pip install numpy pandas matplotlib


📈 Results & Visualizations
Regression coefficients interpreted

R² score computed manually

Plots:

Residuals vs Fitted

Actual vs Predicted strength

Histogram of residuals

📚 Learnings
Hands-on understanding of linear regression mathematics

Gradient descent and cost function optimization

Model evaluation without relying on ML libraries

✅ Future Work
Implement regularization (Ridge/Lasso) manually

Polynomial regression extension

Support for normalization and feature scaling
