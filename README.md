# Movie-Recommender-System
Hybrid Movie recommender system using deep neural networks.

## Overview
Recommender Systems(RS) makes life easier by proposing most suitable item which might interest the users using various Machine Learning algorithms based on the user’s historical behavior and contextual analysis. Traditional approaches for recommending systems include Content based filtering and Collaborative filtering. But these personalized systems limit the options by displaying only the content liked by user, overtime they homogenize the users interest, making users to lose interest into other topics, which indirectly reduces options for recommendation system. To make this worse User might have to rate low to the recommendation to get rid of them. In the following paper I would like to propose a hybrid approach to recommendation systems to diversify recommendation.

## Dataset
The Movie Lens 100K(ML-100K) dataset is being used to test the effectiveness of the recommendation systems, which contains 100,000 ratings (0.5-5) from 943 users on 1682 movies, each user has rated at least 20 movies and it also contains genre of each movie and demographic information such as age, gender and occupation. This dataset also contains time stamp when the user has given rating and external links to IMDB and TMDB id’s which was beneficially to extract meta data about the movies. For the content-based recommender meta data of the movies was required for better predictions, So the addition of movie’s meta data information from TMDB (The Movie Database) was added to suffice the request.</br>
The TMDB consists of meta data of 45000 movies listed in the Full Movie Lens Dataset. The Dataset consists of movies released on or before July 2017. Data includes cast, crew, genres, keywords, release dates, revenue, budget, overview, production company, languages, TMDB vote count and vote average. [Data Source](https://www.kaggle.com/rounakbanik/the-movies-dataset)

