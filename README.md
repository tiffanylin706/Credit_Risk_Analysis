# Credit_Risk_Analysis

An analysis using Machine Learning algorithms to identify credit card risk using a dataset from LendingClub.

# Overview

The purpose of this analysis is to build and evaluate machine learning models or algorithms to predict credit risk by using resampling and to understand how to utilize `Machine Learning` statistical algorithms to make predictions based on data patterns provided. In this challenge, we focus on **Supervised Learning** using a free dataset from **LendingClub**, a P2P lending service company to evaluate and predict credit risk. 

Different `Machine Learning` techniques to train and evaluate the data with unbalanced classes are used to complete the analyses. The dataset from the **LendingClub** has an unbalanced classification problem due to the number of good loans outweighing the amount of risky loans. In order balance out the classifications to allow for more meaningful predictions and improve the accuracy score, we needed to employ various `Machine Learning` algorithms to resample the data. 

# Results

As mentioned in the overview, we use `Machine Learning` to resample the dataset using `Python` libraries: `scikit-learn` and `imbalanced-learn` evaluate the results and provide a comparison for our analysis. 

The original dataset contained 115,675 loan applications in Q1 of 2019. We used the "loan status" to determine whether the application was considered "low" or "high" risk. Applications that had "current" as the "loan status" were classified as "low risk" and the remaining as "high risk". This reduced the dataset to 68,817 total applications with 99% classified as "low risk". 

