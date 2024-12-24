# BoomBikes Linear Regression Assignment (Case Study)
> A Multiple Linear Regression is being performed on the data set from a Bike Rental Company called Boombikes using RFE and MinMax Scaling.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)


## General Information
- The project is done as part of coursework in the Machine Learning module.
- Multiple linear regression is performed on the dataset.
- We are trying to find the number of rentals issued from the company based on numerous independent values such as temperature, weather, humidity, holiday, etc.
- The Boombikes bike rental dataset is being used.

## Technologies Used
- pandas
- seaborn
- matplotlib
- statsmodels
- sci-kit learn
- numpy

## Conclusions
- The developed model's mean squared error is almost 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set. The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.

- The R-squared value of the train set is 82.74% whereas the test set has a value of 81.21% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.

- The major steps included in the python notebook are data interpretation, data visualisation, data pre-processing, model training, feature selection, residual analysis, model evaluation on the test set.

- Concepts such as EDA, p-value, VIF, RFE were used and model building was done using statsmodels library

## Contact
Created by [@shashidharpattar007] - feel free to contact me!
