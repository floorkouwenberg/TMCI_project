# Final Project: Text Mining and Collective Intelligence
## Floor Kouwenberg, Lanie Preston, and Jasmijn Bleijlevens 

## Title

## Abstract
We would like to create a classifier that can predict the number of stars a food item will recieve in an Amazon review based on sentiment analysis of the language in the review. We will achieve this by training a Naive Bayes classifier or a KNN classifer on the number of stars that the review earned on a selection of Amazon food reviews in the Review.csv file to predict the number of stars. We will also count the co-occurrences to find the words in the review that are most often associated with positive and negative words. We will take the list of positive or negative words from the SentiWordNet corpus in NLTK. We think this would be extremely helpful to those who wish to purchase food online without being able to try it in advance.     

## Research questions
1. Is it possible to estimate the number of stars a food review will recieve based on the language of the review?
2. Can we isolate specific attributes of a product that contribute to its rating?

## Dataset
Link to the Dataset: https://drive.google.com/file/d/1muN7X7tqzIZRokeyBnnvW8aXlkRpvIun/view?usp=sharing (it was too large to put on Github)

List the dataset(s) you want to use, and some ideas on how do you expect to get, manage, process and enrich it/them. Show you've read the docs and are familiar with some examples, and you've a clear idea on what to expect. Discuss data size and format if relevant.

## A tentative list of milestones for the project
Week 12: Pre-processing and Preparations
In this week, Jasmijn will pre-process by filtering and lemmatizing the textual reviews in our dataset. 

Week 13
Create and train the Naive Bayes Classifier on our dataset. The Naive Bayes model will focus on the raw frequencies of positive, neutral, or negative words in the text of the review as well as the number of stars in the review and the correlation between these two metrics. We will then evaluate this model on our test set.    

Week 14
We will apply vector semantics to the data set to measure the words that specifically co-occurred with positive and negative words in each review. This way, we can predict the stars the review will get, but also what about the review is  
 
Week 15
Lanie will write the project report. Jasmijn will create the slides for our presentation on Tuesday.

## Documentation
Currently our repo conists of our dataset.
