# Task-8-Clustering-with-K-Means.
1.Dataset Used:I used the famous Iris flower dataset which has 4 features like petal length/width etc.

2.Goal: To group similar flowers into clusters using KMeans (unsupervised learning).

3.Tools: sklearn, pandas, matplotlib, seaborn.

4.PCA Visualization: Since the data has 4 features, I used PCA to shrink it to 2D for easy plotting.

5.Elbow Method: Tried different values of K (number of clusters) to find the best one. Chose K=3 based on the plot.

6.Model Fit: Fitted the KMeans model and got cluster labels for all the samples.

7.Plotting: Used those labels to color-code the clusters and plotted them using PCA components.

8.Evaluation: Silhouette score was calculated to see how well the clusters are separated. Higher score = better.

9.Bonus: Compared actual species vs predicted clusters just for curiosity (though clustering doesn’t use target labels).

10.Saved Result: Exported the final data with clusters to a CSV for future use.
