# Car Price Prediction Model

## Problem Statement
The goal of this project is to build a **Car Price Prediction Model** that predicts the price of a car based on various features such as car name, year of manufacture, mileage, fuel type, transmission, and more. This model helps potential buyers or sellers estimate the price of a car, assisting in making informed decisions when purchasing or selling vehicles.

## About the Dataset
The dataset used for this project is a **Car Price Prediction Dataset**, which contains information about various cars, including their name, year of manufacture, selling price, present price, mileage, and other relevant features. The data helps in predicting the car’s price by evaluating how these features impact the value of a car.

### Dataset Information:
- **Source**: Kaggle (Car Price Prediction Dataset)
- **Rows**: 1000+
- **Columns**: 9

### Features:
The dataset consists of the following columns:

- **Car_Name**: The name of the car (categorical)
- **Year**: The year the car was manufactured (numeric)
- **Selling_Price**: The actual price at which the car is being sold (numeric, target variable)
- **Present_Price**: The current market price of the car (numeric)
- **Driven_kms**: The distance driven by the car in kilometers (numeric)
- **Fuel_Type**: The type of fuel the car uses (categorical: 'Petrol', 'Diesel', etc.)
- **Selling_type**: The selling type of the car (categorical: 'Individual', 'Dealer')
- **Transmission**: The type of transmission (categorical: 'Manual', 'Automatic')
- **Owner**: The number of previous owners (numeric)

## Why This Dataset?
This dataset is suitable for building a car price prediction model because it includes key features like the car's name, manufacturing year, mileage, fuel type, and others, which influence the price of a car. The target variable (**Selling_Price**) is continuous, making it ideal for regression models.

### Benefits of this dataset:
- It contains various features that affect car pricing, making it useful for building an accurate prediction model.
- The dataset is large enough to model and test the performance of the prediction algorithm.
- It is a widely used dataset for regression tasks in machine learning tutorials, making it a great starting point for predictive models.

## Model
The model used for this project is a **Linear Regression** model, which is commonly used for predicting continuous variables like car prices based on other numerical and categorical features.

### Steps Taken:

1. **Data Preprocessing**:
    - Handled missing values and encoded categorical variables (such as fuel type, transmission, etc.).
    - Scaled numerical features (such as selling price, present price, and driven kilometers) to ensure all features are on a similar scale for better model performance.

2. **Model Training**:
    - Trained a Linear Regression model on the preprocessed dataset using cross-validation.

3. **Model Evaluation**:
    - Evaluated the model’s performance using metrics like **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R-squared**.

4. **Model Saving**:
    - The trained model was saved as a pickle file (`car_model.pkl`) for future use, such as making price predictions on new car data.

## About
A machine learning project that predicts the price of a car based on various features like car name, year, fuel type, transmission, and mileage. The model uses **Linear Regression** to estimate the car’s price and evaluates its performance using regression metrics.

## Topics
- python
- machine-learning
- regression

## Resources
- Kaggle (Car Price Prediction Dataset)
- Scikit-learn (Linear Regression)

## Languages
- **Jupyter Notebook**: 90%
- **Python**: 10%
