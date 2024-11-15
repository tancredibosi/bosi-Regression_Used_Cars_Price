# Regression of Used Car Prices  

## Objectives  
This project aims to explore and predict used car prices using Machine Learning techniques, offering insights into the factors that influence automotive pricing over time. The dataset includes detailed information about vehicles, such as brand, model, year, mileage, and additional specifications, which serve as predictors for car prices.  

## Project Structure  
The goal is to build a reliable predictive model for estimating car prices based on the provided features. The project follows a systematic workflow to prepare the data for machine learning models:  

- **Data Visualization**: Generate plots to examine the relationships between various features and the target variable (price), uncovering patterns and trends.  
- **Data Preprocessing**:  
  - Remove outliers.  
  - Extract meaningful features.  
  - Handle missing values.  
  - Drop irrelevant features.  
  - Scale numerical columns.  
  - Encode categorical features.  
- **Train-Test Split**: Divide the dataset into training and testing subsets to evaluate model performance.  

Model evaluation is conducted using the Root Mean Squared Error (RMSE) metric, which is calculated for both the training and testing datasets. This approach helps measure model accuracy and detect overfitting.  

### Machine Learning Models  
The following models were implemented and evaluated:  
- Ridge Regressor  
- Random Forest Regressor  
- Random Forest Regressor with Grid Search  
- AdaBoost Regressor with Decision Trees  
- AdaBoost Regressor with Random Forest  
- Multi-Layer Perceptron Regressor  

## Results  
The evaluation reveals that the **Random Forest Regressor**, with hyperparameters optimized via grid search, performs best. It achieves the lowest Test RMSE while maintaining a relatively high Train RMSE, indicating good generalization.  

### Model Performance Metrics  

| Model                        | Train RMSE | Test RMSE |  
|------------------------------|------------|-----------|  
| Ridge Regressor              | 19,192     | 18,878    |  
| Random Forest Regressor      | 8,134      | 17,625    |  
| Random Forest Regressor (GS) | 15,130     | 16,518    |  
| AdaBoost Regressor           | 19,941     | 19,990    |  
| MLP Regressor                | 17,049     | 17,043    |  
| AdaBoost RF Regressor        | 14,433     | 16,710    |  

## References  
This project is based on the Kaggle competition: [Playground Series - S4E9](https://www.kaggle.com/competitions/playground-series-s4e9).

## Author
Tancredi Bosi
