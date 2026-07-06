# Titanic-Survival-Classifier
# Titanic Survival Classifier

A machine learning project that predicts passenger survival on the Titanic using a Random Forest classifier, built with pandas and scikit-learn.

## Overview

This project walks through a complete, simple data science pipeline:
1. Load raw passenger data
2. Clean and handle missing values
3. Encode categorical features
4. Train a Random Forest model
5. Evaluate accuracy on unseen data
6. Interpret which features mattered most

## Dataset

The dataset used is the classic Titanic passenger dataset (891 passengers), including features like age, sex, ticket class, fare, and port of embarkation, with survival as the target label.

## Tools Used

- Python
- pandas / numpy — data loading and cleaning
- scikit-learn — model training and evaluation
- matplotlib — visualization

## Results

- **Accuracy:** [FILL IN YOUR ACCURACY]% on the held-out test set
- **Top predictors:** Sex and passenger class were the strongest signals of survival

![Feature Importance](images/feature_importance.png)

## How to Run

1. Open `titanic_survival_classifier.ipynb` in Google Colab
2. Run all cells in order (Runtime → Run all)
3. The final cells will print the accuracy score and display the feature importance chart

## Key Takeaway

Gender and socio-economic class (reflected in fare and passenger class) were the dominant factors in survival — consistent with historical accounts of lifeboat prioritization during the disaster.
