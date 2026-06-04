# Data Navigator

## Project Overview

Data Navigator is a personal data science project developed to simplify the end-to-end machine learning workflow. The goal of this project is to reduce repetitive tasks in data analysis by integrating data preprocessing, model training, evaluation, and visualization into a single application.

The system allows users to upload a dataset, automatically perform exploratory data analysis, apply preprocessing techniques, train machine learning models, and compare model performance through visual reports.

## Objectives

* Automate common data preparation tasks.
* Reduce the amount of manual configuration required for machine learning experiments.
* Provide a unified interface for classification, regression, and clustering problems.
* Generate visual insights to support model interpretation and decision-making.

## System Workflow

1. Upload dataset
2. Perform data inspection and preprocessing
3. Handle missing values and categorical features
4. Apply feature transformation and dimensionality reduction
5. Split training and testing data
6. Train machine learning models
7. Evaluate model performance
8. Visualize results and export outputs

## Implemented Features

### Data Preprocessing

* Missing value handling
* Duplicate record removal
* Feature encoding
* Data normalization
* Box-Cox transformation
* PCA dimensionality reduction

### Machine Learning

#### Classification

* Logistic Regression
* Random Forest
* Support Vector Machine
* Gradient Boosting
* XGBoost
* AdaBoost
* Naive Bayes

#### Regression

* Linear Regression
* Ridge Regression
* Lasso Regression
* Elastic Net
* Random Forest Regressor
* Gradient Boosting Regressor

#### Clustering

* K-Means
* DBSCAN
* Gaussian Mixture Model
* Hierarchical Clustering
* Spectral Clustering

### Model Evaluation

Classification:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC Curve
* AUC

Regression:

* MAE
* MSE
* RMSE
* R² Score
* Residual Analysis

Clustering:

* Silhouette Score
* Davies-Bouldin Index
* Calinski-Harabasz Score

## Data Visualization

The platform includes several visualization modules:

* Distribution analysis
* Correlation analysis
* Feature relationship analysis
* 3D scatter visualization
* Word cloud generation
* Geographic heat maps

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Plotly
* Streamlit

## Future Improvements

* Time-series forecasting support
* Automated hyperparameter optimization
* Model explainability using SHAP
* Deep learning integration with PyTorch
* Deployment support for cloud environments
