# Car Price Prediction

This repository contains the implementation of **Car Price Prediction**, completed as part of Task 2 for the CodeAlpha internship.

---

## Project Overview
The objective of this project is to predict the selling price of cars based on their attributes, such as present price, fuel type, transmission type, and more. We utilized regression models to train and evaluate accurate car price prediction.

---

## Workflow
1. **Data Preprocessing**:
   - Encoded categorical features (`Fuel_Type`, `Selling_Type`, `Transmission`).
   - Derived the `Car_Age` feature from the car's manufacturing year.
   - Removed outliers and scaled numerical features for better model performance.
2. **Exploratory Data Analysis**:
   - Visualized key relationships between features and the target variable (`Selling_Price`).
   - Identified significant predictors like `Present_Price`.
3. **Model Training and Evaluation**:
   - Trained multiple regression models:
     - Linear Regression
     - Random Forest Regressor
     - Gradient Boosting Regressor
     - XGBoost Regressor
     - CatBoost Regressor
   - Selected **Gradient Boosting Regressor** as the final model:
     - **R² Score**: 0.96
     - **MAE**: 0.39
     - **RMSE**: 0.60
4. **Final Model and Deployment**:
   - Saved the final model as `final_gradient_boosting_model.pkl`.
   - Demonstrated its usage for predicting car prices on new data.

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/CodeAlpha_Task2_CarPricePrediction.git
2. Open the Jupyter Notebook (Car_Price_Prediction.ipynb) and run the cells sequentially.
3. Use the saved model (final_gradient_boosting_model.pkl) to make predictions on new car data.

**Technologies Used :**
 - Python
 - Scikit-learn
 - Matplotlib, Seaborn
 - Gradient Boosting Regressor

**About CodeAlpha**
This project is part of Task 2 for the CodeAlpha internship program.
