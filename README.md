# Road Accident Prediction and Prevention (m-indicator Hackathon Project)


This repository contains Python scripts for analyzing and preprocessing the US Accidents dataset available on Kaggle. The dataset provides comprehensive information about traffic accidents across the United States, including various attributes such as weather conditions, location details, and accident severity. These scripts were developed as part of an open-ended 24-hour m-indicator hackathon, where participants were given the freedom to choose from a variety of categories. Our team chose to focus on road safety challenges and leveraged data-driven approaches to predict and prevent road accidents. The hackathon provided a platform for innovative solutions across different categories, and our team was motivated to contribute to improving overall road safety and reducing accidents' severity.
## Table of Contents

- Overview
- Exploratory Data Analysis (EDA)
- Preprocessing
- Model Building
- Increasing the Recall of High Severity Accidents

## Overview

The main objective of this project is to perform exploratory data analysis, preprocess the dataset, and build predictive models to classify accident severity. The analysis includes identifying patterns, correlations, and factors affecting accident severity.

## Exploratory Data Analysis (EDA)

The initial exploration of the dataset involves understanding its structure, checking for missing values, and examining unique values of attributes. This step provides insights into the distribution and characteristics of the data.

## Preprocessing

Preprocessing steps include data cleaning, feature selection, and transformation. This ensures that the dataset is ready for model building. Techniques such as label encoding, one-hot encoding, and scaling are applied to prepare the data for machine learning algorithms.

## Model Building

Several machine learning models are trained and evaluated for predicting accident severity. The models include Decision Tree Classifier, Logistic Regression, Random Forest Classifier, and XGBoost Classifier. Evaluation metrics such as accuracy, precision, recall, and F1-score are used to assess model performance.

## Increasing the Recall of High Severity Accidents

A specific analysis is conducted to increase the recall of high severity accidents (Severity Level 4). This involves creating a binary classification task to identify whether an accident is of high severity or not. Techniques such as adjusting threshold values and focusing on class imbalance are applied to improve the recall of high severity accidents.

--- 
