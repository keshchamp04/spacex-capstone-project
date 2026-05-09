# Predictive Analysis 🤖

## Overview
This section focuses on building machine learning models to predict the success of Falcon 9 first-stage landings using historical launch data.

## Objectives
- Train classification models on SpaceX launch data  
- Compare model performance using evaluation metrics  
- Predict whether the Falcon 9 first stage will land successfully  

## Files Included
- SpaceX_Machine Learning Prediction_Part_5.ipynb  
  → Performs feature scaling, model training, hyperparameter tuning, and evaluation of classification algorithms.

## Machine Learning Workflow
1. Prepared feature matrix and target labels  
2. Standardized input features using preprocessing techniques  
3. Split dataset into training and testing sets  
4. Trained multiple classification models:
   - Logistic Regression
   - Support Vector Machine (SVM)
   - K-Nearest Neighbors (KNN)
   - Decision Tree Classifier
5. Applied GridSearchCV for hyperparameter tuning  
6. Evaluated models using:
   - Cross-validation accuracy
   - Test accuracy
   - Confusion matrix

## Results
- Decision Tree Classifier achieved the best cross-validation performance  
- Final test accuracy obtained: **94.44%**  
- Machine learning models successfully predicted Falcon 9 landing outcomes using historical mission data  

## Tools Used
- Python  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib  
