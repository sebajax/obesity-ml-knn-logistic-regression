# 🍏 Obesity Prediction using K-Nearest Neighbors (KNN) and Logistic Regression

Welcome to the Obesity Prediction repository! This project aims to predict obesity levels using two popular machine learning algorithms: K-Nearest Neighbors (KNN) and Logistic Regression. The dataset utilized in this project contains various health and lifestyle factors that contribute to an individual's obesity level.

## Project Overview

Obesity is a major health concern worldwide, associated with various chronic diseases and conditions. Accurately predicting obesity levels can aid in early intervention and effective health management. This repository provides an end-to-end machine learning pipeline for predicting obesity levels based on multiple health indicators.

## Dataset

The dataset comprises the following variables:

- **Gender**: Gender of the individual (categorical)
- **Age**: Age of the individual (numeric)
- **Height**: Height of the individual (numeric)
- **Weight**: Weight of the individual (numeric)
- **family_history_with_overweight**: Family history of overweight (binary: 1 = Yes, 0 = No)
- **FAVC**: Frequent consumption of high-calorie foods (binary: 1 = Yes, 0 = No)
- **FCVC**: Frequency of consuming raw vegetables (numeric)
- **NCP**: Number of main meals (numeric)
- **CAEC**: Consumption of food between meals (categorical)
- **SMOKE**: Smoking habit (binary: 1 = Yes, 0 = No)
- **CH2O**: Daily water intake (numeric)
- **SCC**: Calorie consumption monitoring (binary: 1 = Yes, 0 = No)
- **FAF**: Frequent physical activity (numeric)
- **TUE**: Technology usage time (numeric)
- **CALC**: Alcohol consumption (categorical)
- **MTRANS**: Main mode of transportation (categorical)
- **Obe1dad**: Obesity level (target variable: categorical)

## Data Preprocessing

- **Handling Missing Values**: Missing values are handled appropriately to ensure data integrity.
- **Feature Transformation**: Continuous numerical variables are standardized, while binary variables remain in their original scale.
- **Target Variable Transformation**: The target variable 'Obe1dad' is transformed from seven categories into two categories: 'Underweight or Normal' and 'Overweight or Obesity'.

## Machine Learning Models

### K-Nearest Neighbors (KNN)
KNN is a simple, non-parametric algorithm used for classification tasks. It classifies data points based on the majority vote of their neighbors.

### Logistic Regression
Logistic Regression is a statistical model used for binary classification. It predicts the probability of an outcome based on the input features.

## Repository Structure

- **data/**: Contains the dataset and any related files.
- **notebooks/**: Jupyter notebooks demonstrating data exploration, preprocessing, and model training.
- **src/**: Source code for data processing, model training, and evaluation.
- **models/**: Saved models for future predictions.
- **results/**: Results and evaluation metrics of the models.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
