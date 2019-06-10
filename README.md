# Movie Recommender System
Exploring different kinds of movie recommender systems

This repository contains files for a recommender system project

## Explanation of Files

* [Dataset Gathering and Scraping](https://github.com/ecbenezra/recommender-system/blob/master/dataset-compiling-scraping.ipynb) - a jupyter notebook documenting the scraping process from IMDb using the OMDB API. Since I am planning onusing the MovieLens 20M dataset for user-user recommender system later on, I wanted to do the other systems on the same movies, so that I can compare them. I scraped movie data including director, actors, title, box office, plot, genres, and more, from 25,634 movies.

* [All datasets cleaning and exploration](https://github.com/ecbenezra/recommender-system/blob/master/all-datasets-cleaning-exploration.ipynb) - cleaning of the three major datasets involved in this process - self scraped data from IMDb, the Movie Database, and the MovieLens 100k dataset. This file contains the cleaning and exploratory visualization for all of the metadata involved in the datasets.

* [Cosine similarity with bag of words and tf-idf](https://github.com/ecbenezra/recommender-system/blob/master/Cosine-similarity-with-NLP-bow.ipynb) - a first pass at using NLP to recommend movies using both cosine similarity and then order those results by their weighted IMDB ratings. This does not include any personalization and has no user data. This method is good for linking movies by underlying thematic elements. See analysis in the notebook for more information.
