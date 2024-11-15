# Project Description
The notebook is structured in the following sections:
 - *Import useful libraries*: import libraries listed in the Prerequisites and set the random state.
 - *Load the data and print some stats*: load the "train.csv" file and visualize it through some prints (head, info, description).
 - *Plot the data*: create plots to analyze the relationship between various features of the dataset and the target variable (price), providing key insights and observations.
 - *Data Preprocessing*: remove outliers, extract features, deal with missing values, drop columns, scale columns and encode non-numerical features.
 - *Create X_train and y_train*: divide the data in 80% train set and 20% test set.
 - *Create, train and evaluate model*: train some Machine Learning models and evaluate them using RMSE and plotting some graphs. Here the models involved:
    - Ridge Regressor
    - Random Forest Regressor
    - Random Forest Regressor using grid search
    - AdaBoost Regressor using Decision Trees
    - AdaBoost Regressor using Random Forest
    - Multi Layer Perceptron Regressor

# Kaggle Reference
Link to the Kaggle competition: https://www.kaggle.com/competitions/playground-series-s4e9

# Installation and Startup Notes
For the installation of the sotware few memory is required (less than 50 Mb). Check the prerequisites before running the code.
I suggest to not press "run all" because the final section containing the models can take a lot of training time. 
In particular the Grid Search over the Random Forest Regressor models and the MLP Regressor

# Prerequisites
Python libraries needed for the sorftware:
 - pandas
 - numpy
 - matplotlib
 - seaborn
 - re
 - sklearn
