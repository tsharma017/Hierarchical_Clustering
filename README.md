# Hierarchical_Clustering

Hierarchical clustering is an unsupervised machine learning algorithm used for grouping data points into clusters without requiring a predefined number of clusters.

✅ Key Idea:
It builds a tree-like structure (dendrogram) to show how clusters are formed at different levels of similarity.


Types of Hierarchical Clustering
There are two main types of hierarchical clustering:

1. Agglomerative Hierarchical Clustering (Bottom-Up Approach)
Starts with each data point as its own cluster.
Step by step, similar clusters are merged together.
The process continues until one single cluster remains.
✅ This is the most commonly used method

2. Divisive Hierarchical Clustering (Top-Down Approach)
Starts with one large cluster containing all data points.
Step by step, the cluster splits into smaller clusters.
The process continues until each point is its own cluster.
❌ Less commonly used because it is computationally expensive.

3. How Agglomerative Hierarchical Clustering Works
Calculate Distances → Compute the similarity (e.g., Euclidean distance) between all points.
Merge Closest Clusters → Combine the two most similar clusters.
Update Distance Matrix → Recalculate distances between new clusters and remaining ones.
Repeat Until One Cluster Remains → Continue merging until only one cluster exists.
