# Flight-Delay-Predictor
## Abstract
This project aims to predict flight delays using various machine learning models. By analyzing flight data from JFK airport, we developed a pipeline to proactively predict delays and improve operational efficiency and customer satisfaction.

## Introduction
Flight delays cause significant inconvenience to passengers and operational inefficiencies for airlines. The goal was to predict flight delays to enhance the user experience and reduce costs associated with inefficiencies.

## Methodology
- Data Preprocessing: Cleaned and prepared the dataset from Kaggle, which includes flights from JFK airport between Nov 2019 and Dec 2020.
- Exploratory Data Analysis: Performed EDA using boxplots and correlation matrices.
- Classification Models: Trained various models to predict whether a flight will be delayed. Used K-fold cross-validation (K=10) to ensure robust results.
- Regression Models: Applied regression techniques to predict the exact delay duration for delayed flights.

## Results
- Best Classifier: XGBoost with an accuracy of 92.66%.
- Best Regressor: K-Nearest Neighbors with an R² score of 0.68.

## Conclusion
Our pipeline effectively predicts flight delays, which can help airlines mitigate disruptions and improve customer satisfaction. The XGBoost classifier and K-Nearest Neighbors regressor were the most effective models for classification and regression, respectively.
