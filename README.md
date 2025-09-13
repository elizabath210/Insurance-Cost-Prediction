
# Insurance Cost Prediction
In order to make their profit, insurance companies must collect a higher premium than the amount which may become due to the insured person. To achieve this, insurance companies invest a lot of time, effort, and money in creating models that accurately predict healthcare expenses.


## Problem Statement
Task 1:- Prepare a complete data analysis report on the given data.

Task 2:-
●	Prepare the data, identifying and extracting key features (both input and output parameters) relevant to the problem you will solve.
●	Build and train a machine learning model. Here you can evaluate different algorithms, settings and see which model is best for your scenario.


## Attribute Information
Attribute Information:
●	age: age of primary beneficiary
●	sex: beneficiary’s gender - female or male
●	bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
●	children: Number of children covered by health insurance / Number of dependents
●	smoker: Smoking or non-smoking
●	region: the beneficiary's residential area in the US; northeast, southeast, southwest, northwest.
●	charges: Individual medical costs billed by health insurance (to be predicted)
●	Id: id of beneficiary

## Libraries
 -Numpy
 -Pandas
 -matplotlib
 -Seaborn
 -scikit-learn

## Algorithms Used
 -Linear Regression
 -Decision Tree Regressor
 -Random Forest Regressor
 -Gradient Boost Regressor

## Model Comparison Result
Among the various algorithms used Gradient boosting gave   better results with r2_score 0.85.