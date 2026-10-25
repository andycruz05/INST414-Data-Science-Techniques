Main Exercise. Clustering Actors in the Actor-Genre Matrix
This exercise builds on prior exercises, where we have extracted a data matrix of actors and the genres in which they have starred. We will use that data to extract a set of actor clusters from the data, using k-means.

* Download this CSV fileLinks to an external site. from GitHub (also available on Canvas in Exercises/data)
* Use the CSV file to create a data frame, where each row corresponds to an actor, each column represents a genre, and each cell captures how many times that row’s actor has appeared in that column’s genre
* Using this data frame as your data matrix, use the k-means package in scikit-learn sklearn.cluster.KMeansLinks to an external site. to extract k=8 clusters from the data.
* Initialize the model using KMeans(n_clusters=8)
* Fit this model to the data and get cluster predictions back using the model.fit_predict()
* Print the number of actors per cluster you have found
* For each cluster, print a random sample of 5 actors in that cluster to get a sense of who is in each cluster
* One easy way to do this sampling is to use Pandas to create a data frame with the predicted cluster labels as a column and the actor IDs from your original actor x genre matrix as the index. Then you can use df.groupby("cluster") to get sub-data frames for each cluster.
