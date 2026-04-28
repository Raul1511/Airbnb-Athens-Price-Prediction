# Airbnb Price Prediction in Athens

## Overview
This project analyzes Airbnb listings in Athens and builds machine learning models to predict listing prices.

## Dataset
The dataset is not included in this repository.

To run the project:
1. Download 'listings.csv.gz' for Athens from Inside Airbnb:
     https://insideairbnb.com/get-the-data/
2. Create a folder named 'data'
3. Place the file here:
    'data/listings.csv.gz'

## Project steps
  - Data loading
  - Data cleaning
  - Exploratory Data Analysis
  - Feature engineering
  - Linear Regression model
  - Random Forest model
  - Feature importance analysis

## Results
  | Model | MAE | R² |
  |------|------|------|
  | Linear Regression | 40.7 | 0.36 |
  | Random Forest | 30.5 | 0.62 |

## Key Findings
  - Location is one of the strongest predictors of Airbnb prices.
  - Entire homes are generally more expensive than private/shared rooms.
  - Availability and property characteristics also influence pricing.
