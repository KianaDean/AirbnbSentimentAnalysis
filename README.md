# AirbnbSentimentAnalysis
Sentiment analysis on Airbnb social media data

## The Problem
Emotions are a factor in customers' purchase decisions. With the rise of social media it has become easier than ever for customers' to share their emotions about their purchases for others to see. The good thing is there is now a trove of data of customer reviews and thoughts of companies. However, it would not be sustainable to go through each tweet, post, and mention to determine customer sentiment.

## The Solution
Using Natural Language Processing brands can turn how customers feel into actionable business data. Tweets, posts, news, and mentions can be ran through tools/models that place a sentiment label (ex: Negative, Postive) on the data. This can give companies an overall view of how customers feel about their brand.

## The Data
I wanted to analyze Airbnb data for this project since I've started to see more tweets mentioning that they have started to consider hotels again over Airbnb.

![AirbnbTweet](https://github.com/KianaDean/AirbnbSentimentAnalysis/blob/main/images/abnbtweet.PNG)

There were two datasets used in this analysis.

Twitter Data
* Pulled data from the Twitter API
* Pulled 5,000 tweets that mentioned airbnb
* Filtered out retweeted tweets to prevent duplicate tweets in the data

Reddit Data
* Pulled post data using RedditExtractoR
* Pulled 614 posts from r/Airbnb that had greater than 5 comments

## Steps Taken
1. Pull Twitter and Reddit data into R using Twitter API and web scrapping
2. Perform sentiment analysis on Twitter and Reddit data
3. Created a PowerBI dashboard to display sentiment analysis data

**Tool Used:** R, PowerBI

## Credit Card Fraud Prediction Dashboard
![Twitter Overview Dashboard](https://github.com/KianaDean/AirbnbSentimentAnalysis/blob/main/images/pbisentimenttwitteroverview.PNG)

![Reddit Overview Dashboard](https://github.com/KianaDean/AirbnbSentimentAnalysis/blob/main/images/pbisentimentredditoverview.PNG)
