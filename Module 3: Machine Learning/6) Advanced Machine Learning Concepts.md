
<img width="800" alt="Machine Learning Overview" src="https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/def3c846-e3de-4424-8c89-ef967abc9ad5">


### Support Vector Machines (SVM): 
A Supervised learning algorithm used for classification and regression analysis. This concept constructs a hyperplane in a high-dimensional space to separate classes.

* Use when dealing with high-dimensional data or when the number of dimensions is greater than the number of samples. This is also effective for both linearly separable and non-linearly separable dataset.
<img width="350" alt="SVM" src="https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/c7a36de7-5fc9-4128-89c0-c5c0513dfb69">


### Linear Discriminant Analysis:

A Supervised learning algorithm used for classification and dimensionality reduction. It seeks to find the linear combination of features that characterizes or separates two or more classes.
* Useful when the goal is to classify observations into distinct categories based on predictor variables and when the assumption of normality holds for the data distribution.

  <img width="450" alt="LDA" src="https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/ce58aeed-d8f5-4beb-a999-cef1c588c2b1">

### Naive Bayes:

This is Supervised learning algorithm which is probabilistic classifier based on Bayes' theorem. This concept assumes that the presence of a particular feature in a class is independent of the presence of other features.
* Ideal for text classification tasks such as spam detection, sentiment analysis, or document categorization and works well with large feature spaces and relatively small datasets.

  <img width="450" alt="LDA" src="https://jakevdp.github.io/PythonDataScienceHandbook/figures/05.05-gaussian-NB.png">

### Nearest Neighbor:

A Supervised learning algorithm that stores all available cases and classifies new cases based on a similarity measure. The new case is assigned to the class most common among its k nearest neighbors.
* Useful when the decision boundary is irregular or difficult to model with other algorithms and appropriate for both classification and regression tasks.

 <img width="500" alt="KNN" src="https://miro.medium.com/v2/resize:fit:640/format:webp/0*OltO4Txr-D0lPWNL.png">

### Neural Networks:

A Supervised learning algorithm which has computational models inspired by the structure and function of the human brain. This is composed of interconnected nodes (neurons) that process information using activation functions.
* Effective for tasks involving complex patterns or relationships in data. Suitable for image recognition, natural language processing, and other tasks where feature engineering is challenging.

 <img width="500" alt="Neural Network" src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/20230602113310/Neural-Networks-Architecture.png">

### Decision Trees:

A Supervised learning algorithm which has a decision support tool that uses a tree-like graph of decisions and their possible consequences. Each internal node represents a "test" on an attribute, each branch represents the outcome of the test, and each leaf node represents a class label.
* Useful for understanding and visualizing decision-making processes. Applicable when dealing with both numerical and categorical data.

  <img width="500" alt="Decision Trees" src="https://miro.medium.com/v2/resize:fit:1400/1*ER9uqmxlsLue-o3eUyMpHA.png">

### Ensemble Models:

A Supervised learning algorithm that uses techniques that combine multiple individual models to improve predictive performance. Examples include Random Forest, Gradient Boosting Machines (GBM), and AdaBoost.
* Recommended when individual models exhibit high variance or bias. Useful for improving overall predictive performance and generalization.

  <img width="550" alt="Ensemble Models" src="https://miro.medium.com/v2/resize:fit:2000/1*T8NnkvKIRmZT38EZ9GDoZg.png">
  
### Non-linear Regression:

A Supervised learning algorithm that uses regression analysis where the relationship between the independent variables and the dependent variable is modeled as non-linear. Uses methods like polynomial regression, exponential regression, or spline regression.
* Suitable when the relationship between independent and dependent variables is non-linear. Useful for modeling phenomena where simple linear models are inadequate.

  <img width="500" alt="Ensemble Models" src="http://www.sthda.com/english/sthda-upload/figures/machine-learning-essentials/009-polynomial-and-spline-regression-scatter-plot-1.png">
  
### Linear Regression:

A Supervised learning algorithm that uses a linear approach to modeling the relationship between a dependent variable and one or more independent variables. It assumes a linear relationship between the independent and dependent variables.
* Appropriate for understanding the relationship between dependent and independent variables when it is assumed to be linear. Useful for prediction and inference tasks.

  <img width="500" alt="Linear Regression" src="https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/774fdb83-3c09-46d8-a1aa-40aaa5a05e95">


### Random Forest

A Supervised learning algorithm used for classification and regression tasks. It builds multiple decision trees during training and merges their predictions to make a final prediction.
The algorithm introduces randomness in two ways: selecting a random subset of features to split each node and bootstrapping the training data.

* Useful when you want to measure feature importance, as the model provides insights into the impact of different features on predictions.

<img width="450" alt="HMM" src="https://cdn.corporatefinanceinstitute.com/assets/random-forest.png">

### K-means:

An Unsupervised learning algorithm used for clustering. Divides a set of samples into clusters of approximately equal variance, minimizing a criterion known as the inertia or within-cluster sum-of-squares.
* Suitable for partitioning data into distinct clusters. Effective for exploratory data analysis and when the number of clusters is known or can be estimated.

<img width="520" alt="K-Means" src="https://miro.medium.com/v2/resize:fit:1080/0*KfNpMUTtyCNQwYnp.png">

### Hierarchical Clustering:

An Unsupervised learning clustering algorithm that builds a hierarchy of clusters. This can be agglomerative (bottom-up) or divisive (top-down).
* Appropriate when the data has a nested structure or when the number of clusters is not known prior. Useful for creating a dendrogram to understand the relationships between clusters.

<img width="774" alt="Hierarchical Clustering" src="https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/1f978097-be3e-4c93-9c1f-fbfbaacf9f2c">


### Gaussian Mixture Models:

An Unsupervised learning algorithm with probabilistic model used for representing the presence of subpopulations within an overall population. This Assumes that all data points are generated from a mixture of several Gaussian distributions.
* Recommended when the data is assumed to be generated from multiple Gaussian distributions. Useful when dealing with data that may exhibit overlapping clusters or mixed memberships.

<img width="500" alt="Hierarchical Clustering" src="https://i.stack.imgur.com/s3QiK.png">

### Hidden Markov Models (HMM):

An Unsupervised learning algorithm used to model sequences of observable events (e.g., speech, handwriting). Consists of states, transitions between states, and emission probabilities associated with each state.
* Suitable for modeling sequential data with probabilistic dependencies between observations. Useful for tasks such as speech recognition, bioinformatics, and time series analysis.
  
<img width="400" alt="HMM" src="https://github.com/StefaneeT/RA-Statistics-Course/assets/89051155/f03fc0ca-e9d6-4da4-9532-b46d2ed60ffb">



