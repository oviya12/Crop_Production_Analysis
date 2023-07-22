This analyzation on crop production uses K-Means clustering algorithm.
DATASET is taken from kaggle (Crop statistics FAO - All countries)

Then the dataset is cleaned by removing unnecessary colums and missing values,

Then the data is visualized to process the insights, and then built kmeans clustering model

K-means is one method of cluster analysis that groups observations by minimizing Euclidean distances between them
k-means clustering aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean, serving as a prototype of the cluster. This results in a partitioning of the data space into Voronoi cells.
Given a set of observations (x1, x2, …, xn), where each observation is a d-dimensional real vector, k-means clustering aims to partition the n observations into k groups G = {G1, G2, …, Gk} so as to minimize the within-cluster sum of squares (WCSS) defined with the formula −  argmin∑i=1k∑x∈Si∥x−μi∥2

Then with the help WCSS, the data are grouped into clusters, which helps in analyzing huge data and get insights quickly
