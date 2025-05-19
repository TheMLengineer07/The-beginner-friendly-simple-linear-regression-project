# Simple Linear Regression for Prediction

* This project implements Simple Linear Regression to predict the dependent variable (y) based on an independent variable (x). The goal is to fit a linear 
  model that accurately captures the relationship between x and y.

# Data Overview

# Data Source:
* https://github.com/TheMLengineer07/The-beginner-friendly-simple-linear-regression-project/blob/main/test.csv
* https://github.com/TheMLengineer07/The-beginner-friendly-simple-linear-regression-project/blob/main/train.csv


#  Data Processing
*  Checked for missing values (isna().sum())
* Removed NaN values using dropna()
* Split dataset into training (75%) and testing (25%) sets

# Regression Model
* Implemented Simple Linear Regression using Scikit-learn:
* Training Data: X_train, Y_train
* Testing Data: X_test, Y_test
* Model Fitting: model.fit(X_train, Y_train)
* Predictions: model.predict(X_test)

# Model Evaluation
* The model was evaluated using: ✅ R-squared (R²): 0.9901 → Indicates excellent predictive accuracy ✅ Mean Squared Error (MSE): 7.8234 → Measures the 
  average squared difference between actual and predicted values

# Visualization:
* Scatter Plot of Training Data (Red) with Fitted Regression Line (Blue)
* Clear linear relationship confirmed between x and y

# Key Findings
* The high R² score suggests the model fits the data well.
* Minimal missing values handled via preprocessing.
* Linear regression proves effective for this dataset.

# Conclusion & Next Steps
✅ Conclusion: The Simple Linear Regression model accurately predicts y values using x, achieving a high R² score. 
🚀 Next Steps: Consider testing Polynomial Regression or Ridge Regression for handling nonlinear relationships or improving robustness.
