# recommendation-engine

Using the MovieLens dataset and build a model to recommend movies to the end users.
DataSet Used: https://grouplens.org/datasets/movielens/100k/

# Building collaborative filtering model from scratch
• We will recommend movies based on user-user similarity and item-item similarity.
• We will calculate the similarity. We can use the pairwise_distance function from sklearn to calculate the cosine similarity.
• Using item-item and user-user similarity in an array form
• Make predictions based on these similarities.
• Finally, we will make predictions based on user similarity and item similarity.

# Building a simple popularity and collaborative filtering model using Turicreate

• We have user behavior as well as attributes of the users and movies, so we can make content based as well as collaborative filtering algorithms. We will start with a simple popularity model and then build a collaborative filtering model.
• First we’ll build a model which will recommend movies based on the most popular choices, i.e., a model where all the users receive the same recommendation(s). We will use the turicreate recommender function popularity_recommender for this.
• Note that the recommendations for all users are the same – 1536, 1201, 1189, 1122, 814. And they’re all in the same order! This confirms that all the recommended movies have an average rating of 5, i.e. all the users who watched the movie gave it a top rating. Thus our popularity system works as expected.
• After building a popularity model, we will now build a collaborative filtering model. Let’s train the item similarity model and make top 8 recommendations for the first 5 users. (you can increase as well, not an issue)

  






