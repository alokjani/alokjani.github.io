t-test
======

- `t-test` or `two sample test` is used to compare 2 samples.
- The comparison is done by evaluating the means of the two groups. 


ANOVA
=====

- `ANOVA` is used to compare 2 or more sample groups for particular hypothesis.
- The acronym stands for `Analysis of Variance` and uses variance/Standard Deviation to compare between 2 or more groups.

Chi-Square
==========

- Both t-test and ANOVA will test whether the samples are related or not, but not the extent of correlation.
- `Chi-Square` will tell you the extent to which the two variables are inter-related. 
- Chi-Square test is used to test independence between the `predictor` variables based on a significance level.


Linear Regression
=================

- Linear Regression encodes `continuous predictors` (X1, X2 ...) as a function that predicts the value of `continuous outcome` variable (Y).

	Y = b0 + b1X1 + b2X2 + .... + bnXn

- i.e. `Dependent/outcome` variable is `continuous`, `Independent/predictor` Variables can be `continous` or `categorical` (encoded)


Logistic Regression
===================

- `Logistic regression` is used when the `dependent/outcome` variable is to be classified as either `Yes/No` or `True/False`. 
- i.e `Dependent/outcome` variable is `categorical`, `Independent/Predictor` variable can be `categorical` or `continous`.

- BLR accept `categorical` predictors and will code these variables as a function of probability that a particular object will be in one of the two categories.

- `Logit function` is used to represent encoded function.
