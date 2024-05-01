# What is Unsupervised Learning?

Unsupervised learning comes into play when there's no labeled data or clear instructions for the computer. Instead, the computer independently seeks out underlying patterns or structures within the data without any external guidance.

## Example of Unsupervised Learning
Suppose a media company has gathered a vast amount of articles from different sources covering various topics such as politics, sports, technology, and entertainment. Without any predefined labels indicating the topic of each article, unsupervised learning algorithms can be utilized to cluster similar articles together based on their content and language patterns.

By applying unsupervised learning techniques, the algorithm can autonomously identify common themes or topics across the articles and group them accordingly. This clustering allows the media company to gain insights into the overarching trends and interests within their content repository. Subsequently, this information can be leveraged to enhance content categorization, recommend related articles to readers, or even identify potential gaps in coverage for specific topics.

# Unsupervised Learning Methods
Unsupervised learning is used for three main tasks:

1. Clustering
2. Association
3. Dimensionality reduction
  
In each of these tasks, we want to discover the inherent structure of our data for which no predefined categories or labels exist.

# Clustering

Clustering is a method in machine learning used to categorize unlabeled data according to their similarities or dissimilarities. This technique allows us to uncover patterns within the data even when we lack prior knowledge about what we're seeking.

An illustration of clustering is organizing customers into distinct segments based on shared characteristics, similar to finding natural groupings within the data. Think of clustering as sorting a stack of books into different genres or topics without any prior information about the books. Each book is examined individually, and if they exhibit similarities, they are grouped together.

Examples of clustering problems include:
* Recommendation systems: Grouping users or items with similar preferences or characteristics to make personalized recommendations for products, movies, or music
* Image compression: Reducing the size of an image by grouping similar pixels together
* Social network analysis: Identifying communities or groups within social networks based on connections and interactions between individuals
* Anomaly detection: Detecting abnormal behavior, such as network intrusions or suspicious bank transactions

# Association
Association focuses on discovering connections or relationships between items without predetermined labels or outcomes.

Association analysis is frequently applied to uncover intriguing associations or patterns, such as in market basket analysis where the objective is to identify items that are frequently purchased together, like products commonly found in a grocery store.

The outcome of association analysis typically takes the form of "if X, then Y," indicating that when item X is present (for example, cappuccino), there's a strong chance of item Y also being present (such as a muffin).

Examples of association problems include:

* Recommendation systems: Generating personalized recommendations by identifying correlations in purchases across different categories (like "frequently bought together" suggestions).
* Tailored marketing campaigns: Pinpointing specific combinations of products or services that are often associated with particular demographic groups (such as age, occupation, etc.).
* Medical analytics: Revealing correlations between symptoms, treatments, and patient outcomes to enhance diagnosis or treatment strategies.

# Dimensionality Reduction
  
Dimensionality reduction is a method employed in machine learning to manage extensive information effectively. Its purpose is to decrease the number of inputs or features while retaining crucial aspects of the data, thereby simplifying data handling and comprehension. For instance, it can refine images to enhance their appearance.

Examples of dimensionality reduction applications include:

* Image and video processing: Streamlining and enhancing images and videos, minimizing storage requirements while retaining essential visual details.
* Genetic research: Facilitating the analysis of vast genetic data sets. By simplifying the data's complexity, researchers can investigate and interpret genetic information more effectively.
* Document classification: Enhancing the usability of online journal databases. Significant features can be extracted from article content, enabling more efficient database organization.

# Example of an Unsupervised Learning Method

## Principal Component Analysis
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

# Advantages vs. Disadvantages

## Advantages
* Dimensionality Reduction: PCA reduces the number of variables in a dataset, simplifying analysis and visualization.
* Captures Variance: It captures the most important information in the data by retaining the components that explain the most variance.
* Noise Reduction: By focusing on the most significant components, PCA can help reduce noise in the data.
* Improves Model Performance: Lower-dimensional data can improve the performance and efficiency of machine learning models.

## Disadvantages
* Loss of Interpretability: Transformed components may not have clear interpretations as they are combinations of original features.
* Sensitivity to Scaling: PCA is sensitive to the scaling of data, so it's important to standardize the data before applying PCA.
* Assumption of Linearity: PCA assumes that the data has a linear relationship, which may not be true for all datasets.
* Loses Original Features: In the transformed space, the original features are lost, which may affect interpretability and decision-making.
* Not Ideal for Sparse Data: PCA may not perform well on sparse data, where there are many missing or zero values.


