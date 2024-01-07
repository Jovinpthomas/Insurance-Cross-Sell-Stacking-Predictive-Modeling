# Vehicle Insurance Cross Sell Prediction

## Problem Statement
Our client, a leading insurance company, is seeking to expand its offerings to include Vehicle Insurance. The goal is to develop a predictive model that can identify potential customers interested in purchasing Vehicle Insurance. This will enable the company to optimize its cross-selling strategy and target the right audience effectively.

## Background
Vehicle Insurance is a significant segment of insurance products, requiring customers to pay premiums regularly in exchange for coverage against unfortunate incidents involving their vehicles. The predictive model aims to leverage demographic information, details about the vehicles, and policy-related data to identify potential customers for Vehicle Insurance.

## Objective
Develop a robust machine learning model that can analyze customer data from the previous year and predict the likelihood of those policyholders showing interest in acquiring Vehicle Insurance.

## Dataset Overview
The dataset includes various features such as gender, age, driving license status, region code, vehicle age, vehicle damage, annual premium, policy sales channel, vintage, and the target variable indicating customer interest in Vehicle Insurance.

## Modeling Approach
The modeling approach involves the use of base models (Random Forest, XGBoost, Multi-Layer Perceptron) and a meta-model (LightGBM) for stacking. The model's accuracy is evaluated on the validation set, and the final predictions are made on the test set.

## Feature Engineering
Certain features are mapped and transformed to enhance the model's predictive power. Gender, vehicle age, and vehicle damage are encoded for better compatibility with machine learning algorithms.

## Data Exploration and Visualization
Exploratory data analysis is conducted to understand the distribution of features such as gender, age, vehicle age, and vehicle damage. Visualization techniques like bar charts and pie charts are employed for a clearer representation of the data.

## Correlation Analysis
Correlation analysis is performed to understand the relationships between different features. A heatmap is created to visualize the correlation matrix.

## Model Evaluation
Base models (Random Forest, XGBoost, MLP classifier) are trained and evaluated on the validation set. The accuracy of each base model is assessed, and a meta-model (LightGBM) is built for stacking.

## Predictions and Threshold Setting
Predictions are made on the test set using base models and the meta-model. A threshold is set for binary classification, and final predictions are saved to a CSV file.

## ROC Curve and AUC
The ROC curve and AUC (Area Under the Curve) are calculated to evaluate the stacked model's performance. The results are visualized to assess the model's ability to distinguish between classes.

## Confusion Matrix and Metrics
A confusion matrix is generated, and metrics such as accuracy, precision, recall, and F1 score are calculated. The results are presented in a tabular format for easy interpretation.

## Conclusion
The developed predictive model provides valuable insights into potential customers interested in Vehicle Insurance. The optimized cross-selling strategy based on these predictions can contribute to revenue optimization and enhanced market positioning.
