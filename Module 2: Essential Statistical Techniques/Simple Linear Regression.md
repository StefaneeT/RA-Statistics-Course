# What is Simple Linear Regression

Simple linear regression is a statistical technique used to analyze and summarize the relationships between two continuous (quantitative) variables:

* One variable, labeled as x, is considered the predictor, explanatory, or independent variable.
* The other variable, labeled as y, is considered the response, outcome, or dependent variable.

Regression models describe the relationship between variables by fitting a line or curve to observed data. Linear regression employs a straight line, whereas logistic and nonlinear regression models use curved lines. Regression analysis enables estimation of how a dependent variable alters as independent variable(s) vary.

For example, in healthcare disparities among minorities, regression analysis could help determine how access to healthcare services (independent variable) affects health outcomes (dependent variable) among different ethnic groups.

# Assumptions of simple linear regression
Simple linear regression is a parametric test, which means it relies on certain assumptions about the data. These assumptions include:

1. Homogeneity of variance (homoscedasticity): The error in our prediction remains relatively consistent across different values of the independent variable.
2. Independence of observations: Data collection involves statistically sound sampling methods, with no concealed relationships among observations.
3. Normality: The data distribution adheres to a normal distribution pattern.

In addition to these assumptions, linear regression has one more:

4. Linearity: The relationship between the independent and dependent variables is linear, where the best-fit line through the data points is a straight line rather than a curve or another grouping factor.

If your data fail to meet the assumptions of homoscedasticity or normality, you might consider using a nonparametric test like the Spearman rank test.

# Simple Linear Regression Formula
<img src="https://www.scribbr.com/wp-content/ql-cache/quicklatex.com-24c2acc90e12e44ba70f7cae7508ae7e_l3.png" width="1000" height="200">

* y represents the anticipated value of the dependent variable (y) corresponding to any given value of the independent variable (x).
* B0 denotes the intercept, indicating the anticipated value of y when x is 0.
* B1 signifies the regression coefficient – indicating the extent to which we anticipate y to change as x increases.
* x stands for the independent variable (the variable we anticipate influences y).
* e represents the error of the estimate, indicating the degree of variation in our estimation of the regression coefficient.
  
Linear regression determines the best-fit line through the data by seeking the regression coefficient (B1) that minimizes the total error (e) of the model.
