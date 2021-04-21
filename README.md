# Neural Architecture Search using Bayesian Optimization to Model Customer Churn

## Background

Building an artificial neural network for predicting a bank's customer churn by maximizing the model's predictive accuracy as a function of the model architecture hyperparameters. This is done through Bayesian optimization using a Gaussian Process surrogate model. More information on the background, goals, and details of the project can be found in Proposal.pdf and Update.pdf, while some preliminary results can be found in Presentation.pdf


## Data

Anonymized customer churn data (churn_modelling.csv) obtained from https://www.kaggle.com/shrutimechlearn/churn-modelling

## Code

All project code found in churn-bayesian.ipynb

TODO: 
* Fix GCP environment to properly display Ax plotly rendered plots
* Further analysis on results, specifically on bandit acquisition function choices throughout course of experiment
