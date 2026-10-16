Main Exercise. Normalizing Actor-Genre Matrix
This exercise builds on the last exercise but asks the student apply L1 normalization to the rows of the matrix. 

* Download imdb_movies_2000to2022.prolific.jsonLinks to an external site. from GitHub (also available on Canvas in Exercises/data)
* Create a data frame, where each row corresponds to an actor, each column represents a genre, and each cell captures how many times that row’s actor has appeared in that column’s genre
* Using this data frame as your “feature matrix”, for every row in the matrix, apply L1 normalization. That is, calculate the sum of each row, and divide every element of that row by this sum. Store this normalized matrix as a new object. If you apply `sum(axis=1)` to the normalized matrix, all actors should now have a value of 1.Using this L1-normalized data frame as your new feature matrix, select an actor (called your “query”) for whom you want to find the top 10 most similar actors based on the genres in which they’ve starred
* As an example, select the row from your data frame associated with Chris Hemsworth, actor ID “nm1165110”, as your “query” actor
* Use sklearn.metrics.DistanceMetricLinks to an external site. to calculate the Euclidean distances between your query actor and all other actors based on this normalized matrix of genre appearances.
* Print a list of the top ten actors most similar to your query actor using Euclidean distance
* Describe how this list has changed compared to Cosine Similarity.
