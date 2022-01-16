
The dataset for this project can be found [here](https://www.kaggle.com/tamber/steam-video-games).

This recommendation system is accomplished using Item-based Collaborative Filtering.

Now, collaborative filtering is usually done with ratings, where users rate movies/games/songs/shows/etc out of 5 or maybe 10. However, I do not have access to rating data, just hours played. So, I will use hours played as the metric. While this may bring some challenges, it should be able to serve in a pretty similar manner as ratings. One key assumption is being made here: the more a user plays a game, the more they like the game. This may not be completely accurate every time, but it should be good enough.

In Item-based Collaborative Filtering, I must construct an item-item (game-game) correlation matrix for the algorithm.
