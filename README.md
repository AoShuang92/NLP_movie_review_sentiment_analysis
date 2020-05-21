# NLP_movie_review_sentiment_analysis
This repo is the NLP sentiment analysis on the data of movie reviews.<br>
About the dataset: the tsv file contains three columns: id, review and sentiment. Review is the comment and sentiment includes two classes, 1 for positive and 0 for negative. <br>
There are two comparative models: one is BOW without LSTM, other one is word embedding with LSTM. Since there is no test data, so I split the data into train and validation data for cross validation.<br>
