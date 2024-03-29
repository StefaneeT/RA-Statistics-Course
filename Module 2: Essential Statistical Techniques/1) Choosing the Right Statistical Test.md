# Choosing the Right Statistical Test

In hypothesis testing, statistical tests serve several purposes:

They help show if a predictor variable holds a statistically significant association with an outcome variable and they aid in estimating discrepancies between two or more groups.
These tests operate under the assumption of a null hypothesis, suggesting no relationship or distinction between groups. They also assess whether observed data goes beyond the range of values.

To determine which statistical test to use, you need to know:

1. Whether your data meets certain assumptions.
2. The types of variables that you’re dealing with.

# Assumptions in Statistical Analysis

Statistical tests rely on certain assumptions about the data:

1. Independence of observations (also known as no autocorrelation): The observations or variables used in the test should not be interrelated. For instance, multiple measurements of a single test subject are not independent, whereas measurements from different test subjects are considered independent.

2. Homogeneity of variance: Assumes that the variation within each group being compared is comparable among all groups. If one group exhibits significantly more variation than others, it can impede the effectiveness of the test.

3. Normality of data: Assumes that the data adheres to a normal distribution, resembling a bell curve. It primarily applies to quantitative data.

When data fails to meet the assumptions of normality or homogeneity of variance, nonparametric statistical tests may offer a solution, enabling comparisons without assumptions about the data distribution.

# Types of Variables

The nature of variables typically dictates the suitable statistical test for analysis.

## Quantitative variables denote quantities and can be categorized as:

1. Continuous <br>
2. Discrete <br>

## Categorical variables denote groupings and include:

Ordinal: Represent data with a specific order.<br>
Nominal: Represent group names.<br>
Binary: Represent data with a yes/no or 1/0 outcome.

Select the appropriate test based on the types of predictor and outcome variables collected. 


# Regression Tests
Regression tests seek to identify cause-and-effect connections. 

| Regression Test            | Predictor Variable              | Outcome Variable                     |
|----------------------------|---------------------------------|--------------------------------------|
|Simple linear regression    | Continuous, 1 Predictor         | Continuous, 1 Outcome                |
|Multiple linear regression  |Continuous, 2 or more Predictors | Continuous, 1 Outcome                |
|Logistic regression         | Continuous                      | Binary                               |


# Comparison tests
Comparison tests look for differences among group means. 

| Comparision Test           | Predictor Variable              | Outcome Variable                     |
|----------------------------|---------------------------------|--------------------------------------|
|ANOVA                       |Categorical, 1 or more predictor | Quantitative, 1 outcome              |
|MANOVA                      |Categorical, 1 or more predictor | Quantitative, 2 or more outcomes     |
|Paired T-Test               |Categorical, 1 predictor         | Quantitative, groups come from the same population|
|Independent T-Test          |Categorical, 1 predictor         | Quantitative, groups come from different populations|

# Correlation Test
Correlation tests determine if variables exhibit a relationship without implying a cause-and-effect association.

| Correlation Test           | Variables                       |
|----------------------------|---------------------------------|
|Pearson's r                 |2 continuous variables           |


# Non-Parametric tests
Non-parametric tests are less reliant on data assumptions and prove beneficial when common statistical assumptions are violated.
  

| Non-Parametric Test        | Predictor Variable              | Outcome Variable                     |
|----------------------------|---------------------------------|--------------------------------------|
|Chi square test of Independence|Quantitative | Quantitative              |


<img src="https://www.statisticalaid.com/wp-content/uploads/2022/09/statistical-test.png" width="800" height="800">
