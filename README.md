# Unsupervised-Learning: Clustering
Clustering for Machine Learning, Data Mining, Exploratory Data Analysis, Pattern Recognition


The objective of this  project is to implement different clustering methods on synthetic and real-world datasets, and subsequently validate the results using both external and internal validation techniques.

### Clustering Methods

1. K-means:
Used for partitioning datasets into clusters based on similarity.
Implementation: KMeans(n_clusters=k, random_state=seed)

2. Hierarchical Clustering:
Employed Agglomerative Hierarchical Clustering for creating tree-like structures of clusters.
Implementation: AgglomerativeClustering(n_clusters=k)

### Task 1: Clustering on Datasets
Datasets:
"Data1.csv", "Data2.csv", "Data3.csv", "Data4.csv", "Data5.csv"

Steps:

1. K-means and Hierarchical Clustering:
Apply K-means and hierarchical clustering methods to generate clusters for each of the five datasets.

2. Evaluation with External Validation Metrics:
Assess the performance of the clustering algorithms using external validation metrics mentioned below:

Adjusted Rand Index (ARI)

Normalized Mutual Information (NMI)

Fowlkes-Mallows Index (FMI)

3. Data Visualization:
Plot the data points in 2D or 3D for each dataset, coloring them according to the original class.
Plot the data points in 2D or 3D for each dataset, coloring them based on the class allocated by each clustering algorithm.

### Task 2: Clustering on World Indicators Dataset
Dataset:
"WorldIndicators.csv"

Steps:

1. K-means and Hierarchical Clustering:
Utilize K-means and hierarchical clustering methods to group similar countries based on selected attributes.

2. Internal Validation Metrics:
Report the cluster quality using internal validation metrics mentioned below:

  Silhouette Score

  Calinski-Harabasz Index

  Davies-Bouldin Index

4. Best Clustering Solution:
Identify and report the best clustering solution, providing a detailed list of all groups and the countries within each group.
5. Scatter Plots:
Generate three different scatter plots, choosing attributes such as "Life expectancy vs GDP," "Infant Mortality vs GDP," etc., and color the data points according to the clusters.

### Usage

1. Dataset Preparation:
Download and load the provided datasets ("Data1.csv," ..., "WorldIndicators.csv").

2. Task 1 Execution:
Run the code for K-means and hierarchical clustering on the synthetic datasets.
Evaluate clustering performance using external validation metrics.
Visualize the results with the specified plots.

3. Task 2 Execution:
Apply K-means and hierarchical clustering on the World Indicators dataset.
Assess the cluster quality using internal validation metrics.
Report the best clustering solution and provide details on each group.
Generate scatter plots to visually represent the clustering results.

### Dependencies

1. Python
2. Jupyter Notebooks (optional for code execution)
3. Required libraries: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, Matplotlib, Plotly, sklearn, scipy

Feel free to explore the code files for detailed implementation and results. If you encounter any issues or have questions, please refer to the documentation or contact the project contributors.

