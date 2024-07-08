# Movie Recommendation System

This repository contains the code for a movie recommendation system using various collaborative filtering and matrix factorization techniques. It includes extensive exploratory data analysis (EDA) and visualizations to better understand the dataset and the recommendation results.

## Dataset

The dataset used in this project is the MovieLens 100k dataset. It consists of 100,000 ratings from 943 users on 1682 movies.

## Recommendation Models

The following recommendation models are implemented in this project:

- User-Based Collaborative Filtering: Uses k-nearest neighbors (KNN) to find similar users and recommend movies based on their ratings.
- Item-Based Collaborative Filtering: Uses k-nearest neighbors (KNN) to find similar items and recommend movies based on item similarity.
- Matrix Factorization (SVD): Uses Singular Value Decomposition (SVD) to predict ratings and recommend movies.
- Content-Based Filtering: Uses TF-IDF vectorization to recommend movies based on their titles.
- Hybrid Model: Combines collaborative filtering and content-based filtering to provide recommendations.

## Evaluation

The models are evaluated using Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE) metrics.

## Visualizations

- **Rating distribution**: description here.
- **Top 10 most rated movies**: description here.
- **Distribution of the number of ratings per user**: description here.
- **Distribution of average ratings given by users**: description here.
- **Top 10 recommendations for each model**: description here.
