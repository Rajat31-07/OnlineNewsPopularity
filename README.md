# Project Title

**Online News Popularity**

## Team Members

* Rajat Chaudhary (rajatc@iisc.ac.in)
* Yuvaraj G (yuvarajgopi@iisc.ac.in)
* Srinivas Shavukapu Kattegummula (srinivassk@iisc.ac.in)
* Sonu Goyal (sonugoyal@iisc.ac.in)

## Problem Statement

This project aims to develop machine learning models to predict the popularity of online news articles, measured either by the number of shares (regression) or by popularity categories such as **Viral**, **Trending**, **Performer**, and **Niche** (classification). The goal is to assist media companies and content creators in optimizing content strategy and forecasting article virality.

## Dataset Description

The dataset comes from the **UCI Machine Learning Repository** and contains approximately **39,000 observations** of news articles published on Mashable. It includes **58 numerical and categorical features** such as metadata, content-based features, and social engagement metrics. The data is preprocessed by removing irrelevant columns, transforming shares via logarithm, and encoding categorical variables for machine learning.

## High-Level Approach and Methods

* **Data preprocessing** including outlier treatment, feature standardization, and one-hot encoding.
* **Exploratory Data Analysis (EDA)** to understand feature distributions and correlations.
* **Model development** using multiple algorithms for regression (Random Forest, Gradient Boosting, Lasso, SVR, KNN, MLP) and classification formulations.
* **Classification categories** of article popularity created using training set percentiles.
* Models evaluated using error metrics (**MAE, MSE, RMSE**) for regression and **accuracy, precision, and F1-score** for classification.
* **Hyperparameter tuning** using Optuna for improved classifier performance.

## Summary of Results

* **Gradient Boosting Regressor** achieved the best regression performance with RMSE of **0.8645** on log-transformed shares.
* Classification models showed moderate accuracy (**~58-63%**) but struggled with minority classes **Viral** and **Trending** due to class imbalance.
* **Random Forest** and **LightGBM** performed best overall among classifiers.
