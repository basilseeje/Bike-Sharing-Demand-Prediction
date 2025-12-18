
# Bike Sharing Demand Prediction 🚲

## Project Overview
This project implements an end-to-end machine learning solution to predict hourly bike rental demand using the Bike Sharing Dataset. The goal is to analyze historical rental patterns and build a predictive model that can estimate the number of bikes rented per hour based on environmental and temporal features.

## Dataset
- **Source:** UCI Machine Learning Repository  
- **Dataset Used:** hour.csv  
- **Number of Rows:** 17,379  
- **Target Variable:** `cnt` (total number of bike rentals per hour)  
- **Problem Type:** Supervised Learning – Regression  

## Project Workflow
1. Data loading and understanding  
2. Exploratory Data Analysis (EDA)  
3. Feature selection and preprocessing  
4. Model building using:
   - Linear Regression
   - Random Forest Regression
5. Model evaluation using:
   - Mean Squared Error (MSE)
   - R² Score
6. Model saving for deployment  
7. Deployment using Flask web application  

## Model Performance
- **Linear Regression:** R² ≈ 0.38  
- **Random Forest Regression:** R² ≈ 0.94  

The Random Forest model significantly outperformed Linear Regression, indicating its ability to capture non-linear relationships in the data.

## Model Deployment
The trained Random Forest model was saved using `pickle`/`joblib` and deployed locally as a Flask web application. A simple HTML interface allows users to input feature values such as hour, temperature, humidity, and windspeed to receive real-time predictions of bike rental demand.

### Model File Note
Due to GitHub file size limitations, the trained model file (`model.pkl`) is not uploaded to this repository.  
However, the Jupyter Notebook contains the complete code for training and saving the model, and the Flask application loads the locally saved model for deployment.

## How to Run the Application
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

The model can accurately forecast hourly bike rental demand.

## 👤 Author
- BASIL SEEJE
- Mini Project 
