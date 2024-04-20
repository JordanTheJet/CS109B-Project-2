# CS109B-Project-2
CS 109B project
Group members: Arushi Agarwal, George Cruz, Jordan Tian, Gabriel Workman

Our dataset has 7475 observations. 



Why not use larger datasets? https://www.kaggle.com/datasets/kazanova/sentiment140 1.6 million labeled tweets but no user information

Interesting to compare our model vs other python sentiment analysis packages: VADER, textblob, flair

2 Rule based models
VADER rule-based sentiment analysis tool gives a a value for the probability of a given input sentence to be Positive, negative, and neutral adding up to 1

textblob gives sentiment as a float [-1, 1] and also a Subjectivity float which lies in the range of [0,1]. Subjective sentences generally refer to personal opinion, emotion, or judgment. 

1 Embedding based model:
flair - pre-trained sentiment analysis model on IMDB dataset. model might not generalize well on data from other domains like twitter. Maybe a good baseline model to compare with?




references:


https://neptune.ai/blog/sentiment-analysis-python-textblob-vs-vader-vs-flair
