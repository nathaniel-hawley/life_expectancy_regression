# 📈 Life Expectancy Prediction with Regression Models

This project uses regression modeling to predict a country's life expectancy based on global health, education, and economic indicators.

## 📊 Overview

Using the UCI Life Expectancy dataset, I evaluated multiple regression models including linear, polynomial, and ensemble methods. The goal was to maximize predictive performance while identifying key factors that impact life expectancy.

## 🧠 Key Features

- Cleaned and normalized multivariate data
- Tested linear vs. non-linear regression models
- Used LazyPredict for model benchmarking
- Evaluated results using R², MAE, and residual analysis
- Achieved **R² = 0.97** with ExtraTreesRegressor

## 🛠️ Models Tested

- ✅ Extra Trees Regressor (Best performance)
- Random Forest
- LightGBM
- Ridge Regression
- Multiple Linear Regression
- Polynomial Regression

## 📈 Results Summary

| Model                    | R² Score |
|--------------------------|----------|
| Extra Trees Regressor    | 0.97     |
| Random Forest            | 0.96     |
| Multiple Linear Regression | 0.76   |
| Polynomial Regression    | -3.31 (overfit)

## 📁 Files Included

- `life_expectancy_model.ipynb` – full notebook
- `images/` – feature importance, residuals, model diagnostics
- `requirements.txt` – Python packages used

## 🧪 Data Source

[UCI Life Expectancy Dataset](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)

## 🚀 How to Run

```bash
pip install -r requirements.txt
