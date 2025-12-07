# Laptop-Pricing-Data-Science-Project
Author: Saroj — Data Science & ML Enthusiast

This project focuses on predicting laptop prices using different hardware specifications such as processor type, RAM size, storage capacity, graphics support, display features, and operating system.
The main objective is to support online retailers in setting competitive and accurate prices so they can improve sales and profitability.

# Problem Statement
Laptop prices vary significantly depending on technical specifications.
Incorrect pricing can lead to lower profit margins or reduced customer purchases.

To solve this issue, I built a machine learning model that can estimate the price of a laptop based on its key features.

## Project Workflow

- Handled missing values and cleaned dataset
- Performed feature engineering (CPU Level, Screen Area, Resolution)
- Applied One-Hot Encoding for categorical features
- Standardized all numerical fields
- Trained a Random Forest Regressor model
- Evaluated using MAE, RMSE & R² Score

## Model Performance

The model delivered strong performance considering the wide variation in laptop prices:

- **MAE (Mean Absolute Error):** ₹13,269  
- **RMSE (Root Mean Squared Error):** ₹24,705  
- **R² Score:** 0.8276  

These results show that the model is able to capture pricing trends effectively and produces accurate predictions for most laptops.

# Insights from the Model
- RAM and processor generation strongly influence laptop price
- Storage type (SSD vs HDD) also impacts pricing
- Touchscreen and better screen resolution usually increase cost
- Certain brands offer higher-priced laptops due to market positioning

# Visual Outputs from the Model
- Actual vs Predicted Price comparison
- Feature importance chart
- Prediction error distribution
All model visualizations are included in the repository.

# Technologies and Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn
- Joblib (for model export)

# Future Work

- Add hyperparameter tuning for further improvement
- Deploy the model as a web application using Streamlit or Flask
- Expand dataset with newer laptop specs for better generalization

# About Me
I am a data science and machine learning enthusiast who loves solving real-world problems using data.
This project helped me strengthen my understanding of feature engineering, model evaluation, and end-to-end ML development.
