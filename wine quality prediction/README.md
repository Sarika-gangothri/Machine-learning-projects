# Wine Quality Prediction using Machine Learning

This project explores the feasibility of predicting wine quality using machine learning techniques.
Two datasets, `winequality-red.csv` and `winequality-white.csv`, are used, containing various physicochemical properties of red and white wines along with their corresponding quality ratings.

## Datasets

The datasets used in this project are:

*   `winequality-red.csv`: Contains information about red wines.
*   `winequality-white.csv`: Contains information about white wines.

Each dataset includes the following features:

*   Fixed acidity
*   Volatile acidity
*   Citric acid
*   Residual sugar
*   Chlorides
*   Free sulfur dioxide
*   Total sulfur dioxide
*   Density
*   pH
*   Sulphates
*   Alcohol
*   Quality (target variable)

## Project Overview

This project involves the following steps:

1.  **Data Loading and Exploration:** The datasets are loaded using the Pandas library, and exploratory data analysis (EDA) is performed to understand the data's characteristics and identify potential patterns.

2.  **Data Cleaning:** Missing values and duplicate entries are handled to ensure data quality.

3.  **Data Visualization:** Matplotlib and Seaborn libraries are used to visualize the data and gain insights into the relationships between features and wine quality.

4.  **Model Development and Evaluation:** Several classification models are trained and evaluated on both datasets.  Accuracy and cross-validation scores are used to assess model performance.

## Technologies Used

*   Python
*   Pandas
*   NumPy
*   Matplotlib
*   Seaborn
*   Scikit-learn

  ## Results

My results demonstrate promising potential for predicting wine quality. 

* ##  The Extra Trees Classifier achieved an accuracy of 61.8% on the red wine dataset.
* ## The Random Forest Classifier achieved an accuracy of 56.5% on the white wine dataset.

Further model tuning and feature engineering may improve these results.
Open for any suggestions or modifications further.
