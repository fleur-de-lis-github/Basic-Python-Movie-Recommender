# Basic Python-Movie-Recommender

This project will take you through the process of mashing up data from two different APIs to make movie recommendations. The TasteDive API lets you provide a movie (or bands, TV shows, etc.) as a query input, and returns a set of related items. The OMDB API lets you provide a movie title as a query input and get back data about the movie, including scores from various review sites (Rotten Tomatoes, IMDB, etc.).

You will put those two together. You will use TasteDive to get related movies for a whole list of titles. You’ll combine the resulting lists of related movies, and sort them according to their Rotten Tomatoes scores (which will require making API calls to the OMDB API.)

To avoid problems with rate limits and site accessibility, we have provided a cache file with results for all the queries you need to make to both OMDB and TasteDive. Just use requests_with_caching.get() rather than requests.get().

Your first task will be to fetch data from TasteDive. The documentation for the API is at https://tastedive.com/read/api.

Your next task will be to fetch data from OMDB. The documentation for the API is at https://www.omdbapi.com/

you will not need an api key in order to complete the project, because all data will be found in the cache.

The cache includes data for the following queries:

![Screenshot (1472)](https://user-images.githubusercontent.com/73738414/140882526-2ccc2e86-ae12-4ee7-8d26-cb95ba7697d1.png)


