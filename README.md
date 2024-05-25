# Predicting Delivery Time for Sendy

## Project Overview
This project aims to predict the delivery time from pickup to arrival for Sendy, a delivery service. Using a dataset containing information about delivery orders, we preprocess the data, engineer features, and build predictive models to estimate delivery times.

## Table of Contents
1. [Introduction](#introduction)
2. [Data](#data)
3. [Feature Engineering](#feature-engineering)
4. [Model Training](#model-training)
5. [Evaluation](#evaluation)
6. [Usage](#usage)
7. [Requirements](#requirements)
8. [Results](#results)
9. [Contributors](#contributors)

# Introduction
In this project, we develop a machine learning model to predict the time from pickup to arrival for delivery orders. The project involves data preprocessing, feature engineering, model training, and evaluation.

# Data
The data includes information about delivery orders, such as the order details, pickup and delivery locations, times, distances, and rider metrics. We also utilize additional rider metrics from a separate dataset.

# Feature Engineering
We perform several feature engineering steps to improve model performance:
- Handling missing values
- Scaling numerical features
- Encoding categorical variables
- Extracting new features from existing ones

# Model Training
We use several regression models to predict the delivery time, including:
- Linear Regression
- Lasso Regression
- Random Forest Regressor
- Gradient Boosting Regressor

We perform hyperparameter tuning using GridSearchCV to find the best parameters for the models.

# Evaluation
The models are evaluated using Mean Squared Error (MSE) and R-squared (R²) metrics. The best-performing model is selected based on the lowest MSE and highest R² score.

# Usage
To run the project, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone <repository_url>
   cd <repository_directory>
   
2. Install the dependencies:
    ```sh
    pip install -r requirements.txt
    
3. Run the Jupyter Notebook:
   Open the Jupyter Notebook and execute the cells to preprocess the data, train the models, and evaluate their performance.
4. Make Predictions:
   Use the trained model to make predictions onn new data.


# Requirements
The project requires the following libraries:

pandas
matplotlib
seaborn
numpy
scikit-learn
To install the dependencies, run:
 ```sh
pip install -r requirements.txt

#Results
The best model achieved a Mean Squared Error (MSE) of X and an R² score of Y. The predictions are saved in the submission.csv file, which contains the order IDs and the predicted delivery times.
