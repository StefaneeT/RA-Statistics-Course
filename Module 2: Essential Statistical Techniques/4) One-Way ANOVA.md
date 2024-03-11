# Introduction to the Concept of ANOVA

Analysis of Variance (ANOVA) is a statistical test used to assess variations among the means of multiple groups.
In the context of ANOVA, a one-way test involves a single independent variable, whereas a two-way ANOVA involves two independent variables.

# ANOVA Example

You want to examine if the type of support system (family, friends, professional counseling) influence the mental health outcomes of LGBTQIA individuals, and if there are significant differences in mental health scores among these groups.

Your independent variable is the type of support system (family, friends, professional counseling), and you categorize individuals into groups based on the level of support they receive. The aim is to investigate potential differences in mental health scores among LGBTQIA individuals based on the type of support they have.
The null hypothesis (H0) states that there is no substantial difference among group means.

The alternative hypothesis (Ha) states that there is substantial difference among group means.

# When should you use a One-Way ANOVA?

Utilize a one-way ANOVA when you have data related to one categorical independent variable and one quantitative dependent variable. The independent variable should encompass a minimum of three levels, which represents distinct groups or categories.

ANOVA helps in discerning whether the dependent variable exhibits variations based on the levels of the independent variable.

If you only want to compare two groups, use a t-test instead.

The ANOVA test assumes that your data:

1. Are independent
2. Are (approximately) normally distributed
3. Exhibit a similar level of variance within each group being compared, known as homogeneity of variance

# Mathmatical Foundation

<img src="https://cdn.testbook.com/images/seo/one-way-ANOVA-formulas.png" width="800" height="400">


Here's a way to express it:
F = MST/MSE
MST = SST/ p-1
MSE = SSE/N-p
SSE = ∑ (n−1)
s2

Here is a break down the variables:

F = Anova Coefficient

MSB = Mean sum of squares between the groups

MSW = Mean sum of squares within the groups

MSE = Mean sum of squares due to error

SST = total Sum of squares

p = Total number of populations

n = The total number of samples in a population

SSW = Sum of squares within the groups

SSB = Sum of squares between the groups

SSE = Sum of squares due to error

s = Standard deviation of the samples

N = Total number of observations

# ANOVA Function in Statistical Software:
You can use the command aov() to run an ANOVA.

In your analysis of support system influence the mental health outcomes of LGBTQIA individuals, if you choose to conduct an ANOVA using R, the code would resemble something similar to the following: anova_result <- aov(Mental_Health_Scores ~ Support_System, data = data)

summary(anova_result)

# Interpretting Test Results

| Source          | Df   | Sum Sq | Mean Sq | F value | Pr(>F)   |
|-----------------|------|--------|---------|---------|----------|
| Support_System  | 2    | 300.5  | 150.2   | 6.75    | 0.0012** |
| Residuals       | 147  | 1800.3 | 12.2    |         |          |

* Df (Degrees of Freedom):
  * Support_System: 2 degrees of freedom for the support system variable.
  * Residuals: 147 degrees of freedom for the error term.
* Sum Sq (Sum of Squares):
  * Support_System: 300.5, representing the sum of squared differences between group means.
  * Residuals: 1800.3, representing the sum of squared differences within each group.
* Mean Sq (Mean Square):
  * Support_System: 150.2, calculated as the sum of squares divided by the degrees of freedom.
  * Residuals: 12.2, representing the mean squared differences within each group.
* F value (ANOVA F-statistic):
  * 6.75, indicating the ratio of variance between group means to variance within groups. A higher F value suggests a higher likelihood of significant differences.
* Pr(>F) (p-value):
  * 0.0012, a small p-value (< 0.05) suggests that there are significant differences in mental health scores among different support systems.
    * The notation "**" indicates a high level of significance.

The p-value (0.0012) is less than the commonly used significance level of 0.05. Therefore, we reject the null hypothesis. This suggests that there are significant differences in mental health scores among the different support systems (family, friends, counseling). The one-way ANOVA results provide evidence to support the idea that the type of support system influences mental health outcomes in LGBTQIA individuals.

# Post-hoc Testing

ANOVA serves to identify differences among the levels of the independent variable, but it doesn't specify which differences are statistically significant. To display how the support system levels differ from one another, consider conducting a TukeyHSD (Tukey’s Honestly-Significant Difference) post-hoc test.

The R Code for the support system influence the mental health outcomes of LGBTQIA individuals would look similar to this:
tukey_result <- TukeyHSD(anova_result)<br>
print(tukey_result)

