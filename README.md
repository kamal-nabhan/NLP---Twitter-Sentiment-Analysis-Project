# NLP---Twitter-Sentiment-Analysis-Project

## Introduction

This is a Kaggle project titled: Sentiment140 dataset with 1.6 million tweets

## Context
This is the sentiment140 dataset. It contains 1,600,000 tweets extracted using the twitter api . The tweets have been annotated (0 = negative, 4 = positive) and they can be used to detect sentiment .

## Content
It contains the following 6 fields:

target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)

ids: The id of the tweet ( 2087)

date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)

flag: The query (lyx). If there is no query, then this value is NO_QUERY.

user: the user that tweeted (robotickilldozr)

text: the text of the tweet (Lyx is cool)

## Acknowledgements
The official link regarding the dataset with resources about how it was generated is [here](http://help.sentiment140.com/for-students)
The official paper detailing the approach is [here](https://www-cs.stanford.edu/people/alecmgo/papers/TwitterDistantSupervision09.pdf)

## Citation: Go, A., Bhayani, R. and Huang, L., 2009. Twitter sentiment classification using distant supervision. CS224N Project Report, Stanford, 1(2009), p.12.

## Output

Sentiment-BNB.pickle

Sentiment-LR.pickle

vectoriser-ngram-(1,2).pickle
