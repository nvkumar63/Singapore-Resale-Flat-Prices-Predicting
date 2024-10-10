
# Singapore Resale Flat Prices Predicting

Project Overview
This project aims to predict the resale prices of HDB flats in Singapore using historical data and machine learning techniques. We will use features such as flat type, location, floor area, age, and proximity to amenities to build a predictive model that estimates the future price of resale flats.

Dataset
The dataset used in this project is sourced from Data.gov.sg and contains historical transaction records of resale flat prices.

Features:
Town: The town where the flat is located (e.g., Jurong East, Bukit Batok).
Flat Type: The type of flat (3-room, 4-room, 5-room, etc.).
Floor Area: The area of the flat in square meters.
Remaining Lease: The number of years left on the 99-year lease.
Storey Range: The range of floors (e.g., 1-3, 4-6) where the flat is located.
Flat Model: The model of the flat (e.g., New Generation, Improved).
Resale Price: The price at which the flat was sold.
Data Source:
Data.gov.sg - HDB Resale Prices
Prerequisites


## Documentation

[Documentation](https://linktodocumentation)

Usage
Step 1: Data Preprocessing
The dataset is first cleaned and preprocessed. Missing values are handled, categorical variables are encoded, and the data is split into training and test sets.

Step 2: Model Building
We use multiple machine learning models such as:

Linear Regression
Random Forest
Gradient Boosting (XGBoost)
Step 3: Model Evaluation
We evaluate the models using metrics such as:

Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R-squared (R²)
Step 4: Prediction
Once the model is trained and evaluated, it can be used to predict resale flat prices for new data inputs.https://github.com/nvkumar63/Singapore-Resale-Flat-Prices-Predicting


## Installation
import pandas as pd
import numpy as np
import datetime
from scipy.stats import skew
import seaborn as sns
import matplotlib.pyplot as plt
    