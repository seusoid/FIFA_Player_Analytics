⚽ FIFA Player Analytics & Market Value Prediction
📌 Project Overview

This project analyzes FIFA player data from FIFA 15 to FIFA 21 to extract meaningful football insights and build machine learning models that predict a player’s market value based on performance, physical, and positional attributes.

The project combines exploratory data analysis, feature engineering, and machine learning to simulate how football clubs can use data-driven approaches to identify undervalued talent.

📊 Dataset

Source: Kaggle – FIFA Complete Player Dataset

Seasons: FIFA 15 to FIFA 21

Records: ~17,000+ players per edition

Features:

Player demographics (age, height, nationality)

Performance stats (pace, shooting, passing, etc.)

Financial data (value, wages, release clause)

Positional ratings

🎯 Objectives

Analyze how player attributes affect overall rating and market value

Identify trends in player development across age and positions

Train ML models to predict player market value

Detect undervalued players using prediction errors

🔍 Key Insights (Example)

Player market value increases non-linearly with overall rating

Attackers are generally overvalued compared to defenders

Players peak between ages 26–29

Certain leagues pay a premium for similar player quality

🤖 Machine Learning Approach

Target Variable: value_eur (log-transformed)

Models Used:

Linear Regression (baseline)

Random Forest Regressor

Gradient Boosting / XGBoost

Evaluation Metrics:

RMSE

MAE

R² Score

⭐ Business Impact

Helps clubs identify undervalued players

Assists scouts in shortlisting talent

Demonstrates how analytics can reduce transfer risk

🚀 Future Improvements

Time-series modeling for career progression

Position-specific value prediction models

Interactive dashboard for scouting teams

🛠️ Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn