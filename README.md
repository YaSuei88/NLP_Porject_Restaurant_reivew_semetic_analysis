# NLP_Porject_Restaurant_reivew_semetic_classification- Project Overview
This is my learning project when taking Machine Learning A-Z course on Udemy. The goal is to do semetic analysis/ classification on the restaurant reivew texts via bag of words model.

## 1. Problem definition
To deterimine a given restaurant review text is negative or possitive. 

## 2. Data
The data provide by the course material.

## 3. Code and Resource Used
Python version: 3.7
Packages:  pandas, numpy, matplotlib.pyplot, re, nltk

## 4. EDA
Check how does the data look like:

![image](https://user-images.githubusercontent.com/70978272/135246433-82bd2935-1586-4985-9e29-97768fc03f82.png)

## 5. Data Cleaning
Clean the data with the following steps:

* replace anything that is not letters into space
* make everything lower case 
* customized the stop word list: excluded the word "not"
* stemming everything that is not in the stop word list    

## 6. Modelling
 Split the data into train and test set. The model that is used for current project: **Naive Bayes** 
 

## 7. Evaluataion
confusion matrix:

![image](https://user-images.githubusercontent.com/70978272/135250934-e5ac6492-b1ce-4dab-80e4-e636d4c79c31.png)
 
accuracy: 0.67


