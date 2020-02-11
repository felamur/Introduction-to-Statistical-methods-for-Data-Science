# Project for Introduction to Statistical methods for Data Science

GRADE: 73%

ReportStatistical.docx is the report which includes the full code.

Report info:

In this project, aim is to model the given dataset. Given dataset is made from two synthetic electroencephalogram (EEG) time-series data. Both of these EEG channels are measured from two different parts of the brain. Purpose is to model and find out the degree of potential nonlinear synergy between the EEG channels.

First signal is referred as X and second signal is Y. To make it easier for our modelling processes we say X is input and Y is output. Since Y is output, that makes it dependent and makes X independent. This implies channel Y can be found by channel X. Both X and Y consists of 250 rows of data. Additionally, signal Y already contains additive noise of an unknown amount.

First step of our process is doing an initial data analysis. After that correct model structure found by doing AIC. Next step is estimating parameters of found model. After finalizing the model and parameters, we can move on to model’s evaluation. This includes parameter covariance matrix, uncertainty p.d.f and 95% confidence intervals. Our last step is validation our model by using train-test split validation to see if identified model is good or not. Code is written with R. Version used for R is version 3.6.1. Integrated development environment (IDE) that was chosen for R is rstudio.
