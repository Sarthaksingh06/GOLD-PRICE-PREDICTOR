# GOLD-PRICE-PREDICTOR(ML TECHNOLOGY)
🔍 Overview

An end-to-end machine learning project that predicts future gold prices using historical time-series data. The system processes 730+ daily records, performs feature engineering with 10+ technical indicators, trains multiple ML models, and selects the best one based on evaluation metrics.

It also includes data visualizations and an interactive CLI-based Q&A module for price trends, forecasts, and investment insights

🚀 Features

Time-series preprocessing and cleaning

Technical indicators: MA (5/20/50), RSI, MACD, Bollinger Bands, Volatility

Model comparison: Linear Regression vs Random Forest

Evaluation using RMSE, MAE, and R²

Interactive question-answering interface

Automated sample data generation

🛠 Tech Stack

Language: Python

Libraries: Pandas, NumPy, Scikit-learn

Visualization: Matplotlib, Seaborn

📂 Project Structure
gold-price-predictor/
│
├── create_sample_data.py   # Generates sample gold price dataset
├── gold_predictor.py       # Main ML pipeline & interactive CLI
└── gold_data.csv           # Auto-generated dataset

▶️ How to Run
# 1. Create virtual environment
python -m venv venv
venv\Scripts\activate   # Windows
# source venv/bin/activate  # Mac/Linux

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

# 3. (Optional) Generate data
python create_sample_data.py

# 4. Run the project
python gold_predictor.py

📈 Model Evaluation

Metrics Used: RMSE, MAE, R²

Best Model: Random Forest Regressor (lower prediction error than baseline)

