# Dogecoin Sentiment 

Phase Four Group Project / Flatiron Data Science Bootcamp

By: 
- Lenore Perconti 
- Evan Johnson
- Andrew Schmeck

## Overview

This Proect is a sentiment analysis with NLP. It identifies positve vs non-positive (neutral, negative) sentiment of tweets on the topic of dogecoin.

### The Stakeholder / Business Problem
Our hypothetical stakeholder is a Marketing team for a hedgefund. As a Marketing team for a hedgefund, understanding current sentiment around dogecoin will be key to helping clients understand and navigate this market. In this projec, we analyze sentiment around Dogecoin on Twitter. Dogecoin is a cryptocurrency with a $30B market cap. Twitter is an excellent way to get a 'pulse' on public sentiment, and in this presentation we'll show you how this team explored public sentiment via a form of machine learning called sentiment analysis

### Data

Twitter API searching for dogecoin topic and excluding retweets. Our final dataset included 9,000 individual tweets between the dates of 11/12/21 and 11/19/21. 

It's worth to note as well that the value of Dogecoin declined dring this week. 

![doge_value_graph](./images/doge_value_graph.png)

![doge_value_stats](./images/doge_value_stats.png)

### Methods

We ran tweets through a Sentiment Intensity Analyzer without preprocessing. This provided the sentiment target (Positive, Negative, Neutral).

We then focused on preproccessing to improve the model. We removed punctuation, lowercased all words and removed stopwords. Then we ran a simple model using Sentiment Intensity Analyzer on the processed tweets. 

## Results

The resulting model was a sentiment analysis that predicted positive tweets with 70% precision. 


## Conclusions

Through this project we’ve found that most of the confidence in the currency is built around hype. For this reason we would want to use our model to continue to monitor dogecoin sentiment to gauge our own confidence in the coin.

We also learned thorugh this project that much of the tweet langugage used for dogecoin is slang and not always intuitive. For example, "shibu inu killer" is a positive tweet because as dogecoin's competetor, killing the value of their competetor is a good thing for dogecoin. This makes seintiment analysis challenging and requires spoon feeding the model known positive words. 

In the context of a social media campaign, modeling and predicting positive tweets could help marketing understand and correctly use buzz words in campaigns in a timely manner. This could strengthen outreach towards investors interested in looking at dogecoin.

### Next Steps

Fo this project we only had access to 100 tweets every hour. Dogecoin gets tweeted about much more than 100 tweets an hour, at one check we observed . An upgraded API would give us 500 tweets every hour.

For this project we only tracked single/double words and tied them to the positive class. For future research we’d like to look at words for the negative/neutral class and also incorporating phrases to better improve the model performance.

Finally we’d like to try and apply our sentiment analysis towards predicting the future price of dogecoin. We would look into seeing if there is a correlation between social media sentiment around the coin and how the coin price changes.


[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)


   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>