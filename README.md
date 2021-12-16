# Twitter Sentiment Analysis for Airline Services

Completed for the UT Austin McCombs Artificial Intelligence and Machine Learning Post Graduate Program. 

**Course:** Introduction to Natural Language Processing - March 2021

**Score:** 60/60

## Project Summary
To identify the sentiment from a tweet to understand an airlines' customer satisfaction.

### Skills and Tools
Vectorization(Count vectorizer & tf-idf vectorizer), Sentiment analysis, Parameter tuning, Confusion matrix based model evaluation

## Project Description

A sentiment analysis job about the problems of each major U.S. airline. Twitter data was scraped from
February of 2015 and contributors were asked to first classify positive, negative, and neutral tweets, followed
by categorizing negative reasons (such as "late flight" or "rude service").

### Dataset:
The project is from a dataset from Kaggle.

Link to the Kaggle project site: https://www.kaggle.com/crowdflower/twitter-airline-sentiment

The dataset has to be downloaded from the above Kaggle website.

The dataset has the following columns:
* tweet_id
* airline_sentiment
* airline_sentiment_confidence
* negativereason
* negativereason_confidence
* airline
* airline_sentiment_gold
* name
* negativereason_gold
* retweet_count
* text
* tweet_coord
* tweet_created
* tweet_location
* user_timezone

### Objective:
To implement the techniques learnt as a part of the course.

### Learning Outcomes:
* Basic understanding of text pre-processing.
* What to do after text pre-processing:
    * Bag of words
    * Tf-idf
* Build the classification model.
* Evaluate the Model.
