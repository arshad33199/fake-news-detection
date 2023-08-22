# fake-news-detection

## Table of Contents
* [Problem Statement](#Problem-Statement)
* [Approach](#Approach)
* [Data Preprocessing](#Data-Preprocessing)
* [Model Implementation](#Model-Implementation)




## Problem Statement:
This is a Machine learning project.i am trying to detect the fake news by the training the dataset.

![1000_F_336304058_lIkAhZbkWlUSQ6W0DY80RWwjjGi7NYNy](https://github.com/arshad33199/fake-news-detection/assets/142779412/82cb9339-8720-4ee6-b77a-3bb28af8478a)


## Approach:

## Data Preprocessing:
In this section I am doing all the Data cleaning and analysis.Most of the data is in categorical form which should get converted. 

I did some feature engineering in it and shuffle the dataset.

I dropped the additional info and route columns as most of the values were missing or of no use.

I added a new column as target for showing true and fake.

I did remove punctuations from text column and stop words from Text column with the help of nltk.

this is the subjects pie graph.
![newplot (34)](https://github.com/arshad33199/fake-news-detection/assets/142779412/2b39a6aa-5769-43b9-9e44-52a5ba73bd3b)




true and fake news counts.


![download](https://github.com/arshad33199/fake-news-detection/assets/142779412/9fe2d506-6af6-4aec-b799-3ea7893c72e5)





## Model Implementation:

I used DecisionTreeClassifier to fit the dataset.

the accuracy score is 99.64%% 


