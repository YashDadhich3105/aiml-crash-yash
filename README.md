# California Housing Price Prediction using Linear Regression

## Project Overview

This project was completed as part of an AI/ML Internship Program. The objective is to build and evaluate Linear Regression models for predicting California housing prices using the California Housing Dataset. The project focuses on model training, performance evaluation, feature comparison, train-test split analysis, and metric verification.

## Objectives

* Build a baseline Linear Regression model.
* Compare one-feature and multi-feature Linear Regression models.
* Analyze the impact of different train-test splits.
* Verify regression metrics manually and compare them with Scikit-Learn outputs.
* Study the effect of large prediction errors on evaluation metrics.

## Dataset

The project uses the California Housing Dataset available through Scikit-Learn.

Features include:

* MedInc (Median Income)
* HouseAge
* AveRooms
* AveBedrms
* Population
* AveOccup
* Latitude
* Longitude

Target Variable:

* median_house_value

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Google Colab / Jupyter Notebook

## Tasks Performed

### Task 1: Baseline Linear Regression Model

* Loaded and explored the dataset.
* Selected target and feature variables.
* Split data into training and testing sets.
* Trained a Linear Regression model.
* Generated predictions.
* Evaluated model performance using MSE, RMSE, MAE, and R² Score.
* Visualized Actual vs Predicted values.

### Task 2: One-Feature vs Multi-Feature Model

* Built Model A using a single feature.
* Built Model B using multiple features.
* Compared performance metrics.
* Selected the better-performing model based on test results.

### Task 3: Different Train-Test Splits

* Evaluated model performance using:

  * 80/20 split
  * 70/30 split
  * 60/40 split
* Compared training and testing metrics.
* Analyzed model stability across different splits.

### Task 4: Metric Verification and Exploration

* Manually calculated MSE, RMSE, MAE, and R².
* Compared manual calculations with Scikit-Learn outputs.
* Added Median Absolute Error as an additional metric.
* Conducted an experiment with artificial prediction errors.
* Observed the sensitivity of evaluation metrics to outliers.

## Evaluation Metrics

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Error (MAE)
* R² Score
* Median Absolute Error

## Results

The multi-feature Linear Regression model achieved better predictive performance compared to the single-feature model. Increasing the number of informative features improved the model's ability to explain housing price variations. The evaluation also demonstrated that MSE and RMSE are more sensitive to large prediction errors than MAE.

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run all cells sequentially.
3. Review model outputs, visualizations, and evaluation metrics.
4. Compare the performance of different models and train-test splits.

## Author

**Yash Dadhich**

AI/ML Internship Project
