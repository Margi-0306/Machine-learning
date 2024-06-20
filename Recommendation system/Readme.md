# Recommendation system
A recommendation system is one of the applications of machine learning. In this project, I used the cosine similarity measure to find the similarity between users. I utilized a movie dataset and set up the environment in Jupyter Notebook, employing pandas and numpy libraries. Additionally, I used the pivot function to create the user-item matrix.

## What is user Item Matrix? 

A user-item matrix (also known as a user-item interaction matrix or user-item rating matrix) is a fundamental concept in recommendation systems. It is a matrix that represents the interactions between users and items (e.g., products, movies, books). Each row corresponds to a user, each column corresponds to an item, and each cell in the matrix represents the interaction (such as a rating, view, purchase, or any other interaction metric) between a specific user and a specific item.

Here’s a more detailed explanation:

**Structure**: 
- Rows: Represent users.
- Columns: Represent items.
- Cells: Represent the interaction between a user and an item.
This interaction can be: Explicit, such as ratings (e.g., 1-5 stars for movies). Implicit, such as clicks, views, or purchases (often represented as 1 if an interaction occurred and 0 if it did not).

## What is cosine similarity rule? 

Cosine similarity is a metric used to measure how similar two vectors are in a multidimensional space. It is widely used in various applications, including information retrieval, text analysis, and recommendation systems, to determine the similarity between items or users. By calculating the cosine similarity, you can find users or items that are similar to each other, which helps in making recommendations.

## What pivot function is doing in Recommendation system? 

In the context of a recommendation system, the pivot function in pandas is used to transform the dataset into a user-item matrix (also known as a user-item interaction matrix). This matrix is fundamental for various collaborative filtering techniques, as it organizes the data in a way that makes it easy to calculate similarities between users or items. user_item_matrix = df.pivot(index='user_id', columns='movie_id', values='rating')

## What is the use of pairwise_distances? 

The pairwise_distances function from the sklearn.metrics module is used to compute the distance between each pair of samples in a given dataset.Used to compute the similarity between users or items. For example, in collaborative filtering, you might compute the cosine similarity between user vectors to find similar users. cosine_sim = 1 - pairwise_distances(user_item_matrix, metric='cosine')
