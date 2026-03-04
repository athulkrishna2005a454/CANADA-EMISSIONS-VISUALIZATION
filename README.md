# CANADA-EMISSIONS-VISUALIZATION
Project Overview
This project builds a machine learning model to predict vehicle CO2 emissions using Linear Regression. The goal is to analyze how engine and fuel-related factors influence emission levels and evaluate the predictive performance of a regression model.

The project follows a complete machine learning workflow from data preprocessing to model evaluation.

Dataset
Dataset Used: CO2 Emissions Canada Dataset

The dataset contains vehicle specifications and fuel consumption data.

Selected Features (Input Variables)
Engine Size (L)
Cylinders
Fuel Consumption Comb (L/100 km)
Target Variable
CO2 Emissions (g/km)
Project Workflow
Data loading and inspection
Handling missing values
Feature selection
Feature scaling using StandardScaler
Train-test split (80-20)
Model training using Linear Regression
Model evaluation using:
R² Score
Mean Absolute Error (MAE)
Visualization of Actual vs Predicted values
Model Performance
The model performance is evaluated using:

R² Score – Measures how well the model explains variance in CO2 emissions.
Mean Absolute Error (MAE) – Measures average prediction error.
Technologies Used
Python
Pandas
Matplotlib
Scikit-learn
Key Learning Outcomes
Understanding regression modeling
Preventing data leakage
Feature scaling and preprocessing
Evaluating model performance
Interpreting regression coefficients
Conclusion
The Linear Regression model demonstrates a strong relationship between fuel consumption and CO2 emissions. The project highlights how real-world environmental data can be analyzed and modeled using machine learning techniques.
