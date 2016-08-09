# Plaid Coat

Determining Car Worth. Linear Regression with a Python module `scikit-learn` for machine learning.

## Description

This project is about supervised machine learning algorithms (Linear Regression and Polynomial Linear Regression) that uses labeled data to predict outputs based on inputs. Linear regression attempts to model the relationship between two variables by fitting a linear equation to observed data. Equation form is  `y=a∗x+b`, where  `x`  is the explanatory variable (variable being used) and `y` is the dependent variable (variable being predicted). The slope of the line is `a`, and `b` is the intercept (the value of `y` when `x=0`).

## Motivation

The motivation of this project is to:

- Be able to use `scikit-learn` to perform linear regression
- Understand single-variable and multiple-variable linear regression
- Decide when to use polynomial linear regression of differing degrees
- Understand the use of dummy variables when fitting lines with linear regression

## Important links

- HTML documentation: http://scikit-learn.org
- Jupyter Notebook: https://github.com/ArtyomMinsk/car_worth_linear_regression/blob/master/car-worth.ipynb

## Special Instructions

User must import the following libraries:

- import pandas as pd
- import itertools
- import matplotlib.pyplot as plt
- import numpy as np
- from sklearn.cross_validation import train_test_split
- from sklearn.linear_model import LinearRegression
- from sklearn.pipeline import make_pipeline
- from sklearn.preprocessing import PolynomialFeatures
- %matplotlib inline
