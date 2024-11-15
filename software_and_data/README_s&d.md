# Project Description  
The notebook is structured into the following sections:

1. **Import Useful Libraries**  
   Import libraries listed in the prerequisites and set the random state.  

2. **Load the Data and Print Statistics**  
   Load the `train.csv` file and visualize it using commands like `head`, `info`, and `describe`.  

3. **Plot the Data**  
   Create visualizations to analyze the relationship between various features of the dataset and the target variable (price), providing key insights and observations.  

4. **Data Preprocessing**  
   Remove outliers, extract features, handle missing values, drop unnecessary columns, scale numerical columns, and encode categorical features.  

5. **Create `X_train` and `y_train`**  
   Split the data into 80% training set and 20% test set.  

6. **Create, Train, and Evaluate Models**  
   Train several machine learning models and evaluate them using RMSE and graphical representations. The models used include:  
   - Ridge Regressor  
   - Random Forest Regressor  
   - Random Forest Regressor with Grid Search  
   - AdaBoost Regressor with Decision Trees  
   - AdaBoost Regressor with Random Forest  
   - Multi-Layer Perceptron Regressor  

---

## Kaggle Reference  
The dataset is sourced from a Kaggle competition: [Playground Series - S4E9](https://www.kaggle.com/competitions/playground-series-s4e9).

---

## Installation and Startup Notes  
The software requires minimal memory for installation, occupying less than 50 MB, including the dataset. Before running the code, ensure that all prerequisites are met.  

**Note**: Avoid pressing **"Run All"** in the notebook, as the final section containing the model training can be time-consuming. This is especially true for the Grid Search with the Random Forest Regressor and the Multi-Layer Perceptron Regressor.

---

## Prerequisites  
The following Python libraries are required:  
- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `re`  
- `sklearn`

