# What is Logistic Regression?
The Logistic Regression is a statistical method used for modeling the relationship between a binary dependent variable and one or more independent variables. It's commonly used when the dependent variable represents a categorical outcome with two possible values (e.g., yes/no, success/failure, 0/1).

# Assumptions of Logistic Regression
* The dependent variable should be dichotomous in nature, meaning it only has two possible outcomes.
* There should be no outliers in the data
* There should be no high correlations (multicollinearity) among the predictors.

# Logistic Regression Formula
  
<img src="https://www.learnbymarketing.com/wp-content/uploads/2017/09/logistic-reg-formula-e1504965903637.png" width="300" height="150">

Logistic regression, similar to linear regression, employs the conventional regression formula within the logistic function of e^x / (1 + e^x). Consequently, this logistic function introduces an altered interpretation of coefficients.

Graphically, while linear regression entails fitting a straight line, logistic regression (probabilities) entails fitting a curved line between zero and one. Observe in the illustration below how the inputs (x-axis) remain consistent while the outputs (y-axis) demonstrate significant variation.

<img src="https://www.learnbymarketing.com/wp-content/uploads/2017/09/logistic-reg-vs-linear.png" width="400" height="300">

# Logistic Regression in R Example
You want to know if smoking status (smoker/non-smoker) predicts the likelihood of developing lung cancer.

Example R Code: 
lung_model <- glm(lung_cancer ~ smoking, data = lung, family = "binomial")
<br /> summary(lung_model)

In this code:

* glm() is the function used to fit generalized linear models, including logistic regression.
* lung_cancer ~ smoking specifies the formula where lung_cancer is the outcome variable and smoking is the predictor variable.
* data = lung specifies the dataset.
* family = "binomial" specifies that logistic regression should be used.

# Interpret Results

| Coefficients | Estimate | Std. Error | z value | Pr(>|z|) |
|--------------|----------|------------|---------|----------|
| (Intercept)  | -3.53100 |   0.30755  | -11.479 |  < 2e-16 |
| smoking      |  0.72935 |   0.15724  |  4.641  | 3.49e-06 |

* The coefficient for smoking is 0.72935, which means that the log odds of developing lung cancer increases by 0.72935 for each unit increase in the smoking status (e.g., from non-smoker to smoker).
* The p-value associated with the smoking coefficient is very low (3.49e-06), indicating that smoking status is significantly associated with the likelihood of developing lung cancer.
* The null hypothesis (H0) is that there is no association between smoking status and the likelihood of developing lung cancer.
* The alternative hypothesis (Ha) is that there is an association between smoking status and the likelihood of developing lung cancer.

Based on the low p-value (less than the conventional significance level of 0.05), we reject the null hypothesis and conclude that smoking status is significantly associated with the likelihood of developing lung cancer.

# Odds Ratio

The odds ratio is a crucial measure in logistic regression that helps quantify the association between the predictor variable (independent variable) and the outcome variable (dependent variable). In logistic regression, the odds ratio tells us how much the odds of the outcome variable change given a one-unit change in the predictor variable, holding all other variables constant.

Odds Ratio=e^Coefficient Estimate

In this case, 
R Code: exp(0.72935)

This yields the odds ratio associated with smoking, which indicates how much the odds of developing lung cancer change for smokers compared to non-smokers.

Interpretation:

In this example, the odds ratio for smoking is approximately 2.07.
This means that the odds of developing lung cancer for smokers are about 2.07 times higher than the odds for non-smokers, all other variables being equal.
The odds ratio provides a valuable measure of the strength and direction of the association between the predictor variable (smoking) and the outcome variable (likelihood of developing lung cancer) in logistic regression analysis.
