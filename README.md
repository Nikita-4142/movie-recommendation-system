Data Set 
The data set used for this notebook is 1M ratings data set from movielens.This contains 1M ratings of movies from 7120 movies and 142025 users. This data set includes:
movield
userld
rating

In addition a data set of movies includes the movies name and genres.

movield
title
genres

The dataset can be found here:https://github.com/Nikita-4142/movie-recommendation-system.git

Approaches Used:
Non Personalised Recommendations

This type of recommendations are simple but very useful.Because they solve the cold start problem for users. That is without knowing anything about the user, we can do some recommendations to the user. After getting some reviews from the user or getting some additional information about the user , We can switch some of the more advanced model which are described below.

In the notebook, formula given by IMDB was used to calculate the best movies according to various genres and they can be recommended to any new user.

Most Commonly watched movie by people who watched X were

This recommender takes the approach of looking at all users who have watched a particular movie and then counts the returns the most popular movie returned by that group.

Finding similar movies

without taking content into account (just based on ratings)

Here just based on the ratings of the users for different movies,we use K nearest neighbours algorithm to find the movies which are similar.

With taking Content into account

Here we just information about the movies, in the case the information of genres to predict the most similar movies.

Deep Learning Methods

Matrix Factorisation based on Deep learning
Matrix Factorisation based on Deep learning with non negative embeddings.
Advanced neural network with different number of embeddings for both and movies.

Required Tools

Numpy
Pandas
python3
Matplotlib
Seaborn
