# Growthlink - Movie Rating Prediction

## Overview
This project builds a predictive model to estimate IMDb movie ratings based on various attributes such as genre, director, and actors. The dataset used is from IMDb Movies India.

## Features Implemented
1. **Data Loading & Exploration**
   - Load dataset and inspect structure
   - Identify missing values and data inconsistencies

2. **Data Preprocessing & Cleaning**
   - Convert data types (Year, Duration, Votes)
   - Handle missing values (imputation for numerical columns, categorical adjustments)
   - Normalize and encode categorical features (Genre, Director, Actors)
   - Remove duplicates and inconsistent data

3. **Feature Engineering**
   - Compute Director Success Rate (average rating of movies by the same director)
   - Compute Genre Average Rating (average rating of movies in the same genre)
   - One-hot encode categorical variables with infrequent category grouping

4. **Data Splitting & Model Training**
   - Split dataset into training and testing sets
   - Train a predictive model using **Random Forest Regressor**
   - Evaluate model performance using **MSE (Mean Squared Error) and R² Score**

## Installation
To run the project, install the required dependencies:
```
pip install -r requirements.txt
```

## Usage
Run the Jupyter Notebook:
```
jupyter notebook Growthlink.ipynb
```

## Expected Outcome
The model predicts IMDb movie ratings with reasonable accuracy.

## Evaluation Metrics
- **Mean Squared Error (MSE):** Measures prediction error
- **R² Score:** Indicates model performance

## Repository Structure
- `Growthlink.ipynb` – Jupyter Notebook containing all steps
- `README.md` – Project documentation
  
## Future Improvements
- Experiment with different models (XGBoost, Linear Regression, etc.)
- Perform hyperparameter tuning for better accuracy
- Add more advanced feature engineering techniques

