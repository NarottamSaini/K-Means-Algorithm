Module: Machine Learning 3

# K-Means-Algorithm

Dataset Description:

Instances in this dataset contain audio features extracted from 1059 wave files. The
data is labelled based on the geographical origin of music (33 classes/countries/areas).
Note: Use the class labels only to verify the performance of the clustering.
116 columns are audio features of the track, and the last one columns are the origin of
the music.
Source : http://archive.ics.uci.edu/ml/datasets/geographical+original+of+music

Task 1:
The task is to perform clustering on the given dataset using k-means algorithm and
experiment with the following specifications.
Initialization: Random
Distance measure: Euclidean Distance
Evaluation metrics: Rand Index, SSE (same as WCSS)
Stopping Criteria: Your choice (simple loop with maximum 200 iterations is
enough)
You should Plot the Rand Index and SSE with the 8 different k values, of your choice.

Table1: K-means clustering.
Number of
cluster
Rand Index SSE
K =
K =
K =
K =
K =
K =
K =
K =
What you think is the best k for this dataset? Give justification about your choice.

Task 2:
The task is to use PCA for dimensionality reduction and visualization. For your chosen
k, do the following:
a) Project your data into 2D plane using PCA and color code the clusters. Use
scatter plot.
b) Choose the following number of components for PCA: 2, 4, 8, 16, 32. Do the
clustering on the reduced dataset and compute the Rand index.
Table 2: K-means clustering after dimensionality reduction
Number of components in PCA
Rand Index
(using chosen k)
N = 2
N = 4
N = 8
N = 16
N = 32
