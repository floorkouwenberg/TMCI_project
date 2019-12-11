# Final Project: Text Mining and Collective Intelligence
## Floor Kouwenberg, Lanie Preston, and Jasmijn Bleijlevens 

## Fantastic Food Finder : Rating Prediction & Sentiment Analysis on Amazon Food Reviews

## Abstract
We would like to create a classifier that can predict the number of stars a food item will recieve based on it's review. We will analyze the reviews and also perform sentiment analysis. We will train a several Naive Bayes classifiers to predict the number of stars a food review will get. We will then preform analysis on them to see which one preforms best. We will also try to write a function that will give the best attribute of a certain product, again using sentiment analysis. We think this would be extremely helpful to those who wish to purchase food online without being able to try it in advance.     

## Research questions
1. Is it possible to estimate the number of stars a food review will recieve based on the language of the review?
2. Can we isolate specific attributes of a product that contribute to its rating?

## Dataset
Source of the dataset: J. McAuley and J. Leskovec. From amateurs to connoisseurs: modeling the evolution of user expertise through online reviews. WWW, 2013.
Link to the Dataset: https://drive.google.com/file/d/1muN7X7tqzIZRokeyBnnvW8aXlkRpvIun/view?usp=sharing (it was too large to put on Github)
This dataset contains more than 500.000 reviews on food products that are sold on amazon. We are mostly interested in the rating and text columns. Since the dataset is quite large we will select the first 50.000 entries, otherwise operations will take a long time to run. 


## A tentative list of milestones for the project
Week 12: Pre-processing and Preparations
In this week, Jasmijn will pre-process by filtering and lemmatizing the textual reviews in our dataset. We chose to lemmatize rather than stem our corpus because lemmatization takes into account the morphological content of the words, making it more accurate in this instance.

Week 13
Floor can create and train the Naive Bayes Classifier on our dataset. The Naive Bayes model will focus on the raw frequencies of positive, neutral, or negative words in the text of the review as well as the number of stars in the review and the correlation between these two metrics. We will then evaluate this model on our test set.    

Week 14
Together we will apply vector semantics to the data set to measure the words that specifically co-occurred with positive and negative words in each review. This way which attributes of a product are especially good or bad. 
 
Week 15
Lanie will write the project report. Jasmijn will create the slides for our presentation on Tuesday.We will all prepare for the presentation. 

## Documentation
| File | Description |
| --- | --- |
| .ipynb_checkpoints	| Related to the Jupyter Notebooks | 
| .gitattributes	| Related to Git | 
| Cooccs.ipynb	| Jupyter Notebook containing the some plots and basic code for the co-occurences | 
| Machine Learning (1) with raw frequencies.ipynb	| Jupyter Notebook containing some Naive Bayes classifiers | 
| Machine learning (2) with plmi weighting and co-occs.ipynb | Jupyter Notebook containing some more Naive Bayes classifiers | 
| Machine learning (3) with positivity and negativity scores.ipynb	| Jupyter Notebook containing one more Naive Bayes classifier | 
| Preprocessing_Lemmatizing.ipynb	| Contains the preprocessing pipeline and lemmeatization of the reviews. Only run this file with the downloaded dataset from the abovementioned website. For all other Notebooks you will not need the large dataset. |
| README.md	| . |
| Reviews.csv	| The csv file containing our dataset |
| cooccs_dict.txt	| Contains a dictionary containing all coocurences of our shortened dataset | 
| desktop.ini	| ? | 
| test_dicts.txt	| Containts 8000 entries of our dataset and is used for testing the classifiers |
| training_dicts.txt | Contains 2000 entries of our dataset an is used for training the classifiers |
