# Robust_Regression_Engine-ML


# House Price Prediction Using Machine Learning

## Project Overview

This project develops a machine learning system to predict house prices based on various property characteristics. The complete machine learning workflow includes data generation, preprocessing, exploratory data analysis, feature engineering, model development, hyperparameter tuning, cross-validation, model evaluation, and performance comparison.

Since a real-world dataset was not provided, a synthetic dataset containing 100,000 records was generated to simulate real estate data. Multiple regression algorithms were implemented and compared to identify the best-performing model for predicting house prices.

## Problem Statement

Accurately estimating house prices is a challenging task because property values depend on multiple factors such as location, area, number of bedrooms, property age, nearby facilities, and crime rate. This project aims to build an accurate regression model that can predict house prices using machine learning techniques.

## Objectives

- Predict house prices using machine learning regression algorithms.
- Perform complete exploratory data analysis.
- Clean and preprocess the dataset.
- Engineer useful features from raw data.
- Compare multiple regression models.
- Apply regularization techniques.
- Perform hyperparameter tuning.
- Evaluate models using multiple performance metrics.
- Select the best-performing model.

## Dataset Information

Dataset Type: Synthetic Dataset

Number of Records: 100,000

Target Variable:

- house_price_inr

Features:

- property_id
- sale_date
- area_sqft
- bedrooms
- bathrooms
- location_score
- property_age
- distance_city_km
- near_school
- near_metro
- crime_rate_index
- parking_spaces
- floor_number
- renovation_year
- house_price_inr

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Models

The following regression algorithms were implemented:

- Ridge Regression
- Lasso Regression
- Decision Tree Regression
- Random Forest Regression
- Support Vector Regression (Linear Kernel)
- Support Vector Regression (RBF Kernel)

## Data Preprocessing

The following preprocessing steps were performed:

- Data loading
- Data inspection
- Missing value checking
- Duplicate removal
- Data type conversion
- Date feature extraction
- Feature engineering
- Train-test split
- Feature scaling using StandardScaler

## Exploratory Data Analysis

EDA included:

- Dataset overview
- Summary statistics
- Missing value analysis
- Correlation analysis
- Histogram
- Box plot
- Count plot
- Scatter plot
- Pair plot
- Heatmap
- Distribution analysis

## Feature Engineering

Additional features were created from the original dataset:

- Sale Year
- Sale Month
- Sale Day

Date columns were transformed into numerical features for better model performance.

## Hyperparameter Tuning

GridSearchCV was used to optimize model parameters.

Models tuned:

- Ridge Regression
- Lasso Regression
- Decision Tree Regression
- Support Vector Regression

## Cross Validation

The following validation techniques were applied:

- K-Fold Cross Validation
- Stratified K-Fold Cross Validation
- Leave-One-Out Cross Validation
- Time Series Split

## Evaluation Metrics

Model performance was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Project Pipeline

```text
Problem Definition--> Data Collection --> Data Loading --> Data Understanding --> Data Cleaning --> Data Preprocessing --> Exploratory Data Analysis (EDA) --> Feature Engineering --> Feature Scaling --> Train-Test Split --> Model Building --> Ridge Regression --> Lasso Regression --> Decision Tree Regression --> Random Forest Regression --> Support Vector Regression (SVR) --> Hyperparameter Tuning --> Cross Validation --> Model Evaluation --> Model Comparison --> Best Model Selection --> House Price Prediction --> Project Conclusion
```

## Project Structure

```

#  Project Structure

```text
House_Price_Prediction/
│
├── data/
│   └── house_price_dataset.csv
│
├── notebooks/
│   └── House_Price_Prediction.ipynb
│
├── reports/
│   └── Final_Report.pdf
│
├── results/
│   └── Model_Comparison.csv
│
├── README.md
│
└── requirements.txt
```

---

# Installation

```bash
git clone https://github.com/your-username/House_Price_Prediction.git

cd House_Price_Prediction

pip install -r requirements.txt
```

---

#  Run the Project

1. Open **House_Price_Prediction.ipynb** in Google Colab or Jupyter Notebook.

2. Run all cells sequentially.

3. The notebook will perform:

- Data Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Model Training
- Hyperparameter Tuning
- Cross Validation
- Model Evaluation
- House Price Prediction

---

#  Results

The performance of all regression models was compared using:

- MAE
- MSE
- RMSE
- R² Score

The best-performing model was selected based on the highest R² Score and the lowest prediction error.

---

# Project Features

- 100,000 synthetic housing records
- Complete Machine Learning workflow
- Data preprocessing
- Feature engineering
- Exploratory Data Analysis
- Multiple regression algorithms
- Hyperparameter tuning
- Cross-validation
- Model comparison
- Feature importance analysis
- Performance visualization
- Final model selection

---

# Future Enhancements

- Use real-world housing datasets
- Deploy using Flask or FastAPI
- Build a Streamlit web application
- Deploy on cloud platforms
- Integrate GIS location features
- Add Deep Learning models
- Create Power BI dashboards

---

#  Learning Outcomes

This project demonstrates:

- Data Preprocessing
- Data Visualization
- Feature Engineering
- Regression Algorithms
- Regularization
- Hyperparameter Tuning
- Cross Validation
- Model Evaluation
- End-to-End Machine Learning Workflow

---

# Author

**Swarna Pathak**

Machine Learning Project


