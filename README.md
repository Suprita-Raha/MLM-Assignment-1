# MLM-Assignment-1

## Objective
The objective of this analysis is to cluster meteorological data to identify patterns and relationships between various weather features. Two clustering algorithms, K-Means and DBSCAN, are employed to group similar data points together.

## Methodology

### Data Preprocessing
The dataset is loaded, and every 10th row is sampled, resulting in a subset of 104,858 data points.
Seven features relevant to meteorological conditions, namely air_pressure, air_temp, avg_wind_direction, avg_wind_speed, max_wind_direction, max_wind_speed, and relative_humidity, are selected for analysis.

### K-Means Clustering
K-Means clustering with 12 clusters is applied to the selected features.
The cluster centers' coordinates are extracted, and each data point is assigned to one of the clusters.

### Cluster Visualization
Utility functions are created to visualize the clusters in parallel coordinate plots.
Three distinct visualizations are generated for dry days, warm days, and cool days, showcasing the behavior of the clusters with respect to humidity and temperature.

### Silhouette Score Calculation
The Silhouette Score is computed to evaluate the quality of the K-Means clustering results. The obtained score is 0.2349.

### Comparison with DBSCAN
DBSCAN clustering is performed with an epsilon value of 0.5 and a minimum sample size of 5.
The size, memory usage, and time taken for both K-Means and DBSCAN clusters are compared.

### Composition of Clusters
The composition of each cluster in terms of the number of data points is analyzed for both K-Means and DBSCAN.

(Source: Github MUHAMMAD MAAZ)
