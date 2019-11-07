# Unsupervised_Learning_3_Clustering_evaluation_2(standerisation)

In this example I have worked on the fish data set containing the measurements (such as weight in grams, length in centimeters, and the
percentage ratio of height to length, have very different scales) (.csv file is in the folder). 
This file has six dimenssional (with four species). However no. of clustering can be 6 or less than 6. Therefore, 
first I have learned how to choose a good number of clusters for a dataset using the k-means inertia graph. 
Using this information cluster the fish samples into four clusters, and compare the clusters to the fish species using a cross-tabulation.
I have found that cross-tabulation reult is not promissing. I have further investigated and found very unstable variances. Therefore,
standerisation applied on the data set that results in an excellent outcome.
