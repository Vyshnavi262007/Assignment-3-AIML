# Assignment-3-AIML
Machine Learning Tasks
Overview
This repository contains the implementation of two machine learning tasks using Python and Google Colab.

Student Performance Prediction using Linear Regression
Customer Segmentation using K-Means Clustering
The objective of this assignment is to understand regression and clustering techniques and evaluate model performance using appropriate metrics.

1. Student Performance Prediction using Linear Regression
Objective

To evaluate the effectiveness of Linear Regression in predicting student performance based on input features.
Steps Performed:
Imported required libraries such as pandas, numpy, matplotlib and sklearn.
Loaded the Student Performance dataset.
Performed data exploration using head() and info().
Visualized the data using scatter plots and histograms.
Separated input features (X) and target variable (y).
Applied MinMaxScaler for feature scaling.
Split the dataset into training and testing sets.
Trained the Linear Regression model.
Predicted the output values.
Evaluated model performance using:
Mean Squared Error (MSE)
Mean Absolute Error (MAE)
R² Score.
Result:
The Linear Regression model predicts student scores based on the input features and its performance is evaluated using regression metrics.

2. Customer Segmentation using K-Means Clustering
Objective

To perform customer segmentation using the K-Means clustering algorithm and evaluate cluster quality using clustering metrics.
Steps Performed:
Imported required libraries.
Loaded the dataset.
Explored the dataset using head() and info().
Visualized relationships between features using scatter plots.
Applied MinMaxScaler for normalization.
Implemented K-Means clustering.
Assigned cluster labels to each data point.
Visualized clusters using scatter plots.
Evaluated clustering performance using:
Silhouette Score
Calinski-Harabasz Score
Davies-Bouldin Score.
Result:

The K-Means algorithm groups similar data points into clusters, helping identify patterns within the dataset.
Tools Used
Python
Google Colab
Pandas
NumPy
Matplotlib
Scikit-learn
GitHub

Repository Contents
StudentPerformance_LinearRegression.ipynb
CustomerSegmentation_KMeans.ipynb
README.md

