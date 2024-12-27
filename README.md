# Car Price Predictions

## Project Overview

This project predicts the prices of cars based on various features using machine learning models. The dataset includes specifications about cars such as their engine type, dimensions, fuel type, and more. The objective is to build regression models to accurately predict car prices and evaluate their performance using various metrics.

---

## Dataset

The dataset contains the following columns:

- `car_ID`: Unique identifier for each car.
- `symboling`: Insurance risk rating (-3 to +3).
- `CarName`: The name of the car.
- `fueltype`: Type of fuel used (e.g., petrol, diesel).
- `aspiration`: Type of aspiration (e.g., turbo, standard).
- `doornumber`: Number of doors.
- `carbody`: Type of car body (e.g., sedan, hatchback).
- `drivewheel`: Drive wheel configuration (e.g., FWD, RWD).
- `enginelocation`: Location of the engine (e.g., front, rear).
- `wheelbase`: Distance between the front and rear axles.
- `carlength`: Length of the car.
- `carwidth`: Width of the car.
- `carheight`: Height of the car.
- `curbweight`: Weight of the car without passengers or cargo.
- `enginetype`: Type of engine (e.g., OHV, DOHC).
- `cylindernumber`: Number of cylinders in the engine.
- `enginesize`: Engine displacement.
- `fuelsystem`: Type of fuel system (e.g., MPFI, SPFI).
- `boreratio`: Ratio of the bore diameter to the stroke length.
- `stroke`: Stroke length of the engine.
- `compressionratio`: Compression ratio of the engine.
- `horsepower`: Horsepower of the car.
- `peakrpm`: Engine revolutions per minute (RPM) at peak power.
- `citympg`: City fuel efficiency (miles per gallon).
- `highwaympg`: Highway fuel efficiency (miles per gallon).
- `price`: **Target variable**, the price of the car.

---

## Models Used

The following regression models were implemented to predict car prices:

- **DecisionTreeRegressor**: A tree-based model that splits the data into decision nodes.
- **RandomForestRegressor**: An ensemble learning method that combines multiple decision trees to improve predictions.

---

## Model Evaluation Metrics

The models were evaluated using the following metrics:

1. **RMSE (Root Mean Squared Error)**: Measures the average magnitude of the errors, penalizing larger errors more heavily.
2. **RMAE (Root Mean Absolute Error)**: Similar to RMSE but less sensitive to outliers.
3. **MSE (Mean Squared Error)**: The average squared difference between predicted and actual values.
4. **MAE (Mean Absolute Error)**: The average absolute difference between predicted and actual values.
5. **R² (R-squared)**: The proportion of variance in the target variable that the model explains.
