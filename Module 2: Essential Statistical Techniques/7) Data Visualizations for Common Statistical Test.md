# Importance of Data Visualizations in Research

Incorporating visualizations in research is crucial for enhancing data interpretation and communication. Visual representations such as graphs and charts enable researchers to discern patterns and trends within their data, this facilitates clearer insights and compelling presentations. To create these visualizations, researchers should develop a code tailored to their specific data and analysis needs by utilizing programming languages like Python or R to create customizable and reproducible graphs.

In this module, we will explore various types of graphs commonly used in research to visualize data effectively. 


# Summary Statistics Tables
Summary statistics tables are used to present key descriptive statistics that summarize the characteristics of a dataset. These tables typically include measures such as the mean, median, mode, standard deviation, minimum, maximum, and quartiles for numerical variables, as well as frequencies and percentages for categorical variables. Summary statistics tables themselves do not dictate a specific statistical test but provide crucial information that guides the selection of appropriate tests based on the research question and the nature of the data.

<img width="450" alt="Summary Statistics Table" src="https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/53201b10-93bd-44fd-b9ba-16e14dff8b87">

# Contingency Tables
Contingency tables, also known as cross-tabulation tables or two-way tables, are used in statistics to summarize and analyze the relationship between two categorical variables. These tables display the frequencies or relative frequencies of observations falling into various categories for each variable. The appropriate statistical test for analyzing data in a contingency table depends on factors such as study design, sample size, and variable characteristics. However, common tests include the chi-square test for independence, Fisher's exact test for small samples or low expected cell frequencies, and McNemar's test for paired categorical data.

For example: A Contigency table could be used to explore the relationship between Breast and Ovarian cancer and display the frequency of observation falling into each category for each variable.

<img width="550" alt="Contingency Table" src="https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/92bbea4e-4166-4b62-97e8-4906112d2576">


# Bar Chart
For tests where both the variables are categorical like chi-square test and fisher-exact test, bar-charts are most commonly used.

For example: A bar chart could be used to visualize the frequency of car brands in a class of students according to gender
<img src="https://datatab.net/assets/tutorial/fig/multiBarChart.png" width="650" height="400">

## Bar chart vs. Histogram
A bar chart and a histogram are both types of graphical representations of data, but they are used to display different types of information.

A bar chart is used to represent discrete data, where the data is divided into separate categories. The height of each bar represents the frequency or quantity of the data that falls into that category.

A histogram, on the other hand, is used to represent continuous data, where the data is divided into a set of bins or intervals. The height of each bar represents the frequency or quantity of the data that falls into that bin or interval. The bars in a histogram are usually adjacent and there is no space between them.

The main difference between a bar chart and a histogram is the type of data they represent and the way the data is divided and displayed. Histograms are used for metric variables such as salary or age, and bar charts for ordinal or nominal variables such as gender or school grade.

# Histogram

A histogram is a graphical representation of data distribution. It uses bars of varying heights to show the frequency of data items in successive numerical intervals. The height of a bar corresponds to the frequency of data in that range.

For example: A histogram would be used to visualize the results of a exam scores of students.
<img width="650" alt="Histogram" src="https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/794bb80c-f6d9-4535-98d5-6648dd9b264d">


# Correlation
For Pearson correlation, where both the variables are continuous, scatter plot with regression line is best to visualize the data.

For example: A scatterplot with a regression line can be used to visualize the points of individuals asked for their weight and height.

<img width="600" alt="Scatterplot" src="https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/6d6de96a-2b13-4494-bf7a-7bbedaa47010">


# Boxplots
Box-plot is also commonly used for visualizing t-test and one-way ANOVA. Box plots are charts used to represent distributions of data. They provide a visual summary of the data by presenting important statistical measures such as median, quartiles, and outliers in a single graph. Since t-test (independent t-test and paired t-test) and one-way ANOVA are used to assess the mean (± SD) difference between the groups, a boxplot with error bars is the best for representing these tests. In addition, Mann-Whitney test, paired samples Wilcoxon test and Kruskal-Wallis test are non-parametric alternatives of independent t-test, paired t-test and one-way ANOVA respectively. In these tests, variables are usually expressed as median (interquartile range); therefore boxplots are a good data visualization technique for these tests. In the box-plot, we can visualize median, interquartile range (i.e. 1st quartile and 3rd quartile), minimum and maximum. Since non-parametric tests like Mann-Whitney test, paired samples Wilcoxon test and Kruskal-Wallis test are used to assess difference in spread of variables between groups, box-plot is the best option.

For example: A boxplot could be used to observe the Body-Mass Index amongst genders
<img width="600" alt="Boxplot2" src= "https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/4cb70754-9939-49c2-95b9-9df9f92635f3">

# Line Charts

Line charts are useful for visualizing trends and changes over time. In a line chart, time or the other continuous variable is plotted on the horizontal axis, while the values of the data to be illustrated are plotted on the vertical axis.

For example: A line chart could be used to visualize the IMR (per 1000 live births) in India from 2010 to 2019.
<img width="600" alt="Scatterplot" src="https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/8570bda8-e309-4094-9e05-676aad02d5ad">

# Heat Maps
Heat maps are graphical representations used to visualize the magnitude of values within a matrix or table of data. They are particularly useful for displaying complex datasets or patterns by using color gradients to represent variations in the data. Heat maps themselves are not used as the basis for statistical tests. Instead, they are a visualization tool used to explore and present data. Researchers can use heat maps for data exploration, genomic data analysis, spatial analysis, cluster analysis, ANOVA or MANOVA, etc.
