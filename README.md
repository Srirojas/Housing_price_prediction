# Housing Price Prediction

## Project Overview
This project aims to predict house prices based on various numerical and categorical features. By applying Regression Models, we analyze key factors that influence house pricing and determine the best-performing model for accurate price prediction.

## Objective
 - Understand the key factors that impact house prices.
 - Perform exploratory data analysis (EDA) to uncover patterns and relationships.
 - Compare multiple regression models to find the best predictive algorithm.

## Dataset
 - Shape: (545, 13) → 545 houses with 13 features
 - Features: Numerical Variables as area, bedrooms, bathrooms, stories, parking &
Categorical Variables as mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea, furnishingstatus
 - Target Variable: price
 - Missing Values: None

## Exploratory Data Analysis (EDA)
✔ Descriptive Statistics – Min, Max, Quartiles, Mean, Standard Deviation
✔ Boxplots & Correlation Analysis – Identify relationships between features & target
✔ Scatter Plots – Visualize trends
✔ Histograms & Distribution Plots – Explore feature distributions
✔ Feature Engineering – Encoding categorical variables, normalization

## Machine Learning Models Used
 - Linear Regression
 - Decision Tree Regressor
 - Random Forest Regressor
 - XGBoost Regressor

## Model Comparison
Evaluated each model using R² Score to determine accuracy.

## Technologies Used
- Python
- Pandas, NumPy – Data Handling
- Seaborn, Matplotlib – Data Visualization
- Scikit-learn, XGBoost – Machine Learning Models

## Inference:
- Linear Regression performed well with an accuracy of 67% being the best fit model.
- A comparative study of algorithms helps in selecting the best fit model.
