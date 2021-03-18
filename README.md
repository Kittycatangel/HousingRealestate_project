# HousingRealestate_project
 
Housing Prediction Project

Introduction

In this project,  multiple linear regression models were optimized to predict the price of houses in King County, Seattle. Three important questions about housing are asked in the beginning and answered at the end of the project.


Motivation

Linear regression models were made to help real estate advisers in real estate companies to  wisely choose housing properties which can be a good investments and render profits.
Linear regression models were assessed based on various perspectives. The first objective, is in general produce a model that can predict the price sale of houses in King County. The second objective, is to produce a model that  can predict the sale price of houses based only on exterior geographic/physical features. This analysis can help to observe if there is a potential effects of geographic/physical parameters on price sale. The third objective, is to produce a model to predict the price sale of houses in King County based only on internal house features. Finally, produce a model that can predict the incearse sale price of houses in King County.


OSEMN Approach

The model is constructed according to OSEMN approach: 
1 - Obtaining the data 2 - Scrubbing the data 3 - Exploring the data 4 - Modeling the data 5 - Interpreting the results.


The Dataset

For this project, the King County House Sales dataset is used. The dataset can be found in the file "kc_house_data.csv", in this repo. The description of the column names can be found in the column_names.md file in this repository. Moreover, a  pdf file  of the presentation of the major results can be found in this repository as "HousPricePredictionProject_presentation.pdf. Moreover,  a jupyter notebook of the python code and the pdf version of can be found as "HousePredictionModel_Final -Jupyter Notebook.pdf and HousePredictionModel_Final.ipynb.

Modelling Process

The initial data was cleaned,  null values are solved, data stantardizations, data normalizations and logarithmic transformations are made.
Normality, linearity and multicollinearity are checked. Visualisations are made. Baseline model is constructed. Model is refined again and again using many methods including normality check with q-q plots, homoscedasticity check with scatter plots of residuals, multicollinearity check with Variance Inflation Factor stepwise selection and K-fold Cross Validation.

Results and data interpretation

Four models were produced in this project to predict the sale price of the houses in King County following different objectives.  The most two important features to predict the sale price are square foot of the houses sold and house grade. Other influential feature that can help to increase the sale price of houses is the location.

In general  real estate investors should aim to look for square footage of the house, house grade (mostly high, 12 or 13), location, a house that has a view and a waterfront.

Conclusion

The most important features to predict the price sale of houses in King County, Seattle are square foot of the house, house grade and location.
