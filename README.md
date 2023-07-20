# Data Scientist Salary Prediction

This project conducts an in-depth analysis using machine learning algorithms to forecast salaries for data science roles based on key factors like work experience, job title, employment type, and more. The goal is to shed light on data scientist salary trends and provide practical models to assist both employers and job seekers.

## Data

The raw data for this analysis is obtained from Kaggle's comprehensive [Data Science Salaries 2023](ds_salaries.csv) dataset. It contains over 3000 rows with features such as work experience level, employment type, job title, salary in different currencies, employee residence, remote work ratio, company location, and company size.

## Methods 

The data is thoroughly preprocessed including handling of missing values, removal of outliers, encoding of categorical variables, and scaling of numerical features.

Three powerful machine learning algorithms are employed:

- Logistic Regression
- Random Forest
- Gradient Boosting Classifier

The models are trained, tuned, and evaluated using K-fold cross validation. Evaluation metrics like accuracy, precision, recall, and F1 score are used to assess and compare the models' performance. Feature importance analysis is also conducted to understand the predictive power of each attribute.

## Key Findings

- The Gradient Boosting Classifier emerges as the best performer with an accuracy of 0.72, able to effectively predict salary buckets.

- Experience level, employment type, and job category are identified as the most influential factors affecting data scientist salaries. 

- The analysis uncovers opportunities to further improve model performance through larger datasets, algorithm tuning, and feature engineering.

## Contents

The repository contains the following key elements:

- [`data_exploration.ipynb`](Utilising_Machine_Learning_Algorithms_to_Forecast_Data_Scientist_Salaries.ipynb): Notebook for initial data exploration and visualization

- [`data_preprocessing.ipynb`](Utilising_Machine_Learning_Algorithms_to_Forecast_Data_Scientist_Salaries.ipynb): Notebook for cleaning, transforming, and preprocessing data

- [`model_training.ipynb`](Utilising_Machine_Learning_Algorithms_to_Forecast_Data_Scientist_Salaries.ipynb): Notebook for machine learning model building, evaluation and analysis

- [`data/`](ds_salaries.csv): Folder containing raw dataset

- [`outputs/`](Utilising_Machine_Learning_Algorithms_to_Forecast_Data_Scientist_Salaries.ipynb): Folder with visualizations, prediction results, and insights from analysis
