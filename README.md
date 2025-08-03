# ✈️ Air Ticket Price Prediction & Analysis

## 📌 Project Overview

The **Air Ticket Price Prediction** project is a machine learning-based system designed to analyze and predict flight ticket prices using real-world data. By leveraging historical flight data and relevant variables such as airline, source, destination, number of stops, class, duration, and days left to departure, this project helps uncover pricing patterns and make accurate fare predictions.

## 🎯 Objectives

- Predict airfare prices based on multiple input features.
- Help **travelers** identify the best time to book tickets at optimal prices.
- Support **airlines** in optimizing pricing strategies to increase revenue.
- Analyze key factors influencing ticket prices in the Indian airline industry.

## 🗂️ Dataset

- Includes details like airline, source, destination, duration, total stops, class, days left before departure, and ticket price.
- Cleaned and preprocessed for model training using label encoding and feature scaling.

## 🧪 Exploratory Data Analysis (EDA)

- Prices vary significantly across airlines and classes.
- Non-stop flights tend to be more expensive.
- Ticket prices increase as the departure date approaches.

## 🧠 Models Used

- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor** (Best performer)

## 📈 Model Performance

| Model              | R² Score | RMSE         |
|-------------------|----------|--------------|
| Linear Regression | 0.9045   | 7014.31      |
| Decision Tree     | 0.9757   | 3540.01      |
| Random Forest     | 0.9849   | **2786.50**  |

✅ **Random Forest** was selected as the final model due to its superior accuracy and lower error.

