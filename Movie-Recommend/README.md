# Strawhat-Labs-Intern-AI
--------------------------------------------------------------------------------------------------------
## Movie Recommendation System

Movie Recommendation System a type of recommendation system model that is built on top of a basic recommendation system known as Content Filtering. In this method, we basically start with taking the dataset of movies from the TMDb dataset from kaggle. We then performed the preprocessing and data-cleaning procedures in order to structurize our dataset as per our required formats. For this, we used several Pandas and Numpy methods as shown in the notebook. We then used the methods of word embeddings and created a matrix of all the word embeddings.Then we used these word embedding and made another matrix that represents the distance of each movie to every other movie on our dataset and stores it in a matrix form. This matrix is calculated by using the cosine similarity and then later, we use this matrix to calculate the top 5 closest movies to the chosen one by the user. Then we recommend these top 5 movies.


### Resources:
  **Dataset:** https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download
  
