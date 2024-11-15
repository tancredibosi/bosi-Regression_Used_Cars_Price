# bosi-Regression_of_Used_Cars_Price

## Objectives
This project aims to explore and predict used car prices using machine learning techniques, providing insights into the factors that influence pricing in the automotive market through time. The dataset used contains detailed information about vehicles, including various attributes such as brand, model, year, mileage, and other specifications.

## Project Structure
The goal is to develop a reliable predictive model that can estimate car prices based on the given features. The project involves a systematic workflow for the preparation of the data before giving it to the Machine Learning models:
 - Data Visualization: create plots to analyze the relationship between various features of the dataset and the target variable (price), providing key insights and observations. 
 - Data Preprocessing: remove outliers, extract features from the given ones, fill missing values, remove useless features, scale numerical columns and encode categorical columns.
 - Train Test Split: split the data into train set and test set.

The evaluation of the models is done through RMSE, checking it on the train and test set to measure performance, but also overfitting.
Here the models involved:
 - Ridge Regressor
 - Random Forest Regressor
 - Random Forest Regressor using grid search
 - AdaBoost Regressor using Decision Trees
 - AdaBoost Regressor using Random Forest
 - Multi Layer Perceptron Regressor

## Results
From the training of the models it can be seen as the Random Forest Regressor, with the hyperparameters found with the grid search approach, is the best model, having the lowest Test RMSE and keeping an high Train RMSE, meaning that the model generalize well. Here below the results for each model:

| Model                        | Train RMSE | Test RMSE |
|------------------------------|------------|-----------|
| Ridge Regressor              | 19192      | 18878     |
| Random Forest Regressor      | 8134       | 17625     |
| Random Forest Regressor GS   | 15130      | 16518     |
| Ada Boost Regressor          | 19941      | 19990     |
| MLP Regressor                | 17049      | 17043     |
| AdaBoost RF Regressor        | 14433      | 16710     |

## References
Link to the Kaggle competition: https://www.kaggle.com/competitions/playground-series-s4e9