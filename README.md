# Car_Price_Analyzer
An ML model that analyzes car prices based on its age and year
Here’s a simple **README** for your Car Price Prediction project:

# Car Price Prediction:

This project predicts the **selling price of used cars** based on features like present price, kilometers driven, fuel type, selling type, transmission, ownership, and car age.

## Dataset
 Source: `cardata.csv.csv`


## Features

* `Present_Price` – Current ex-showroom price (in lakhs)
* `Driven_kms` – Total kilometers driven
* `Fuel_Type` – Petrol/Diesel/CNG
* `Selling_type` – Dealer or Individual
* `Transmission` – Manual or Automatic
* `Owner` – Number of previous owners
* `Car_Age` – Years since manufacture

## Target

* `Selling_Price` – Price at which the car is being sold (in lakhs)

## Model

## Algorithm: Random Forest Regressor
## Metrics: R² Score, RMSE

## Steps

1. Load and preprocess dataset
2. Encode categorical variables
3. Create `Car_Age` from `Year`
4. Train-test split (80/20)
5. Train Random Forest model
6. Evaluate performance
7. Predict on new data

