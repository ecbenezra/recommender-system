# Movie Recommender System
Exploring different kinds of movie recommender systems

This repository contains files for a recommender system project

## Explanation of Files

* [Presentation](https://github.com/ecbenezra/recommender-system/blob/master/MovieRecPresentationPDF.pdf) - Presentation slides

* [Dataset Gathering and Scraping](https://github.com/ecbenezra/recommender-system/blob/master/dataset-compiling-scraping.ipynb) - a jupyter notebook documenting the scraping process from IMDb using the OMDB API. Since I am planning on using the MovieLens 20M dataset for user-user recommender system later on, I wanted to do the other systems on the same movies, so that I can compare them. I scraped movie data including director, actors, title, box office, plot, genres, and more, from 25,634 movies.

* [All datasets cleaning and exploration](https://github.com/ecbenezra/recommender-system/blob/master/all-datasets-cleaning-exploration.ipynb) - cleaning of the three major datasets involved in this process - self scraped data from IMDb, the Movie Database, and the MovieLens 100k dataset. This file contains the cleaning and exploratory visualization for all of the metadata involved in the datasets.

* [A popularity-based recommender system](https://github.com/ecbenezra/recommender-system/blob/master/Popularity-based-recommender.ipynb) - An initial, Universal popularity recommender that is completely unpersonalized and given to every user. The idea behind popularity recommenders is that if there is a movie you haven't seen that 1,000,000 people saw and liked, you might just like it, too! This method of system is used widely on the internet using various data available, such as: Reddit's [r/all results](https://www.reddit.com/r/all/), YouTube's [trending page](https://www.youtube.com/feed/trending), and the New Yorker's [most popular articles](https://www.newyorker.com/popular) 

* [Cosine similarity with bag of words and count vectorization](https://github.com/ecbenezra/recommender-system/blob/master/Cosine-similarity-with-NLP-bow.ipynb) - a first pass at using NLP to recommend movies using both cosine similarity and then order those results by their weighted IMDB ratings. This does not include any personalization and has no user data. This method is good for linking movies by underlying thematic elements. See analysis in the notebook for more information.

* [Collaborative recommender using SVD](https://github.com/ecbenezra/recommender-system/blob/master/collaborative-recommender-svd.ipynb) - using ratings data, predicting user ratings of movies they haven't watched yet.

* [Hybrid recommender](https://github.com/ecbenezra/recommender-system/blob/master/hybrid-recommender-system.ipynb) - a one-two punch of the recommender system, this allows a user to input a movie title and get back a curated list of movies that are similar to the movie in question, ordered by rating prediction. If the notebook doesn't load, you can also view it [here](https://nbviewer.jupyter.org/github/ecbenezra/recommender-system/blob/master/hybrid-recommender-system.ipynb)



Special thanks to the following:  
* David Reed 
* Jeff Kessler  
* Zachary White
