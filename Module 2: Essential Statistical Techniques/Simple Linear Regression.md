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
<img src="https://www.scribbr.com/wp-content/ql-cache/quicklatex.com-24c2acc90e12e44ba70f7cae7508ae7e_l3.png" width="200" height="25">

* y represents the anticipated value of the dependent variable (y) corresponding to any given value of the independent variable (x).
* B0 denotes the intercept, indicating the anticipated value of y when x is 0.
* B1 signifies the regression coefficient – indicating the extent to which we anticipate y to change as x increases.
* x stands for the independent variable (the variable we anticipate influences y).
* e represents the error of the estimate, indicating the degree of variation in our estimation of the regression coefficient.
  
Linear regression determines the best-fit line through the data by seeking the regression coefficient (B1) that minimizes the total error (e) of the model.

# Simple Linear Regression in R

To perform simple linear regression in R, you can use the `lm()` function, which stands for linear model. Let's say we want to investigate the relationship between the number of doctor visits (independent variable) and health outcomes (dependent variable) among minority populations

Example R Code: model <- lm(health_outcomes ~ doctor_visits, data = data)

# Interpreting the Results
Example R Code: summary(model)


| Coefficients   | Estimate | Std. Error | t value | Pr(>|t|)   |
|----------------|----------|------------|---------|------------|
| (Intercept)    | 62.35338 | 4.41048    | 14.141  | 3.43e-06   |
| doctor_visits  | 1.47425  | 0.26308    | 5.606   | 0.000595   |

- Residual standard error: 1.906 on 8 degrees of freedom
- Multiple R-squared: 0.7917, Adjusted R-squared: 0.7669
- F-statistic: 31.45 on 1 and 8 DF, p-value: 0.0005951

Coefficients:

* Intercept (62.35338): This represents the estimated health outcome when the number of doctor visits is zero. It implies that, if a person does not visit the doctor at all, their health outcome is estimated to be around 62.35.
* Doctor_visits (1.47425): This coefficient suggests that, on average, for each additional doctor visit, the health outcome increases by approximately 1.47 units.
* R-squared: The R-squared value (0.7917) indicates that approximately 79.17% of the variability in health outcomes can be explained by the linear relationship with the number of doctor visits.
* P-values: The p-value associated with the coefficient for doctor_visits is very small (0.000595), indicating that the relationship between the number of doctor visits and health outcomes is statistically significant.

In conclusion, the results suggest that there is a statistically significant positive linear relationship between the number of doctor visits and health outcomes among the studied population. As the number of doctor visits increases, health outcomes tend to improve. This finding may suggest that increasing access to healthcare services, such as promoting regular doctor visits, could potentially lead to better health outcomes among minorities in healthcare.
