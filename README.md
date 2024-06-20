# Movie-Recommender-System-Using-Machine-Learning

![_c2204eeb-cec7-48ed-b0f1-486d02cd88d3](https://github.com/abhayjr11/Movie-Recommender-System-Using-Machine-Learning/assets/62216948/aeea1bba-4756-4594-9553-c55ab0742c0e)

Recommendation systems are becoming increasingly important in today’s extremely busy world. People are always short on time with the myriad tasks they need to accomplish in the limited 24 hours. Therefore, the recommendation systems are important as they help them make the right choices, without having to expend their cognitive resources.

The purpose of a recommendation system basically is to search for content that would be interesting to an individual. Moreover, it involves a number of factors to create personalised lists of useful and interesting content specific to each user/individual. Recommendation systems are Artificial Intelligence based algorithms that skim through all possible options and create a customized list of items that are interesting and relevant to an individual. These results are based on their profile, search/browsing history, what other people with similar traits/demographics are watching, and how likely are you to watch those movies. This is achieved through predictive modeling and heuristics with the data available.

# Types of Recommendation System :
There are mainly three methodologies for Recommendation Systems: collaborative filtering, content-based filtering, and hybrid systems.

Method 1. Collaborative filtering

Collaborative filtering operates by evaluating user interactions and determining similarities between people (user-based) and things (item-based). For example, if User A and User B like the same movies, User A may love other movies that User B enjoys. A method used in recommendation systems to forecast items which user may enjoy based on the preferences of other users who have similar likes. It works by analyzing user interactions and identifying similarities between individuals (user-based) and objects (item-based).

1.1 User-based Collaborative Filtering

This technique predicts products that a user could appreciate based on ratings provided to that item by other users who share the target user’s preferences. The steps are as follows:

Finding similarities between users and the target user: This is determined using an algorithm that considers the ratings provided by both users to common goods.
Predict the missing rating of an item: The ratings that come from users who are more like you are given more weight than the ratings that come from users who are less like you. This is accomplished using a weighted average method.

1.2 Item-Based Collaborative Filtering

This method predicts which things a user would enjoy based on their similarity. The steps are as follows:

Item to item similarity: The similarity of all item pairings is determined, often using cosine similarity.
Prediction Computation: A rating is generated using the items that the user has previously rated and are most comparable to the missing item. This is accomplished using a method that calculates the rating for a specific item based on a weighted sum of the ratings of other comparable goods.
Both user-based and item-based collaborative filtering may work on the same data, the choice is determined by the recommendation system’s unique needs.

Method 2. Content-based filtering

Content-based filtering is a technique used in recommender systems to suggest items that are comparable with an item a user has shown interest in, based on the item’s attributes. It uses machine learning algorithms to classify similar items based on inherent characteristics such as genres, directors, or keywords associated with previously seen movies. This strategy is especially effective for enterprises that provide a variety of goods, services, or information since it may make individualized suggestions to consumers based on their previous behavior or explicit input. If a user has given high ratings to action movies, the algorithm will propose more action movies based on genres, directors, or keywords connected with previously loved movies.

Content-based filtering involves representing items and users in a feature space, which may contain categories, publishers, and other relevant properties.
The similarity between user and item is then determined using statistic metric dot product, which reflects how many features are active in both vectors at a moment. A high dot product suggests more common features, resulting in a higher similarity.
Content-based filtering are implemented using classification models and the vector spacing method. The classification strategy makes use of machine learning models such as decision trees, whilst the vector spacing method makes recommendations based on the distance between the user and item vectors.

One of the primary benefits of content-based filtering is that it does not rely on data from other users to create suggestions, making it especially effective for people with specific taste or items with low user interaction data. However, it may be limited by the quality of the item features and the algorithm’s ability to capture the intricacies of human preferences.

Method 3. Hybrid systems

Hybrid systems in recommendation systems combine collaborative and content-based methods to leverage the strengths of each approach, resulting in more accurate and diversified recommendations. These systems often start with content-based filtering to study new users and gradually integrate collaborative filtering as more interaction data becomes available.

Hybrid recommender systems can be categorized into weighted, feature combination, cascade, feature augmentation, meta-level, switching, and mixed models. The feature combination method interprets collaborative information as additional feature associated with each example and applies content-based approaches to this enriched data collection. The meta-level hybrid recommender system combines two recommender systems such that the outputy of one becomes the input for the other.

Hybrid recommender systems are the most effective approach to developing a recommender system. However, they do have drawbacks, such as the ramp-up problem, since both systems need a database of ratings. Knowledge-based and utility-based recommender strategies . The most popular hybrid recommender systems are feature augmentation and meta-level systems, which feed information from one into the output of the other.
