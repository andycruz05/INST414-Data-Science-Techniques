Main Exercise. Finding Similar Actors based on Genre
* Download imdb_movies_2000to2022.prolific.jsonLinks to an external site. from GitHub (also available on Canvas in Exercises/data)
* Create a data frame, where each row corresponds to an actor, each column represents a genre, and each cell captures how many times that row’s actor has appeared in that column’s genre
* Using this data frame as your “feature matrix”, select an actor (called your “query”) for whom you want to find the top 10 most similar actors based on the genres in which they’ve starred
* As an example, select the row from your data frame associated with Chris Hemsworth, actor ID “nm1165110”, as your “query” actor
* Use sklearn.metrics.DistanceMetricLinks to an external site. to calculate the euclidean distances between your query actor and all other actors based on their genre appearances
* Print a list of the top ten actors most similar to your query actor using Euclidean distance
