
# 🚲 Bike Sharing Demand Prediction – Mini Project

This project analyzes the Bike Sharing Dataset (UCI Machine Learning Repository) and builds machine learning models to predict hourly bike rental demand.

## 📌 Project Objectives
- Perform Exploratory Data Analysis (EDA)
- Understand factors influencing bike rentals
- Build Linear Regression and Random Forest models
- Evaluate model performance
- Interpret feature importance
- Predict bike rental count (`cnt`)

## 📂 Dataset Used
- **hour.csv** from UCI Bike Sharing Dataset  
- Contains 17,379 rows and 17 columns

## 🔍 EDA Performed
- Histogram of bike rentals
- Rentals by hour of day
- Correlation heatmap
- Trend and seasonal patterns

## ⚙️ Preprocessing
- Removed unnecessary columns: `instant`, `dteday`, `casual`, `registered`
- Defined features (X) and target variable (`cnt`)
- Train-test split (80–20)

## 🤖 Models Built
### 1. Linear Regression (baseline)
- R² Score: ~0.38  
- MSE: High  
- Limited performance due to non-linearity

### 2. Random Forest Regression (improved model)
- R² Score: **0.94**
- MSE: **Very low**
- Accurate predictions

## 📈 Key Visualizations
- Feature importance plot  
- Actual vs Predicted graph  
- Hourly rental trend  

## 📝 Conclusion
Random Forest performed extremely well, capturing non-linear patterns and achieving an R² of 0.94.  
Hour of the day, temperature, and humidity were the most important features.  
The model can accurately forecast hourly bike rental demand.

## 👤 Author
- BASIL SEEJE
- Mini Project 
