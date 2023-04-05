# ML_CA06
# This aiisgnment is easy on coding and model, but the main point is how to write the analysis of our finding.
# First step, just follow the requirement of 1 to make the data reading, handling missing value and visualization by histograms and boxplots, I reommend to do both plots  for all features.
# Then in step2, Use from sklearn.preprocessing import StandardScaler to make standardization for "Annual Income (k$)", "Spending Score (1-100)"
# Create a new DataFrame with "Annual Income (k$)", "Spending Score (1-100)"
# In step 3,  Use the Silhouette Method to determine and make the plot of Silhouette Score, so we can see the optimal number of clusters is 5, easy right?
# just train the K-means model with both features and the the optimal number of clusters 5
# then kmeans.labels_ is vert important, because After training the KMeans model with the optimal number of clusters, the kmeans.labels_ attribute contains the cluster assignment for each data point in the original data. This allows us to easily visualize and analyze the clusters based on their assigned labels.
# finally, use sns.scatterplot to make the clustering polt, we can see I got the whole clustering distribution for the both features.
# So, this could explain a strategic analysis for customer for this mall.
