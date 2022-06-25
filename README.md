# Fake News Detection
## A Fake News Detection model using NLP and Logistic Regresion 🤖

![](https://media3.giphy.com/media/uIUao4X7CjXl2n0dd6/giphy.gif?cid=ecf05e47c9eiyvhcjm7yflf2cdu91lqfbtze6ntvx18vj8n6&rid=giphy.gif&ct=s)

## Table of Contents

1.  [Overview](#Overview)
 
2.  [Libraries Used](#Libraries-Used)
3.  [Workflow](#Workflow)
4.  [Flow-Chart](#Flow-Chart)
5.  [Challenges](#Challenges)
6. [FAQs](#FAQs)

## Overview

As human beings, when we read a sentence or a paragraph, we can interpret the words with the whole document and understand the context. In this project, I implemented a system to read and understand the differences between real news and fake news using concepts like natural language processing, and prediction classifiers like the Logistic regression which will predict the truthfulness or fakeness of an article.


## Libraries-Used

-   `pandas`
-   `nltk`
-   `sk-learn`

## Workflow


- **Loading Dataset:** First we will load the dataset in Google Colab notebook. We use the pandas library for loading and analyzing the dataset.

- **Data pre-processing:** All the preprocessing functions are needed to process all the documents and texts. First, we read the files then perform some preprocessing using NLTK.

- **Splitting data into train and test:** We will split data to train and test datasets. For this purpose, we are going to use the sci-kit learn library which helps to split data into X_train, X_test,y_train,y_test.

- **Training and modeling the dataset using logistics regression:** We will use a logistic regression classifier which will serve the model and work with user input. A logistic regression classifier will be used from sk-learn library.

- **Saving the model for future use:** We will be using the pickling technique here. Pickle is the standard way of serializing objects in Python. We can use the pickle operation to serialize your machine learning algorithms and save the serialized format to a file. Later you can load this file to deserialize your model and use it to make new predictions.

## Flow-Chart

![](https://github.com/Kens3i/Fake-News-Detection-Using-NLP-and-Machine-Learning/blob/main/workflow.JPG?raw=true)


## Challenges

First time working with NLP and had some difficulties undersatnding the concept of stopwords, stemming, and count vectorizer.

## FAQs
**_What are Stopwords ?_**
_A stop word is a commonly used word (such as “the”, “a”, “an”, “in”) that a search engine has been programmed to ignore, both when indexing entries for searching and when retrieving them as the result of a search query._  [https://www.geeksforgeeks.org/removing-stop-words-nltk-python/](https://www.geeksforgeeks.org/removing-stop-words-nltk-python/)

**_What is PortStemmer ?_**
_A PortStemmer is an algorithm used for removing the commoner morphological and inflexional endings from words in English. For example: words such as “Likes”, ”liked”, ”likely” and ”liking” will be reduced to “like” after stemming._  [https://www.geeksforgeeks.org/python-stemming-words-with-nltk/](https://www.geeksforgeeks.org/python-stemming-words-with-nltk/)

**_What is CountVectorizer ?_**
_CountVectorizer is a tool provided by the scikit-learn library. It is used to transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text._  [https://www.geeksforgeeks.org/using-countvectorizer-to-extracting-features-from-text/](https://www.geeksforgeeks.org/using-countvectorizer-to-extracting-features-from-text/)


### Thankyou For Spending Your Precious Time Going Through This Project!
### If You Find Any Value In This Project Or Gained Something New Please Do Give A ⭐.
