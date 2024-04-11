# What is Principal Component Analysis (PCA)?

Principal Component Analysis is a dimensionality reduction technique that transforms data into a new coordinate system. It identifies the directions (principal components) that maximize the variance in the data.
PCA reduces the number of variables while retaining as much information as possible.

# When to Use

A Principal Component Analysis is use when you want to reduce the dimensionality of a dataset to make it easier to analyze and visualize. It is also useful for handling multicollinearity (highly correlated features) in regression models.
It is ideal for data compression, noise reduction, and data preprocessing before applying machine learning algorithms. It is also applicable when you want to identify patterns or trends in the data by observing how the data points cluster around certain axes and suitable for tasks like feature extraction and understanding which features contribute most to data variance.

# Example
Werner and Friedrich (2014) provided an effective example of Principal Component Analysis using fish as the subject.

 <img width="650" alt="SVM" src="https://devopedia.org/images/article/139/9153.1547301619.png">


In this example, we can represent the shape of a fish using two dimensions: height and width. However, these two dimensions are not independent and are strongly correlated. Knowing one allows us to predict the other. This suggests that the shape of a fish can be described using a single component but does not mean we can disregard either height or width. Instead, we convert the two original variables into two orthogonal (independent) components that offer an alternative complete description. The first component (represented by a blue line) accounts for most of the data's variation. The second component (dotted line) captures the remaining variation. Both components are based on the original height and width.

The first component can be thought of as the line of best fit that minimizes information loss. Alternatively, it maximizes variance, aiming to explain as much variation in the dataset as possible.
