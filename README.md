# Crop Prediction using Soil Metrics

## Project Overview

This project aims to assist farmers in selecting the best crop for their fields based on soil metrics such as nitrogen, phosphorous, potassium levels, and pH value. By leveraging machine learning classification models, we predict the optimal crop to maximize yield while considering soil conditions.

## Dataset

The dataset [`soil_measures.csv`](https://github.com/Sophie-XL/Classification_Agri_Project/blob/631285fdd735d602e8839f19fad0523cba5b4d9b/soil_measures.csv) contains the following columns:

- "N": Nitrogen content ratio in the soil
- "P": Phosphorous content ratio in the soil
- "K": Potassium content ratio in the soil
- "pH": pH value of the soil
- "crop": Categorical values representing various crops (target variable)

## Project Structure

The project is structured as follows:

- [`soil_measures.csv`](https://github.com/Sophie-XL/Classification_Agri_Project/blob/631285fdd735d602e8839f19fad0523cba5b4d9b/soil_measures.csv): Dataset containing soil metrics and crop information.
- [`Agri_project.ipynb`](https://github.com/Sophie-XL/Classification_Agri_Project/blob/631285fdd735d602e8839f19fad0523cba5b4d9b/Agri_project.ipynb): Jupyter Notebook containing the Python code for data preprocessing, model building, and evaluation.
- `README.md`: This file providing an overview of the project.

## Code Overview

The [`Agri_project.ipynb`](https://github.com/Sophie-XL/Classification_Agri_Project/blob/631285fdd735d602e8839f19fad0523cba5b4d9b/Agri_project.ipynb) notebook contains the following sections:

1. Data Loading and Exploration: Loading the dataset and performing exploratory data analysis.
2. Data Preprocessing: Handling missing values and scaling the input variables.
3. Model Selection: Comparing the performance of Logistic Regression, K-Nearest Neighbors, and Decision Tree models using cross-validation.
4. Model Evaluation: Evaluating the selected Decision Tree model on the test set and fine-tuning hyperparameters using Grid Search.
5. Feature Importance: Identifying the most important feature for predictive performance using the Decision Tree model.

## Results

- The Decision Tree model outperformed other models with an accuracy score of 77.3% on the test set.
- After hyperparameter tuning, the accuracy increased by 2%.
- The most important feature for predicting crop type was potassium content (K) in the soil.

## Skills Utilized

- Data Preprocessing: Handling missing values and scaling input variables.
- Machine Learning Model Building: Utilizing Logistic Regression, K-Nearest Neighbors, and Decision Tree models.
- Model Evaluation and Hyperparameter Tuning: Evaluating model performance and fine-tuning hyperparameters using Grid Search.
- Feature Importance Analysis: Identifying the most important feature for predictive performance.

## Conclusion

This project demonstrates the application of machine learning classification techniques in predicting crop types based on soil metrics. By leveraging predictive modeling, farmers can make informed decisions to maximize crop yield and optimize resource utilization.
