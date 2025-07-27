# 📈 Time Series Forecasting - Taxi Orders

## 📝 Project Overview

This project uses historical taxi order data to predict the number of orders for the next hour. The goal is to help **Sweet Lift Taxi** attract more drivers during peak times by accurately forecasting demand.

The final model must achieve a **Root Mean Squared Error (RMSE)** below **48** on the test set.

## 📂 Project Structure

- **Resampling:** Convert raw data to hourly intervals.
- **Exploratory Analysis:** Visualization and time series decomposition.
- **Modeling:** Train multiple models with various hyperparameters.
- **Evaluation:** Use a 10% test split to assess performance.

## 📊 Dataset

The dataset is provided in the file `taxi.csv` and contains the following key column:

- `num_orders` – the number of taxi orders per hour.

## 🧠 Models Used

- Random Forest
- Linear Regression
- Lasso Regression
- LightGBM
- CatBoost
- XGBoost

## 🧪 Evaluation Metric

The main metric used is:

- **RMSE (Root Mean Squared Error)**

## ✅ Results

- The best model achieved **RMSE < 48**, meeting the project's success criteria.

## 🛠 Technologies & Libraries

- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- statsmodels
- lightgbm
- catboost
- xgboost

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
