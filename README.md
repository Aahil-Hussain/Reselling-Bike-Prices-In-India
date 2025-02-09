# Reselling-Bike-Prices-In-India

# Overview
This project involves predicting the prices of reselling used bikes using machine learning models based on various features of the bike, such as model year, mileage, and kilometers driven.
The goal of this project is to develop a model that accurately predicts the price of a used bike based on several factors. This can assist both buyers and sellers in determining the fair market value of a bike based on its condition and specifications.

## Dataset
The dataset contains the following columns:

- model_name: The name of the bike model.
- model_year: The year the bike was manufactured.
- kms_driven: Total kilometers driven by the bike.
- owner: The number of previous owners.
- location: The location of the bike.
- mileage: Fuel efficiency of the bike in kilometers per liter.
- power: The engine power of the bike in brake horsepower (BHP).
- price: The resale price of the bike (target variable).

## Libraries: 
Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Chi2, etc

## Objective
The aim is to predict the resale price of used bikes based on the features provided in the dataset. This involves:

- Exploratory Data Analysis (EDA): Analyzing and preprocessing the dataset.
- Model Building: Training regression models to predict used bike prices.
- Model Evaluation: Evaluating the models using metrics such as Root Mean Squared Error (RMSE).

# Results:
The Random Forest model performed significantly better than the Decision Tree model, with a lower RMSE indicating a more accurate prediction
