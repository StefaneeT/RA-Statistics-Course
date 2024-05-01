### Polynomial Regression

Polynomial regression is a method used to model a non-linear relationship between a dependent variable and one or more independent variables. It extends the multiple linear regression model by allowing the line of best fit to be a curve instead of a straight line.

![Polynomial](https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/a53c31dc-0eb9-4633-b001-666cdd2d5e93)

### Ridge Regression

Ridge regression is employed to address issues of multicollinearity among independent variables, where these variables are highly correlated. Although ordinary least squares estimates remain unbiased in such situations, their high variances can significantly distort the true relationship. Ridge regression combats this by introducing a bias to the regression estimates, which helps reduce the standard errors. The inclusion of a lambda (λ) parameter in ridge regression helps to tackle the problems caused by multicollinearity.

![Ridge Regression](https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/52b39ca6-1b84-47ed-a8d3-240c6e777fc2)

### Lasso Regression

Similar to ridge regression, lasso regression (Least Absolute Shrinkage and Selection Operator) also penalizes the coefficients of the regression model. However, it uniquely incorporates variable selection by driving some coefficients to zero, effectively eliminating them from the model.

![Lasso Regression](https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/b58c1738-6323-47dc-ad78-884c8631977e)

### General Linear Models (GLM)

General Linear Models (GLM) extend traditional linear regression by allowing for response variables that have error distribution models other than a normal distribution. This flexibility makes GLMs suitable for a range of data types, including binary, count, and continuous outcomes, thus providing a versatile framework for analyzing data with various distributions.

![GLM](https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/621f132d-ed79-4891-9e64-335be17f1375)

### Bayesian Linear Regression
Bayesian linear regression applies Bayes' theorem for regression analysis, offering a probabilistic approach to modeling relationships in data. Unlike traditional methods that compute least squares, Bayesian regression estimates the posterior distribution of the features, enhancing the model's stability and reliability.

![Bayesian](https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/af1c3c82-1b45-4cdd-8e5c-c4e75462fc2f)

### Partial Least Squares Regression

Partial least squares regression is a robust method particularly useful in scenarios with numerous independent variables and potential multicollinearity. It simplifies the complexity by reducing the dataset to fewer predictive components before conducting regression, making it both effective and efficient for large datasets.
