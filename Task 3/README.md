# Wine Quality Prediction

## Project Overview

This project focuses on predicting wine quality using Machine Learning classification techniques. The wine quality is classified into two categories: Good and Bad, based on the physicochemical properties of red wine.

## Objectives

- Analyze the wine quality dataset
- Explore the distribution and relationships between wine features
- Classify wines as Good or Bad
- Train multiple Machine Learning classification models
- Compare model performance
- Identify the best-performing model

## Dataset

The project uses the Red Wine Quality dataset (`winequality-red.csv`).

The dataset contains physicochemical properties of wine such as:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

The original `quality` score is converted into a binary target:

- 0 = Bad Wine
- 1 = Good Wine

A wine with a quality score of 6 or above is considered Good.

## Exploratory Data Analysis

The project includes:

- Wine quality distribution
- Feature distributions
- Correlation heatmap
- Good vs Bad wine distribution
- Feature importance analysis

## Machine Learning Models

The following classification models were trained and evaluated:

1. Random Forest Classifier
2. SGD Classifier
3. Support Vector Classifier (SVC)

## Model Evaluation

The models were evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

The models were compared based on their accuracy, and the model with the highest accuracy was selected as the best-performing model.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Conclusion

This project demonstrates how Machine Learning can be used to predict wine quality based on the physicochemical properties of wine.

Different classification models were trained and compared to determine the best-performing model for predicting Good and Bad wine quality.
