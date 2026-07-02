# K-Nearest Neighbors (KNN) Classification

## Project Overview
This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm using Scikit-learn to predict heart disease.

## Dataset
- heart.csv

## Libraries Used
- Pandas
- Scikit-learn

## Steps Performed
1. Imported required libraries.
2. Loaded the Heart Disease dataset.
3. Split the data into training and testing sets.
4. Applied StandardScaler for feature scaling.
5. Trained KNN classifier with different values of K (3, 5, 7).
6. Evaluated the model using Accuracy, Precision and Recall.
7. Used GridSearchCV to determine the best value of K using 5-fold Cross Validation.

## Evaluation Metrics
- Accuracy Score
- Precision Score
- Recall Score

## Best Result
- Accuracy: 91.80%
- Precision: 93.55%
- Recall: 90.63%

## Hyperparameter Tuning
GridSearchCV was used to identify the optimal number of neighbors.
