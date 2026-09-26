# Salary Prediction using Linear Regression

## 📌 Overview

A beginner machine learning project that predicts **salary based on years of experience** using Linear Regression.

The project covers:

* Data preparation
* Train/test splitting
* Model training and prediction
* Model evaluation
* 5-Fold Cross-Validation

## 📊 Dataset

The model uses:

* `YearsExperience` — input feature
* `Salary` — target variable

```text
Years of Experience → Salary
```

## 🧠 Model

**Linear Regression** from Scikit-learn.

The model learns a linear relationship between experience and salary and uses it to make predictions.

## 📈 Results

| Metric         |        Result |
| -------------- | ------------: |
| Test Samples   |            12 |
| MSE            | 37,867,393.39 |
| RMSE           |      6,153.65 |
| R²             |        0.9532 |
| 5-Fold CV RMSE |      5,167.38 |

The RMSE represents the typical size of prediction errors in salary units.

The R² score of `0.9532` means the model explains approximately **95.3% of the variation in salary** on the test set.

## 🔄 Cross-Validation

5-Fold Cross-Validation was applied to the training data to evaluate how consistently the model performs across different subsets of the data.

## 🛠️ Technologies

* Python
* Pandas
* NumPy
* Scikit-learn

## 🚀 Future Improvements

* Analyze individual prediction errors
* Try other regression models
* Add more features
* Compare model performance
* Build a simple frontend for predictions

## 📚 Purpose

This project was created to practice the fundamentals of **machine learning regression**, including training, prediction, evaluation, and cross-validation.

