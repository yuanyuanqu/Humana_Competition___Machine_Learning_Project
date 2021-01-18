# Predict_Transportation_Challenge___Machine_Learning_Project-
## Project Description
Social determinants of health are the conditions in the environments in which people live, learn, work, play, worship and age that affect a wide range of health, functioning and quality-of-life outcomes and risks. Transportation challenges is one of these determinants.

In this project, we are trying to use the data provided and potentially supplementing with public data, create a model to predict which Medicare members are most likely struggling with Transportation Challenges.

## File Description
- 2020_Competition_Training.csv		= Data to be used for analysis & model development
- 2020_Competition_Holdout.csv		= Holdout data to be scored with final model and results returned with Oct 11 submission
- 2020_Competition_Data_Documentation	= File Statistics, File Layout, descritions of attributes for each event type  

## Model Description
In our project, we will conduct the following parts step by step:
- Exploratory Data Analysis
- Feature Engineering and Feature Selection
- Modeling using LDA, Logistic Regression, Neural Network

## Discussion
In our modeling part, we have encounted a problem, that is unbalanced predicted variables. In other words, more than 85% of the predicted variables are 0, but only 15% of them are 1. This led to the gradient vanishing problem. We are trying to figure it out, and we'll update findings as soon as we find the solutions.
