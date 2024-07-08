# Movie Recommendation System

This repository contains the code for a movie recommendation system using various collaborative filtering and matrix factorization techniques. It includes extensive exploratory data analysis (EDA) and visualizations to better understand the dataset and the recommendation results.

## Table of Contents

- [Dataset](#dataset)
- [Requirements](#requirements)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Recommendation Models](#recommendation-models)
  - [User-Based Collaborative Filtering](#user-based-collaborative-filtering)
  - [Item-Based Collaborative Filtering](#item-based-collaborative-filtering)
  - [Matrix Factorization (SVD)](#matrix-factorization-svd)
  - [Matrix Factorization (ALS)](#matrix-factorization-als)
  - [Content-Based Filtering](#content-based-filtering)
  - [Hybrid Model](#hybrid-model)
- [Evaluation](#evaluation)
- [Visualizations](#visualizations)
- [Usage](#usage)

## Dataset

The dataset used in this project is the [MovieLens 100k dataset](https://grouplens.org/datasets/movielens/100k/). It consists of 100,000 ratings from 943 users on 1682 movies.

## Requirements

The following Python libraries are required to run the code:

- pandas
- matplotlib
- seaborn
- surprise
- sklearn
- implicit

You can install these libraries using pip:

```bash
pip install pandas matplotlib seaborn scikit-surprise scikit-learn implicit
