This repository contains an analysis that compares the forecasting accuracy of three regression techniques—K-Nearest Neighbors (KNN), Multiple Linear Regression, and Polynomial Regression—to predict avocado sales in the U.S. Using a dataset from Kaggle, the study explores how each model performs in capturing the complex relationships between variables like average price, product type, and sales volume. Key evaluation metrics, such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared, are used to assess and contrast the models' predictive abilities.

Project Overview
This analysis aims to provide insights into the most effective regression techniques for avocado sales forecasting, offering industry practitioners a basis for data-driven decision-making. By applying these models, the study contributes to the broader conversation on predictive modeling in the agricultural sector.

Contents
Data Processing: The dataset undergoes various preprocessing steps, including:

Outlier Handling: Removal using the Interquartile Range (IQR) method.
Normalization: Scaling data for consistent analysis.
Encoding: Converting categorical data to numerical format for modeling.
Data Visualization: Charts and graphs illustrate trends, including:

Bar Charts for total sales volume by price level and year.
Scatterplots to examine correlations between features.
Heatmaps for correlation analysis between variables.
Regression Modeling:

Multiple Linear Regression (MLR), Polynomial Regression, and K-Nearest Neighbors (KNN) models are applied to the dataset, with performance compared based on accuracy and error metrics.
Model Comparison and Findings: The analysis highlights KNN as the most accurate model with an R-squared value of 93.7%, outperforming both MLR and Polynomial Regression.

Key Findings
KNN Regression outperformed other models with the highest R-squared score, indicating its strength in explaining sales variation.
Polynomial Regression achieved lower errors than MLR, suggesting its efficacy in capturing non-linear relationships.
Visualizations reveal trends in avocado sales, showing variations in volume and price across regions and product types.
