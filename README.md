# ClassifySong Genres from Audio Data
Project Classify Song Genres from Audio Data
- Topic : Machine Learning
- Programming language : Python
- Packages : Pandas, Seaborn
- Algorithms used :Principal Component Analysis,Logistic Regression, Decision Trees

## Introduction  : 
Over the past few years, streaming services with huge catalogs have become the primary means through which most people listen to their favorite music. But at the same time, the sheer amount of music on offer can mean users might be a bit overwhelmed when trying to look for newer music that suits their tastes.

For this reason, streaming services have looked into means of categorizing music to allow for personalized recommendations. One method involves direct analysis of the raw audio information in a given song, scoring the raw data on a variety of metrics. Today, we'll be examining data compiled by a research group known as The Echo Nest. Our goal is to look through this dataset and classify songs as being either 'Hip-Hop' or 'Rock' - all without listening to a single one ourselves.


## Data :
we'll be examining data compiled by a research group known as The Echo Nest. A song is about more than its title, artist, and number of listens. We have another dataset that has musical features of each track such as danceability and acousticness on a scale from -1 to 1. These exist in two different files, which are in different formats - CSV and JSON. While CSV is a popular file format for denoting tabular data, JSON is another common file format in which databases often return the results of a given query.

## Task :
Using a dataset comprised of songs of two music genres (Hip-Hop and Rock), we will train a classifier to distinguish between the two genres based only on track information derived from Echonest (now part of Spotify). We will first make use of pandas and seaborn packages in Python for subsetting the data, aggregating information, and creating plots when exploring the data for obvious trends or factors we should be aware of when doing machine learning.

Next, we will use the scikit-learn package to predict whether we can correctly classify a song's genre based on features such as danceability, energy, acousticness, tempo, etc. We will go over implementations of common algorithms such as PCA, logistic regression, decision trees, and so forth.

## Summary :
Found that my model was biased because of skewed training and test samples which I solved by standard resampling. Although balancing removed bias it had a significant hit on the performance plummeting it down by about 5%. Achieved a final accuracy of 72.2% for Decision Tree and 77.3% for Logistic Regression.
