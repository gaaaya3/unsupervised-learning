# unsupervised-learning
http://localhost:8888/lab/tree/unsupervised%20learning.ipynb

A).KMeans clustering:
KMeans clustering is an unsupervised learning algorithm that partitions a dataset into K distinct clusters based on feature similarity. The algorithm works as follows:
a)Initialize K centroids randomly.
b)Assign each data point to the nearest centroid.
c)Recalculate the centroids as the mean of all points assigned to each cluster.
d)Repeat steps 2 and 3 until convergence (when assignments no longer change).

Suitability for the Iris Dataset:
KMeans is suitable for the Iris dataset because:
The dataset contains continuous numerical features (sepal length, sepal width, petal length, petal width) that can be clustered based on distance metrics.
The natural grouping of species in the dataset can be effectively captured by KMeans as it tends to form spherical clusters.

B)Hierarchical Clustering:
Hierarchical clustering builds a hierarchy of clusters either through:
1.Agglomerative approach: Starting with individual points and merging them into larger clusters.
2.Divisive approach: Starting with one cluster and dividing it into smaller clusters.
For this assessment, we will use agglomerative hierarchical clustering.

Suitability for the Iris Dataset:
Hierarchical clustering is suitable for the Iris dataset because:
   It does not require specifying the number of clusters in advance.
   It provides a dendrogram that helps visualize how clusters are formed at different levels of similarity.
