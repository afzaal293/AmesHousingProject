# Lab 04 – Advanced Modelling, Classification and Clustering

## Dataset
Ames Housing Dataset

Rows: 2930
Columns: 82

## Objective

The objective of this project is to perform:

1. Data preprocessing
2. Regression modelling
3. Classification modelling
4. Clustering analysis
5. Feature importance analysis

using the Ames Housing dataset.

## Data Preparation

The following preprocessing steps were performed:

- Removed unnecessary ID columns
- Handled missing values
    - Median imputation for numerical features
    - Mode imputation for categorical features
- One-Hot Encoding for categorical variables
- Standard Scaling for numerical variables

## Regression Models

Models trained:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

Evaluation Metrics:

- R² Score
- RMSE
- MAE

### Best Regression Model

Random Forest / Gradient Boosting achieved the best performance with the lowest prediction error.

## Classification Models

Target:

HighPrice

1 = SalePrice above median

0 = SalePrice below median

Models trained:

- Logistic Regression
- KNN
- Decision Tree
- Random Forest
- SVM
- Naive Bayes

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### Best Classification Model

Random Forest Classifier achieved the highest overall performance.

## Clustering

Algorithms Used:

- K-Means
- DBSCAN

Features Used:

- Overall Qual
- Gr Liv Area
- Total Bsmt SF
- Year Built
- Garage Cars
- SalePrice

Evaluation:

- Silhouette Score
- PCA Visualization

## Important Features

The most influential features were:

- Overall Qual
- Gr Liv Area
- Garage Cars
- Total Bsmt SF
- Year Built
- Full Bath
