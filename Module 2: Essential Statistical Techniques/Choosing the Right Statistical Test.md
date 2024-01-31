# Choosing the Right Statistical Test

In hypothesis testing, statistical tests serve several purposes:

They help ascertain if a predictor variable holds a statistically significant association with an outcome variable.
They aid in estimating discrepancies between two or more groups.
These tests operate under the assumption of a null hypothesis, suggesting no relationship or distinction between groups. Subsequently, they assess whether observed data deviate beyond the range of values anticipated by the null hypothesis.

To determine which statistical test to use, you need to know:

1. Whether your data meets certain assumptions.
2. The types of variables that you’re dealing with.

# Assumptions in Statistical Analysis

Statistical tests rely on certain assumptions about the data under examination:

1. Independence of observations (also known as no autocorrelation): The observations or variables used in the test should not be interrelated. For instance, multiple measurements of a single test subject are not independent, whereas measurements from different test subjects are considered independent.

2. Homogeneity of variance: It assumes that the variation within each group being compared is comparable among all groups. If one group exhibits significantly more variation than others, it can impede the effectiveness of the test.

3. Normality of data: This assumption presupposes that the data adheres to a normal distribution, resembling a bell curve. It primarily applies to quantitative data.

When data fails to meet the assumptions of normality or homogeneity of variance, nonparametric statistical tests may offer a solution, enabling comparisons without assumptions about the data distribution.

If the assumption of independence of observations is not met, tests accommodating the data structure, such as repeated-measures tests or those involving blocking variables, might be applicable.

# Types of Variables

The nature of variables typically dictates the suitable statistical test for analysis.

## Quantitative variables denote quantities and can be categorized as:

Continuous (also known as ratio variables): These represent measures and can usually be divided into units smaller than one
Discrete (also known as integer variables): These represent counts and generally cannot be subdivided into units smaller than one

## Categorical variables denote groupings and include:

Ordinal: Represent data with a specific order.
Nominal: Represent group names.
Binary: Represent data with a yes/no or 1/0 outcome.

Select the appropriate test based on the types of predictor and outcome variables collected (in experiments, these correspond to independent and dependent variables). 


# Regression Tests

| Regression Type            | Predictor Variable   | Outcome Variable | Research Question Example |
|----------------------------|----------------------|------------------|---------------------------|
|Simple linear regression    |   * Continous *1 Predictor        |                  |                           |
|                               1 predictor                                                        |
|Multiple linear regression  |                                                                     |
|Logistic regression         |                                                                     |

