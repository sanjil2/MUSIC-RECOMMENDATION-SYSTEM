# Music-Recommendation-System

Recommendation systems play a vital role in our day to day lives whether it may provide recommendations on which movie to watch or which item to buy. 
In this project, we are going to design, implement and analyze a music recommendation system. The dataset that we are using is the Million Song Dataset
provided by Kaggle. We are trying to find correlations between users and songs and to learn from the previous listening history of users to provide 
recommendations for songs which users would prefer to listen most in future. We are planning to implement various algorithms such as popularity based 
model, memory based collaborative filtering, and content based model using k-NN. In the popularity based model, we find the popularity of each song by
looking into the number of users listened to that song. Users are recommended with the top most popular songs and this does not involve personal interests. 
Collaborative filtering (CF) uses the numerical reviews given by the user andis mainly based upon the historical data of the user available to the system. 
The historical data available helps to build the user profile and the data available about the item is used to make the item profile. Both the user profile 
and the item profile are used to make a recommendation system. Collaborative filtering is considered the most basic and the easiest method to find recommendations
and make predictions regarding the sales of a product. In the item-based model, it is assumed that songs that are often listened together by some users tend to 
be similar and are more likely to be listened together in future also by some other user. According to the user-based similarity model, users who have similar 
listening histories, i.e., have listened to the same songs in the past tend to have similar interests and will probably listen to the same songs in future too. 
In the KNN method, we create a space of songs according to their features from the data and find out neighborhood of each song. We choose some of the available 
features (e.g., loudness, genre, mode, etc.) which we find most relevant to distinguish a song from others. After creating the feature space, to recommend songs
to the users, we look at each users profile and suggest songs which are neighbors to the songs present in his listening history. 

Dataset Link: https://www.kaggle.com/c/msdchallenge/data 
