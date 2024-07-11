# Movie Recommendation System

## Overview
This project implements a movie recommendation system using content-based filtering and cosine similarity based on movie metadata. It analyzes movies based on their plots, genres, keywords, cast, and crew to recommend similar movies to users.

## Dataset
The dataset can be download from kaggle or any other similar source (https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv).
The dataset used for this project includes:
- **tmdb_5000_movies.csv**: Contains information about 5000 movies including budget, genres, homepage, id, keywords, original language, overview, popularity, production companies, production countries, release date, revenue, runtime, spoken languages, status, tagline, title, vote average, and vote count.
- **tmdb_5000_credits.csv**: Provides details about the cast and crew associated with each movie, including movie_id, title, cast, and crew.

## Features
- **Data Preprocessing**: Cleaned and merged movie metadata from two datasets.
- **Text Processing**: Extracted features like genres, keywords, cast, and crew from textual data using natural language processing techniques.
- **Cosine Similarity**: Computed similarity scores between movies based on their textual features to recommend similar movies.
- **Vectorization**: Utilized CountVectorizer to convert text data into numerical vectors suitable for similarity calculations.

