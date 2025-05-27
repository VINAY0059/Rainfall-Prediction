# Rainfall-Prediction
Project : Build a model to predict whether it will rain tomorrow using classification algorithms and weather data.



This project focuses on predicting whether it will rain tomorrow based on historical weather data from various Australian weather stations. The goal is to build a machine learning model that can classify days into two categories: “Rain” or “No Rain” for the next day.

🔍 Problem Statement:
Can we use today's weather conditions (like humidity, temperature, wind speed, etc.) to predict whether it will rain tomorrow?

🧠 Approach:
Data Preprocessing:

Loaded the weatherAUS.csv dataset.

Removed unnecessary or incomplete columns (e.g., Evaporation, Sunshine).

Handled missing data with mean imputation.

Encoded categorical variables using LabelEncoder.

Model Training:

Split the data into training and testing sets.

Trained a Random Forest Classifier, a powerful ensemble learning algorithm.

Evaluation:

Checked the model’s performance using accuracy and classification report.

Visualized the results using a confusion matrix.

Displayed feature importance to understand which weather factors influence predictions the most.

📈 Result:
The model achieved high accuracy (~85%), showing good capability in predicting rainfall.

Important features included humidity, rainfall today, and temperature.

✅ Application:
Such a model can help in agriculture, event planning, and disaster preparedness by giving early warnings about rainfall.
