
# Project: Laptop Price Prediction

## Introduction
In the modern technological era, laptops are essential for personal and professional use. The diverse range of models available, each with varying specifications and pricing, poses challenges for consumers to ascertain value-for-money options. Additionally, GPUs (Graphics Processing Units) are critical in defining laptop suitability for specific tasks such as gaming, graphic design, or machine learning.

## Problem Statement
Laptop prices vary significantly based on specifications such as processor, RAM, GPU, and weight. Identifying meaningful patterns manually is inefficient and inaccurate, necessitating automated, data-driven approaches.

## Objectives

### Price Prediction
Develop regression models to predict laptop prices accurately based on specifications, understanding pricing trends.

### GPU Classification
Classify laptops based on GPU types to identify patterns useful for specific user segments such as gamers, designers, and general productivity users.

## Dataset
The dataset from Kaggle comprises 1273 records with 13 columns (5 categorical, 8 numerical).

Key features:
- RAM, Weight, Price, HDD, SSD (Numerical)
- Company, GPU_brand, TypeName, OS (Categorical)

[Dataset Link](https://www.kaggle.com/datasets/gyanprakashkushwaha/laptop-price-prediction-cleaned-dataset/data)

## Methodology

### Data Preprocessing
- Checked for missing and duplicate values; duplicates and nulls removed.
- Normalized and scaled data.
- Encoded categorical variables using LabelEncoder.

### Machine Learning Algorithms

#### Classification
- Logistic Regression
- Artificial Neural Networks (ANN)
- Support Vector Machine (SVM)
- Naïve Bayes
- Decision Tree
- K-Means Clustering

### Regression Algorithms
- Simple Linear Regression
- Multivariate Linear Regression

## Processes & Improvements
- Hyperparameter tuning
- Feature selection and engineering
- Binary conversion of categorical classes

## Results and Insights

### Classification
- **Best Algorithm:** ANN with optimized hyperparameters (Accuracy: 85%)
- ANN provided significant improvement for class imbalance.
- Logistic Regression and SVM also showed good results after tuning.

### Regression Insights
- Simple Linear Regression: Initial R² was 45%; improved to 54% post log transformation, significantly reducing prediction errors.
- Multivariate Regression initially performed better (R²=62%) but didn't improve significantly after optimization.

## Key Findings
- ANN best for GPU classification.
- Simple Linear Regression after transformation best for price prediction.

## Conclusion
The project effectively applied machine learning techniques for predicting laptop prices and classifying GPU types, providing valuable insights for consumers and manufacturers.

## Team Members
- Rajesh Dulal
- Xanaldo Knox
- Devan Watson
- Rohan Saldanha
- Hetal Parmar
- Omasanjuwa Esun
