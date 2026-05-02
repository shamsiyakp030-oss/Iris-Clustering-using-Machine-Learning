# Iris Clustering Project
## About the Project

This project explores how machine learning can group similar data points without using predefined labels. Using the Iris dataset, clustering techniques are applied to discover natural patterns among flower measurements.

Instead of predicting categories, the focus here is on identifying hidden structures in the data.

## What This Project Does
Groups Iris samples based on feature similarity
Applies two clustering approaches:
KMeans
Hierarchical Clustering
Visualizes how clusters are formed
Compares the behavior of both algorithms
## Dataset Information

The dataset comes from the built-in sklearn library and contains:

150 observations
4 numerical features:
Sepal length
Sepal width
Petal length
Petal width

The species column is intentionally removed to simulate a real clustering scenario.

## Approach
🔹 Data Preparation
Loaded the dataset using sklearn
Removed the target label
Scaled features to ensure fair distance calculations
🔹 KMeans Clustering
Used the elbow method to determine the ideal number of clusters
Built the model with 3 clusters
Assigned each data point to a cluster
Visualized the cluster distribution
🔹 Hierarchical Clustering
Generated a dendrogram to understand cluster formation
Applied agglomerative clustering
Compared results with KMeans
## Key Observations
The data naturally forms three groups
Both algorithms produced similar clustering patterns
KMeans was faster and more straightforward
Hierarchical clustering gave better insight into cluster relationships
## What I Learned
Importance of feature scaling in clustering
How different clustering methods behave on the same dataset
How to interpret dendrograms and cluster plots
Practical use of unsupervised learning techniques
## Project Files
iris_clustering.ipynb → Complete implementation
README.md → Project explanation
images/ → Visual outputs (optional but recommended)
## How to Run
Clone the repository
Install required libraries
Open the notebook and run all cells
## Future Scope
Try other clustering algorithms like DBSCAN
Use PCA for dimensionality reduction
Evaluate clustering performance using metrics

## video presentation


## Author

Shamsiya kp
Aspiring Data Analyst / Data Science Learner
