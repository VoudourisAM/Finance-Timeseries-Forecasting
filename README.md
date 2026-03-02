# 📈 Finance Time Series Forecasting (ML Pipeline)

This project implements an end-to-end Machine Learning pipeline for financial index forecasting using historical market data.

#

### 🔹 Project Structure

- Extract_Data.py → Downloads financial index data using yfinance
- Preprocessing.py → Data cleaning & handling missing values
- Feature_Engineering.py → Percentage returns & moving averages
- train_test_split.py → Train-test split (80/20, no shuffle)
- GridSearch.py → Hyperparameter tuning (Decision Tree & XGBoost)
- ML_Forecast.py → Model training, prediction & RMSE evaluation
- Visualization.py → Missing data visualization
- MAIN.ipynb → Full workflow execution notebook 

#

### 🔹 Features

✔ Financial index data extraction (S&P 500, NASDAQ, Euro Stoxx 50)

✔ Data cleaning & forward filling

✔ Feature engineering (returns, moving averages)

✔ Target shifting for forecasting

✔ Hyperparameter optimization with GridSearchCV

✔ Model evaluation (RMSE)

✔ Cyberpunk-style visualization

#

### 🔹 Models Used
- Linear Regression

- Decision Tree Regressor

- XGBoost Regressor

#

### 🔹 Technologies

- Python

- pandas

- scikit-learn

- xgboost

- yfinance

- matplotlib / seaborn

#

### 🔹 Workflow

- Data Extraction

- Preprocessing

- Feature Engineering

- Train/Test Split

- Model Training

- Evaluation

- Visualization

#

🎯 Goal

To build a structured ML pipeline for financial time series forecasting with proper validation and hyperparameter tuning.

#
