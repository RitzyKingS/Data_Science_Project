# House Prices Prediction Project: Advanced Regression Techniques

This repository contains an end-to-end house price prediction project that utilizes advanced regression techniques. The project focuses on the Kaggle competition titled "House Prices: Advanced Regression Techniques." The project encompasses data exploration, preprocessing, model training, evaluation, and prediction.Link to DataSet.  [House Prices](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

## Project Overview

The objective of this project is to predict house prices using advanced regression techniques. The project utilizes the dataset provided by the Kaggle competition, which includes various features related to houses such as size, location, number of rooms, amenities, etc. By leveraging advanced regression techniques, we aim to build models that can accurately predict house prices based on these features.

## Key Features

1. **Basic Data Exploration:** The project starts with an initial exploration of the dataset, understanding its structure, and gaining insights into the available features.

2. **Exploration of the Dependent Variable:** The project examines the dependent variable (sale price) to understand its distribution, determine if normalization is required, and potentially apply appropriate transformations.

3. **Formulating Questions:** The project identifies specific questions to ask of the data, such as analyzing the distribution of sale prices, common building classes, correlation between overall quality and sale prices, neighborhood-based price differences, relationship between the number of rooms and sale prices, and the impact of garage size on prices.

4. **Data Preprocessing:** The project performs data preprocessing steps to handle missing values, handle categorical variables, and potentially normalize or transform variables as necessary. This ensures that the data is in a suitable format for training the regression models.

5. **Train and Evaluate Models:** The project utilizes advanced regression techniques such as Linear Regression, Logistic Regression, RidgeCV, LassoCV, Random Forest, and XGBoost Regressor. These models are trained and evaluated using appropriate evaluation metrics such as Root Mean Square Error (RMSE), Mean Absolute Error (MAE), and R-Squared to assess their performance.

6. **Prediction:** Once the models are trained and evaluated, they can be used to make predictions on the provided test dataset. This allows for estimating house prices based on the given features.

## Repository Contents

- `train.csv`: The training dataset containing house features and corresponding sale prices.
- `test.csv`: The test dataset for making predictions on unseen data.
- `sample_submission.csv`: An example submission file with the expected format for submission to the Kaggle competition.
- `data_description.txt`: A description of the dataset and its features.
- `House Prices - Advanced Regression Techniques.ipynb`: Jupyter Notebook demonstrating the complete pipeline of the project, including data exploration, preprocessing, model training, evaluation, and prediction.

## Dependencies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- sklearn
- plotly
- scipy

## How to Use

1. Clone the repository to your local machine.
2. Open the Jupyter Notebook `House Prices - Advanced Regression Techniques.ipynb` to explore and run the complete pipeline of the project.
3. Follow the instructions and code within the notebook to perform data exploration, preprocessing, model training, evaluation, and prediction.
4. Modify and experiment with different regression techniques, hyperparameters, and evaluation metrics to improve the prediction performance.
5. Utilize the trained models to make predictions on the provided test dataset and generate a submission file in the expected format for the Kaggle competition.

Note: Make sure to install the necessary dependencies in your Python environment to execute the code successfully.
