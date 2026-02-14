## K-Means vs K-Medoids Clustering – Wine Dataset

## Purpose of the Lab

This lab aimed to apply and compare the K-Means and K-Medoids clustering algorithms using the Wine Dataset from sklearn. Clustering performance was evaluated using the Silhouette Score, Adjusted Rand Index (ARI), and visual interpretation.

## Key Insights

* Both algorithms successfully identified three clusters that correspond to the three wine classes.
* K-Means produced a Silhouette Score of 0.2849 and an ARI of 0.8975.
* K-Medoids produced a Silhouette Score of 0.2676 and an ARI of 0.7411.
* K-Means generated more compact clusters with a spherical structure.
* K-Medoids demonstrated increased robustness and stability, attributable to the use of medoid-based cluster centers.

## Observations

K-Means exhibited marginally superior cluster compactness, whereas K-Medoids offered more interpretable cluster representatives by selecting actual data points as medoids.

## Challenges Faced

* The implementation of K-Medoids required the installation of the sklearn-extra package.
* Choosing dimensionality reduction (PCDimensionality reduction using Principal Component Analysis (PCA) was selected to enhance visualization clarity. It is suitable for large datasets with clear cluster separation, whereas K-Medoids is preferable when robustness to outliers is required.


