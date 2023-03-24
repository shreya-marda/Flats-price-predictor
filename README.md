# Project for predicting prices of flats

### Problem statement

* We are given the dataset of house prices with some features like number of bathrooms, number of bedrooms, etc
* Our task is to create a model which will predict the price for any new house by looking at these features.

Getting started:

* What is the objective?
* What are the purpose and the benefit of the model? (expectations)

Example of its benefit:
Suppose we predict the price of the house as 30L and someone is offering to sell the same house to the real estate company at 3Cr, then we have a net profit of 1.5Cr.

Steps to creating the model:

* This is a supervised learning model as we have features and labels.
* This is a regression problem as we need the value of the price.
* Batch learning or Online learning:
	This is a batch-learning problem as we already have data to predict but online learning is where you have a pipeline from where you continuously keep getting data and your model keeps getting trained.
	This is a batch learning model as we already have the data for now.


Selecting a performance measure:

* A typical performance measure for regression problems is Root Mean Square Error(RMSE)
* RMSE is generally the preferred performance measure for regression tasks, so we choose it for this particular problem
* Other performance measures include Meam Absolute error, Manhattan norm, etc

Checking the assumptions:
* It is very important to check for any assumptions we might make and more important to correct them before launching the ML model.
* We need to know that we need the prices, not the categories like expensive, cheap, etc..
