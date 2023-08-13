# Datathon Open Competition - London Street Average Speed Forecasting

## Overview

This repository contains the work I've done for the Datathon Open Competition organized by RISTEK Universitas Indonesia. The competition aimed to predict and forecast the average speed of streets in London from February 23rd to 29th using historical data from February 1st to 22nd.

## Dataset

The competition dataset is available on [Kaggle](https://www.kaggle.com/competitions/ristek-datathon-2023/data). It includes historical information about street average speeds in London for the specified time period.

## Notebooks

The following notebooks showcase my work and approach for this competition:

1. [Notebook for preprocessing the data](https://github.com/alifrachmat2002/datathon-ristek/blob/ead0edccdc00f1a8f88814767787ccfadd1d2aab/Datathon%20-%20Preprocessing%20Code.ipynb) - This notebook outlines the steps I took to preprocess and clean the data.
2. [Notebook with MLforecast and LGBM Model](https://github.com/your-username/your-repo-name/blob/main/notebooks/datathon_notebook.ipynb), and [Notebook with MLforecast and XGBoostRegressor Model](https://github.com/your-username/your-repo-name/blob/main/notebooks/datathon_notebook.ipynb) -  This notebook outlines the steps I took to train the models using the MLforecast library, LGBM model, and XGBoostRegressor model. I also used the Optuna library for hyperparameter tuning.

## Models Used

### MLforecast

MLforecast is a library specifically designed for time series forecasting. It provides various tools to handle time series data and implement forecasting models.

### LightGBM (LGBM)

LightGBM is a gradient boosting framework that uses tree-based learning algorithms. It's known for its efficiency and accuracy in handling large datasets.

### XGBoostRegressor

XGBoost is another gradient boosting algorithm that has gained popularity for its high performance and flexibility in various machine learning tasks, including regression.

## Results

After thorough data preprocessing, feature engineering, and model tuning, I managed to achieve a lowest SMAPE score of 8.52 on the training set and 8.57 on the test set.

While I didn't qualify for the finals, this competition was a valuable learning experience, allowing me to apply advanced forecasting techniques and improve my skills in data analysis and machine learning.

Feel free to explore the provided notebook to see my code and methodology in detail.
