# k-means-clustering-for-Fifa_21-players
# Project Overview
In this project, I used k-means clustering (an unsupervised machine learning technique) to find patterns in Fifa 2021 players data, using python and pandas and thereafter comparing it to reference implementation from scikit-learn.
# Project Steps
Write out pseudocode for the algorithm
Code the k-means algorithm
Plot the clusters from the algorithm
Compare performance to the scikit-learn algorithm
# K-means overview
K-means allows data points to cluster which enables the algorithm to find patterns in the data to analyze it more effectively. K-means is an iterative algorithm, it will converge to the optimal clustering over time.
# The following steps was used to run the k-means clustering:
1.	Specify the number of clusters (k).
2.	Randomly initialize the centroid for each cluster (the data point at the center of the cluster).
3.	Find the closest centroid to each data point by determining which data points belong to which cluster.
4.	Update the centroids based on the geometric mean of all the data points in the cluster.
5.	Run 3 and 4 until the centroids stop changing (iteration).
# Data
Data from Kaggle was used for this project and can be found here https://www.kaggle.com/datasets/stefanoleone992/fifa-22-complete-player-dataset  players_21.csv
