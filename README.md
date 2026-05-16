# Tata Motors Stock Price Prediction

This project is a Machine Learning and Time Series Analysis application that predicts Tata Motors stock prices using historical stock market data. The model analyzes previous stock trends and forecasts future stock prices using regression techniques.

---

## Project Overview

The objective of this project is to build a stock price prediction system using historical Tata Motors stock market data from NSE (National Stock Exchange). The project includes data preprocessing, visualization, model training, prediction, and saving the trained model.

---

## Features

- Historical stock data analysis
- Data preprocessing and cleaning
- Stock trend visualization
- Feature scaling using pipeline
- Machine Learning model training
- Stock price prediction
- Model saving using Joblib
- Performance evaluation using RMSE and R² Score

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## Dataset Information

Dataset used:

```bash id="wgo9m4"
TATAMOTORS_NSE_1995-2025.csv

## Project Structure
├── README.md
├── TATAMOTORS_NSE_1995-2025.csv
├── Tata_Motors_Stock_Prediction.ipynb
├── model.pkl
├── pipeline.pkl
└── output.csv

## Machine Learning Workflow
1. Import Libraries

Libraries used for:

Data analysis
Visualization
Model training
Performance evaluation

2. Load Dataset

The stock dataset is loaded using Pandas.

df = pd.read_csv("TATAMOTORS_NSE_1995-2025.csv")
Data Preprocessing

The preprocessing pipeline includes:

Handling missing values
Feature scaling using StandardScaler
Data transformation using Scikit-learn Pipeline
Model Training

The project uses:

LinearRegression()

for stock price prediction.

The dataset is divided into:

Training data
Testing data

using:

train_test_split()
Model Evaluation

The model performance is evaluated using:

Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
Visualization

Matplotlib is used to visualize:

Stock price trends
Actual vs Predicted prices
Historical market movement
