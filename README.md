# Predicting Boston Housing Prices

Supervised Learning Project of Udacity Machine Learning Engineer Nanodegree Program

Built a model to predict the value of a given house in the Boston real estate market using decision tree. Identified the best price that a client can sell their house utilizing machine learning.


## Project Overview

This project applies basic machine learning concepts on data collected for housing prices in the Boston, Massachusetts area to predict the selling price of a new home. This project consists of the following tasks:
* Explore the data to obtain important features and descriptive statistics about the dataset.
* Split the data into testing and training subsets.
* Determine a suitable performance metric for this problem.
* Hyper-parameter Tuning:
  - Analyze performance graphs for a learning algorithm with varying parameters and training set sizes.
  - Pick the optimal model that best generalizes for unseen data. 
* Test the optimal model on a new sample and compare the predicted selling price to the statistics.


## Machine Learning Theory

* Supervised learning using __decision trees__.
* Analyze learning curve to decide whether a model suffers from overfit (high variance) or underfit (high bias).
* Hyper-parameter tuning.


## Technical Skills

* `sklearn.tree.DecisionTreeRegressor`: decision tree for supervised learning.
* `sklearn.model_selection.GridSearchCV`: automatic hyper-parameter tuning.
* `sklearn.model_selection.ShuffleSplit`: split labeled data into training and validation sets.
* `sklearn.metrics.r2_score`: evaluate goodness of fit.
* `numpy` and `pandas`: data wrangling.


## Development Environment

* OpenSUSE Linux 42.2
* Anaconda 4.4 with Python 2.7
* pandas, numpy, sklearn
