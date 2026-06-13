# House Price Prediction

## Project Overview

This project aims to predict house prices using Machine Learning techniques. The model analyzes various house features such as area, number of bedrooms, bathrooms, stories, parking facilities, and furnishing status to estimate the price of a house.

The project demonstrates the complete machine learning workflow including data preprocessing, exploratory data analysis, model training, prediction, and performance evaluation.

---

## Objective

The main objectives of this project are:

* Analyze housing market data.
* Identify factors affecting house prices.
* Build a predictive machine learning model.
* Evaluate prediction performance.
* Visualize important housing insights.

---

## Dataset

Dataset: Housing Prices Dataset

Features:

* Area
* Bedrooms
* Bathrooms
* Stories
* Main Road Access
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Parking
* Preferred Area
* Furnishing Status

Target Variable:

* Price

Dataset Size:

* Total Records: 545
* Total Features: 13

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Power BI
* GitHub

---

## Exploratory Data Analysis

The following visualizations were created:

### 1. House Price Distribution

Analyzes the distribution of house prices.

### 2. Area vs Price

Shows the relationship between house area and selling price.

### 3. Bedrooms vs Price

Compares house prices based on the number of bedrooms.

### 4. Correlation Heatmap

Visualizes relationships among all features.

### 5. Actual vs Predicted House Prices

Compares actual house prices with model predictions.

### 6. Residual Distribution

Shows the distribution of prediction errors.

---

## Machine Learning Model

Algorithm Used:

* Linear Regression

Steps Performed:

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Train-Test Split
6. Model Training
7. Price Prediction
8. Model Evaluation

---

## Model Performance

### Mean Absolute Error (MAE)

970,043

### Mean Squared Error (MSE)

1,754,318,687,330

### R² Score

0.653

### Interpretation

The model explains approximately 65.3% of the variation in house prices and provides reasonably accurate predictions for housing market analysis.

---

## Project Structure

```text
House-Price-Prediction/
│
├── data/
│   └── Housing.csv
│
├── notebook/
│   └── house_price_prediction.ipynb
│
├── images/
│   ├── price_distribution.png
│   ├── area_vs_price.png
│   ├── bedrooms_vs_price.png
│   ├── correlation_heatmap.png
│   ├── actual_vs_predicted.png
│   └── residual_distribution.png
│
├── model/
│   └── house_price_model.pkl
│
├── house_price_predictions.csv
│
└── README.md
```

---

## Results

* Successfully built a house price prediction model.
* Performed exploratory data analysis and visualization.
* Predicted house prices using Linear Regression.
* Evaluated model performance using MAE, MSE, and R² Score.
* Generated prediction results and saved the trained model.

---

## Future Improvements

* Random Forest Regression
* XGBoost Regression
* Hyperparameter Tuning
* Advanced Feature Engineering
* Real-Time House Price Prediction Web Application
* Interactive Power BI Dashboard

---

## Dataset Source

Housing Prices Dataset available on Kaggle.

---

## Author

Vishal Kumar


