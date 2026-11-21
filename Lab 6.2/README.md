Main Exercise. Comparing Three Models on Precision, Recall, and F1
Three genre-prediction models have already been run for you. Their outputs are in the course files under module_07/exercises/:

prediction_model_01.csv
prediction_model_02.csv
prediction_model_03.csv
Each file has one row per film with the following columns:

imdb_id — the film’s IMDB identifier
predicted — the single genre the model predicted
actual genres — the list of genres actually tagged on that film
correct? — 1 if the predicted genre appears in the actual genre list, 0 otherwise
Note that ground truth is multi-label (a film can be both a Drama and a Romance) while each model emits a single label. A prediction counts as correct when the predicted genre is among the film’s actual genres.

Load all three files. Report the overall accuracy of each model — the fraction of rows where correct? is 1.
For each model, compute per-genre precision, recall, and F1. Treat each genre as its own binary problem: for genre g, a true positive is a film predicted g where g is in its actual genres; a false positive is a film predicted g where it is not; a false negative is a film whose actual genres include g but which the model predicted as something else.
Build a table, for each model, of the ten most frequently predicted genres with their precision, recall, and F1.
Compute macro-averaged F1 for each model (the unweighted mean of per-genre F1). Compare it to the overall accuracy from step 1. Where do the two rankings disagree, and why?
Identify one genre where a model has high precision but low recall, and one where it has high recall but low precision. Explain in one or two sentences what each model is doing wrong in each case.
Which of the three models would you ship, and why? Your answer must cite specific metrics, and it should not simply be "the one with the highest accuracy."
