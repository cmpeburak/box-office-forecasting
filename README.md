This repository includes some codes that I've written for a master thesis with the title of "Using reviews on the web to predict Box Office success with deep neural networks".

Codes to retrieve data from various sources, the data itself, codes to analyze the data and machine learning models used in the prediction are provided and ready to use.

## box-office-open-data
A comprehensive open data set is created by crawling and integrating information from various sources. This data set will be made publicly available to the research community. The data set contains various features about the movies ranging from basic information like actors, genre and run time to economic information like budget, revenue and number of screens that show the movie. Also, all YouTube user comments that were made on the movie trailer are added to the data set.

There are two type data files in this repository:
* movie-master <br>
'actor', 'director', 'genre', 'movie_id', 'name', 'rating', 'runtime',
'votes', 'year', 'release_date', 'index', 'video_id', 'view_count',
'like_count', 'dislike_count', 'comment_count', 'budget', 'revenue',
'is_sequel', 'mpaa', 'screen_count', 'season', 'seasonality',
'like_ratio', 'is_profitable', 'revenue_range', 'polarity_tb',
'w_polarity_tb', 'count_pos_tb', 'count_neg_tb', 'polarity_sia',
'w_polarity_sia', 'count_pos_sia', 'count_neg_sia', 'polarity_avg',
'w_polarity_avg', 'pos_neg_ratio', 'pos_neg_ratio_1', 'pos_neg_ratio_3',
'pos_neg_ratio_5'

* youtube-comments (splitted into multiple files) <br>
Columns: 'video_id', 'comment', 'comment_date', 'comment_like'

Detailed information about the data will be added here.
