House Price Prediction App

Overview

This project is a Machine Learning web application that predicts house prices based on various property features.
The model is trained using housing data and deployed as an interactive web application.
Users can enter house details such as overall quality, living area, number of bathrooms, and other property features. The app then predicts the estimated house price using a trained machine learning model.

Features

Predict house prices using a trained ML model
Interactive user interface
Easy input fields for property features
Real-time price prediction

Technologies Used

Python
Streamlit
Pandas
Scikit-learn
XGBoost
Joblib

Dataset

The dataset contains multiple housing features such as:
OverallQual – overall material and finish quality
GrLivArea – ground living area in square feet
GarageArea – garage size in square feet
YearBuilt – construction year
LotArea – property land size
CentralAir – whether the house has central air conditioning
These features are used to train the machine learning model.

Model

The model used for prediction is XGBoost Regressor, which learns patterns from historical housing data to estimate house prices.
