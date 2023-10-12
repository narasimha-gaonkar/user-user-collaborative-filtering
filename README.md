# User-User Collaborative Filtering

The code aims to provide movie recommendations based on user-user similarities.

## Approach
This code does not make use of any machine learning algorithms, it relies on fundamental mathematical and statistical techniques, such as calculating user averages, deviations, and user weights, to make recommendations.

## Dataset:
The datasets contains ratings and free-text tagging activities from MovieLens, a movie recommendation service. It contains 20000263 ratings and 465564 tag applications across 27278 movies.
[Dataset Link](https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset)

## Steps Performed:
  1. Loaded and preprocessed the data movie dataset.
  2. Shriknied Dataset to subset of Most repitatitaive users (N = 10000) and movies (M = 2000).
  3. Calculated user averages and deviations.
  4. Calculated Pearson correlation weights between users.
  5. Creatrd a list of neighbors for each user (K = 25).
  6. Implemented a prediction function based on the calculated weights and deviations.
  7. Calculated mean squared errors for both the training and test sets.

