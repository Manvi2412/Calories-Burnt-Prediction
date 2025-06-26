# Calories Burnt Prediction using Machine Learning

This project predicts the number of calories burnt based on exercise and physiological data using regression models. It includes data preprocessing, feature engineering, model training, evaluation, and deployment using a Streamlit web app.

## Problem Statement

Given a dataset containing features like age, gender, height, weight, exercise duration, heart rate, and body temperature, the goal is to build a regression model that can predict the number of calories burnt during exercise.

---

## Features

- Exploratory Data Analysis (EDA)
- Feature Engineering (BMI, Age Groups)
- Model Training:
  - Linear Regression
  - Random Forest Regressor
  - XGBoost Regressor
  - Gradient Boosting Regressor
- Model Evaluation using MAE, RMSE, R² Score
- Feature Importance & Explainability using SHAP
- Interactive Web App using Streamlit
- Deployed on Streamlit Cloud

---

## Dataset

- `calories.csv`: Contains `User_ID` and `Calories`
- `exercise.csv`: Contains `User_ID` and features like Age, Gender, Height, Weight, Duration, Heart Rate, Body Temp

---

## How to Run the Project

### 1. Clone the Repository
git clone https://github.com/your-username/calories-burnt-prediction.git
cd calories-burnt-prediction

Install Dependencies
pip install -r requirements.txt

Run the App
streamlit run app.py



### Files Overview
app.py: Streamlit app for user interaction
calorie_model.pkl: Trained XGBoost model
calories.csv, exercise.csv: Input datasets
requirements.txt: Project dependencies
notebook.ipynb: Development notebook (optional)
README.md: Project documentation


### Future Improvements
Deploy with Docker or on a cloud platform
Add user authentication to app
Enable data logging and visualization of trends

