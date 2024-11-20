# Movie Recommendation System

## Overview
This project is a movie recommendation system built using Flask that provides personalised movie suggestions based on user ratings and movie metadata. The system employs two models:

1. Collaborative Filtering using Singular Value Decomposition (SVD)
2. Content-Based Filtering using Genres with Term Frequency - Inverse Document Frequency (TF-IDF)

***

## Features
- Personalised movie recommendations based on user preferences.
- Two recommendation models:
  - Collaborative filtering: Uses SVD to recommend movies based on user ratings and latent features.
  - Content-based filtering: Recommends movies based on similar genres and metadata.
- Flask-based web interface for easy interaction.

***

## Dataset
The project uses the MovieLens dataset obtained from Kaggle:
- [movies.csv](https://www.kaggle.com/datasets/parasharmanas/movie-recommendation-system?select=movies.csv) for metadata.
- [ratings.csv](https://www.kaggle.com/datasets/parasharmanas/movie-recommendation-system?select=ratings.csv) for user ratings for the movies.

***

## Screenshots
<html>
<figure style = "text-align: center;">
  <img src = "https://github.com/user-attachments/assets/5d2ac67d-c2de-4423-a87e-4b9afc167e40" alt = "collaborative filtering" width = "80%"><br>
  <figcaption>Collaborative filtering using SVD</figcaption>
</figure>

<br>

<figure style = "text-align: center;">
  <img src = "https://github.com/user-attachments/assets/bd02d3dd-8225-4636-86ea-d4c0629757e0" alt = "content based filtering" width = "80%"><br>
  <figcaption>Content-based filtering using TF-IDF</figcaption>
</figure>
</htmL>

***

## External links
[Link to implementation of the project](https://svd-djjz.onrender.com/)
