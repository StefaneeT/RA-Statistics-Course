# Background 
## Definitions and Terms

| Term                    | Definition                                                                                           |
|-------------------------|------------------------------------------------------------------------------------------------------|
| Null Hypothesis (H0)   | The statement or claim being made (which we are trying to disprove                      |
| Alternate Hypothesis   | The statement that the researcher is trying to find evidence to support                                |
| Type I Error           | Rejecting the null hypothesis when the null hypothesis is true                                           |
| Type II Error          | Failing to reject the null hypothesis when the alternative hypothesis is true                             |
| Test Statistics (t)    | A single number that summarizes the sample data used to conduct the test hypothesis                   |
| Standard Error         | How far sample statistics (e.g., mean) deviates from the actual population mean                        |
| p-value                | Probability of observing a test statistics, assuming that the null hypothesis is true                                                         |
| Significance level (α) | Probability of making Type I error                                                                    |
| One tailed test        | Test statistics falls into one specified tail of its sampling distribution                            |
| Two tailed test        | Test statistics can fall into either tail of its sampling distribution                                |

## Normal Curve
<img width="350" alt="Normal Curve" src="https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/a7bd752a-69bb-4047-b7e0-62e8fb7a9f8b">

## Acceptance/Rejection Regions: *Two Tailed Test*
<img width="348" alt="Two-Tailed" src="https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/de3885ea-2dba-4ce2-b59a-7624b0a9eb6f">


# Hypothesis Testing
## Steps to Significance Testing
1. Define H0 and Ha
2. Identify test, α, find critical value, test statistics
3. Construct acceptance/rejection regions
4. Calculate test statistics
* Critical value approach: Determine critical region
* p-value approach: Calculate p-value
5. Retain or reject the hypothesis


# Choosing a Statistical Test
<img width="588" alt="Statistical Test Decision Tree" src="https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/61d134a9-a5d3-441c-a343-2f5570bc0acb">

## Choosing by Data Structure

### Categorical Data: 
Use Chi Square

### Sample size (n):
* n < 30 and Population Variance is unknown - t-test
* n < 30 and Population Variance is known - z-test
* n > 30 - z-test or t-test

# Statistical Test Examples
## Chi Square test for independence:
Checks whether two categorical variables are related or not
(independence)

E.g., Is the distribution of smoking status and lung cancer diagnosis due to chance, or is there a relationship between smoking and lung cancer diagnosis rates in a population?

## T-Test:
Looks at the difference between two groups
(e.g., undergrad/grad)

E.g., Do patients who receive medication A differ significantly in blood pressure reduction compared to those who receive medication B?

## ANOVA (Analysis of Variance):
Tests the significance of group differences between two or
more groups (only determines that there is a difference between groups, but does not tell which is different)

E.g.,  Do different exercise regimens (keto, detox, and paleo diets) result in varied weight loss outcomes among obese patients?

## ANCOVA (Analysis of Covariance):
Same as ANOVA, but adds control of one or more covariates
that my influence dependent variable
E.g., Do cholesterol levels differ among patients undergoing different dietary interventions after controlling for age and gender differences?

# Proportions
Use when the respose is binary, eg. yes or no; Vote for candidate A
or not vote for candidate A
<img width="449" alt="Formulas" src="https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/e4ca8b0e-3921-4a30-b1ee-bdae4d234e97">


