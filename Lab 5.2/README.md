Main Exercise. Evaluating Hyperparameter Performance
* Download the scaffolding code: kNN Train/Test Scaffold
* You will need to modify this scaffolding to turn `training_ids` and `testing_ids` into X_train/y_train and X_test/y_test matrices/label vectors, as the SKlearn classes' `.fit()` function expects an `X` matrix of features and a `y` vector of labels. The `X` matrix should be a matrix where rows represent films and columns represent actors, and the `y` vectors are the genre tags of the films. Note that you may have to duplicate rows such that each genre tag a movie has gets its own row.
* Split your data into an 80/20 train/test split.
* Use the decision tree classifier from SciKit-learn to classify movie genres in your test set for different values of `max_depth`.
* Initialize the DecisionTreeClassifier() with different values of `max_depth`, starting at 1 and going to 10.
* For each value for depth, evaluate accuracy of the trained model on both your training set and your test set, where a prediction is correct if the predicted genre exists in the actual set of genres for a film
* What is the relationship between max depth and accuracy?
