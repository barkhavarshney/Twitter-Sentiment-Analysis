# Twitter Sentiment Analysis

## Overview

The following project is about analyzing the sentiments of tweets on the social networking website 'Twitter'. The dataset for this project is scraped from Twitter, containing 1,600,000 tweets extracted using the Twitter API. It is a labeled dataset with tweets annotated with sentiment (0 = negative, 2 = neutral, 4 = positive). It contains the following 6 fields:

- **target:** The polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
- **ids:** The id of the tweet.
- **date:** The date of the tweet (e.g., Sat May 16 23:58:44 UTC 2009)
- **flag:** The query. If there is no query, then this value is NO_QUERY.
- **user:** The user that tweeted.
- **text:** The text of the tweet.

## Objective

Design a classification model that correctly predicts the polarity of the tweets provided in the dataset.


