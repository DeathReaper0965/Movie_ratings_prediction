# Scikit_Test

Movie Rating prediction...

Kaggle Dataset: https://www.kaggle.com/PromptCloudHQ/imdb-data/data

## Feature generation
 
Casts: https://archive.ics.uci.edu/ml/machine-learning-databases/movies-mld/data/casts.html

Awards_types(dataset A): https://archive.ics.uci.edu/ml/machine-learning-databases/movies-mld/data/awtypes.html

Actors(dataset A): https://archive.ics.uci.edu/ml/machine-learning-databases/movies-mld/data/actors.html

Movies(dataset M): https://archive.ics.uci.edu/ml/machine-learning-databases/movies-mld/data/main.html

Used Levenshtein distance to match movie names in Kaggle Dataset with movies provided in other datasets
Persisted the lavestein distance cutoff scores to 80(for better recommendations)

## Models Implemented:
1. SVM for multiclass prediction
2. LARS Lasso

## Model comparision metrics used: 
1. ROC-AUC Curve
2. MAPE (LARS)
3. R2 (LARS)
