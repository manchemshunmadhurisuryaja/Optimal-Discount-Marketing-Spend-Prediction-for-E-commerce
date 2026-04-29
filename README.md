# 📊 Optimal Discount & Marketing Spend Prediction for E-commerce

## 📌 Project Overview

This project focuses on predicting **Units Sold** in an e-commerce platform using machine learning models. The main goal is to identify the **optimal discount and marketing spend** that maximize sales.

The project compares multiple regression models and evaluates their performance using different train-test splits.

---

## 🎯 Objectives

* Predict **Units_Sold** using machine learning models
* Compare performance of:

  * Random Forest Regressor
  * XGBoost Regressor
  * Support Vector Regressor (SVR)
* Evaluate models using different train-test ratios (70-30, 75-25, 80-20)
* Identify the **best model**
* Find optimal values for:

  * Discount
  * Marketing Spend

---

## 🗂️ Dataset Information

* **Dataset Name:** Ecommerce Sales Prediction Dataset
* **Source:** Kaggle
* **Records:** 1000
* **Features:** 7
* **Target Variable:** Units_Sold

### Features Used:

* Discount
* Marketing_Spend

---

## ⚙️ Technologies Used

* Python
* Google Colab
* Libraries:

  * pandas
  * numpy
  * matplotlib
  * seaborn
  * scikit-learn
  * xgboost
  * scipy

---

## 🔄 Data Preprocessing

* Removed unnecessary column: `Date`
* Encoded categorical features
* Checked for:

  * Missing values ❌ (none found)
  * Duplicates ❌ (none found)

---

## 🤖 Models Implemented

1. Random Forest Regressor
2. XGBoost Regressor
3. Support Vector Regressor (SVR)

---

## 🏆 Best Model

* ✅ **Support Vector Regressor (SVR)**
* Best performance at **70-30 split**
* Lowest MAE and MSE

---

## 📈 Optimization Results

* **Optimal Discount:** 0.00%
* **Optimal Marketing Spend:** $100
* **Maximum Predicted Units Sold:** 30.16

---

## 🔍 Key Insights

* Increasing **marketing spend** improves sales
* Discounts help, but excessive discount may reduce effectiveness
* SVR performed better than ensemble models for this dataset
---

## 🚀 How to Run the Project

```bash
# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn xgboost scipy

# Run the notebook
Open Ecommerce code file.ipynb in Jupyter/Colab
```

---

## 📌 Future Improvements

* Use more features like Price, Category, Customer Segment
* Apply hyperparameter tuning
* Try deep learning models
* Use real-world dataset instead of synthetic data

---
