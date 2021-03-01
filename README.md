# Collaborative Filtering
An Implementation of item-item collaborative filtering model and a latent factor model with stochastic gradient descent algorithm and evaluate the performance of models with Root Mean Squared Error(RMSE). The dataset is obtained from https://grouplens.org/datasets/movielens/100k/ and further processed to contain ‘user_id’, ‘item_id’, ‘rating’ and ‘movie_name’.

## Item-item Collaborative Filtering: 
Item-item collaborative filtering sets to achieve the similarity metric, calculate similarities of multiple movies, and to predict the rating of the given movie for given user. The similarity is calculated using the following equation.

![sim](https://user-images.githubusercontent.com/57331062/109444284-854ef680-7a02-11eb-9594-f81d7c64c14d.png)

## Latent Factor Model:
Latent Factor Recommendation system with optimizied the P and Q matrix in memory using the Stochastic Gradient Descent algorithm. The error function is calculated using the following equation where the sum is calculated on the pairs of user and movie based on the users rating of an item.

![error](https://user-images.githubusercontent.com/57331062/109444357-b16a7780-7a02-11eb-911e-c010bbdb971b.png)
