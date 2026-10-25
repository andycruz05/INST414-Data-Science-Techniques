Main Exercise. k Selection via Elbow Method
K-Means requires setting a value for k, so how do you do that? In this exercise, we'll use inertia and the "elbow method" to find a reasonable value for k.

* Using this CSV fileLinks to an external site. from GitHub (also available on Canvas in Exercises/data), create a dataframe of actors and their genres.
* Starting with k=2, fit a k-means clustering model and record the `.inertia_` parameter of the fitted model.
* Repeat step 2 for k from 2 to 30, recording the `.inertia_` value for each k.
* Plot the inertia values from k=2..30 and use this plot to select a value for k.
