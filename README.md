# Movie-Genres-Classification-from-their-Poster-Image-using-CNNs

## Introduction
### Problem Description

This project has the aim to achieve movie genre classification based only on movie poster images.
For movie viewers, movie posters are one of the first impressions used to get an idea about the movie content and its genre. Humans can get an idea based on things like color, objects, expressions on the faces of actors etc to quickly determine the genre (horror, comedy, animation etc).
If humans are more or less able to predict genre of a movie only giving a look at its poster, then we can assume that the poster possesses some characteristics which could be utilized in machine learning algorithms to predict its genre.

### Proposed Approach

In order to do that a Deep Neural Network (Convolutional Neural Network) is constructed to classify a given movie poster image into genres. Since a movie may belong to multiple genres, this is a multi-label image classication problem.

First of all, we use an online available IMDB dataset (source: https://www.kaggle.com/neha1703/movie-genre-from-its-poster) collected from the most famous movie website (https://www.imdb.com/).
Using the IMDB link of each movie (available in this dataset) we use a Web Scraping approach in order to retrieve its poster image from the IMDB movie page and save it locally. Once this is done, we can finally construct our Convolutional Neural Network in order to classify movie genre basing on poster characteristics.

Note: since even a human can easily make mistakes in this task, our initial goal is to recognize correctly at least half of the movies.

(sources and related links: 
https://www.depends-on-the-definition.com/classifying-genres-of-movies-by-looking-at-the-poster-a-neural-approach/
https://www.kaggle.com/neha1703/movie-genre-from-its-poster
https://towardsdatascience.com/building-a-convolutional-neural-network-cnn-in-keras-329fbbadc5f5)
