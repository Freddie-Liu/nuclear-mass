# Nuclear Mass Prediction Project

This project aims to use different machine learning models to predict nuclear mass  and compare the results with a traditional physical model, the Weizsäcker formula.

## Project Overview

The primary task of this project is to predict the nuclear mass. We used three machine learning models: Linear Regression, Multilayer Perceptron (MLP), and XGBoost, and compared their results with the Weizsäcker formula. Features selected include neutron number, proton number, mass number, proton separation energy, and neutron separation energy. We applied normalization to the data and split the dataset with an 8:2 ratio for training and testing.

## File Structure

- `code.ipynb`: The main Jupyter Notebook file containing the complete process of data processing, model training, evaluation, and result analysis.

## Dependencies

Before using this project, ensure you have the following Python libraries installed:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`
- `xgboost`

## Results and Analysis

- Linear Regression: MSE = 25,592,094.61, MAE = 3,878.24
- Multilayer Perceptron (MLP): MSE = 72,513,418.17, MAE = 7,104.05
- XGBoost: MSE = 3,760,266.11, MAE = 1,378.83
- Weizsäcker Formula: MSE = 10,378,939,271.76, MAE = 101,236.87
From these results, it is evident that the XGBoost model performed the best, with the lowest error rates, significantly outperforming the other models and the traditional Weizsäcker formula.