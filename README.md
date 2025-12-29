## Electricity Bill Prediction System
This project predicts the monthly electricity bill based on energy consumption, temperature, and seasonal patterns using machine learning.
## Problem Statement
Electricity providers and consumers need an efficient way to estimate monthly electricity costs.
Estimation is based on usage trends and environmental conditions.
This project automates electricity bill prediction using machine learning models.
## Dataset
The dataset is created directly inside the Python code.
It includes the following features:
Month
Units Used
Temperature
Electricity Bill
Additional derived features:
Average Units (last 3 months)
Season indicator (Summer / Non-summer)
## Algorithm Used
Linear Regression
Random Forest Regressor
The model with the lowest Mean Absolute Error (MAE) is selected automatically.
## Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Joblib
## How the Project Works
Data is loaded into a Pandas DataFrame.
Feature engineering is performed.
Data is split into training and testing sets.
Two regression models are trained.
Model performance is evaluated using MAE.
The best model is selected and saved.
User inputs values.
The model predicts the electricity bill.
High usage months are detected.
Consumption trend is visualized.
## How to Run
Install required libraries:
pip install pandas numpy matplotlib scikit-learn joblib

Run the Python file:
python electricity_bill_prediction.py

Enter the required values when prompted.
## Conclusion
This project demonstrates a complete end-to-end machine learning workflow.
It effectively predicts electricity bills and analyzes energy consumption patterns.
The system is suitable for college mini-projects and ML demonstrations.
