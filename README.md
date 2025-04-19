# 🚲 Bike Sharing Demand Prediction – Mini Project 2

This project explores the use of various machine learning algorithms to predict the number of bikes rented in a given hour based on historical data. The dataset includes features like weather, time, and seasonality. This is part of a machine learning mini-project series.

## 📁 Dataset

The dataset used is `train.csv`, which contains bike sharing data including:
- Timestamped demand
- Weather and seasonal data
- Holiday/workday flags

## 🧪 Project Highlights

- Outlier detection and data preprocessing
- Exploratory Data Analysis (EDA) with `seaborn` and `plotly`
- Training and comparing multiple ML models:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - XGBoost
  - CatBoost

## 🧠 Notable Insight

> 💡 **CatBoost** was found to outperform the other models in terms of prediction accuracy.

## 📊 Evaluation Metrics

The models are evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R-squared (R²)

## 📦 Dependencies

Make sure you have the following libraries installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn plotly xgboost catboost

🚀 Getting Started

    1. Clone the repo

    2. Add the train.csv file in the same directory

    3. Run the notebook: Mini Project 2.ipynb

📸 Visualizations

The notebook includes insightful visualizations for:

    1. Demand trends

    2. Outlier distribution

    3. Feature relationships

Author

Made with ❤️ by [Hossein siadati]
