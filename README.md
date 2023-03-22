# Twitter Sentiment Analysis

## Project description:
This project aims to perform sentiment analysis on Twitter data using the Sentiment140 dataset, which consists of 1.6 million tweets extracted using the Twitter API. The tweets in this dataset have been annotated as either negative or positive sentiment based on their content. The objective of this project is to develop a model that can accurately classify the sentiment of a tweet as either positive or negative.

The end goal of this project is to build a sentiment analysis model that can accurately classify the sentiment of a tweet as either positive or negative. The model can be used to analyze the sentiment of Twitter data for various applications, such as brand monitoring and customer feedback analysis.

## Dataset:

[Sentiment140 dataset with 1.6m tweets](https://www.kaggle.com/datasets/kazanova/sentiment140). It contains the following 6 fields:

* target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
* ids: The id of the tweet ( 2087)
* date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
* flag: The query (lyx). If there is no query, then this value is NO_QUERY.
* user: the user that tweeted (robotickilldozr)
* text: the text of the tweet (Lyx is cool)

## Word Clouds for tweets:

Word cloud for positive tweets:
![alt text](https://github.com/lhthien09/Twitter_Sentiment_Analysis/blob/main/figures/Pos_words.png)

Word cloud for negative tweets:
![alt text](https://github.com/lhthien09/Twitter_Sentiment_Analysis/blob/main/figures/Neg_words.png)

## Results:
The whole notebook with EDA, Preprocessing data & model building is detailed presented at: [JupyterNote](https://github.com/lhthien09/Twitter_Sentiment_Analysis/blob/main/Sentiment_Analysis.ipynb)
