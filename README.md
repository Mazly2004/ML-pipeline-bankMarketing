# Bank Marketing ML Pipeline
  - A comprehensive machine learning pipeline for predicting customer responses and optimizing call strategies in bank marketing campaigns using XGBoost, Random Forest, and Logistic Regression models.

## Overview
This project implements a robust machine learning pipeline to enhance the efficiency of bank marketing campaigns by predicting customer responses and optimizing contact strategies. The pipeline performs two key predictive tasks:

#### Classification Task: Predicting whether a client will subscribe to a term deposit
#### Regression Task: Estimating the number of contact attempts (calls) required for successful conversion

The pipeline handles all aspects of the machine learning workflow, from data preprocessing and feature engineering to model training, evaluation, and visualization.

#### Dataset

Rows: 41,188

Columns: 21 

Source: ** UCI Machine Learning Repository - Bank Marketing Dataset **

Classification Target: y (yes/no) - whether the client subscribed to a term deposit

Regression Target: campaign - number of calls made during the campaign

### Features

Comprehensive Data Preprocessing: Handling of unknown values, standardization of numerical features, and encoding of categorical variables
Exploratory Data Analysis: Visualization of distributions, relationships, and correlations
Multiple Model Training: Implementation of various classification and regression algorithms

####  Classification: Logistic Regression, Random Forest, XGBoost
#### Regression: Linear Regression, Random Forest, XGBoost


Model Evaluation: Detailed performance metrics and comparative analysis
Feature Importance Analysis: Identification of the most influential factors

# Installation
bash# Clone this repository
git clone https://github.com/Mazly2004/bank-marketing-ml-pipeline.git
cd bank-marketing-ml-pipeline

## Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate

## Install required packages
pip install -r requirements.txt

## Requirements

Python 3.8+
scikit-learn
pandas
numpy
matplotlib
seaborn
xgboost

License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

** UCI Machine Learning Repository for providing the Bank Marketing Dataset
scikit-learn and XGBoost documentation and communities **
