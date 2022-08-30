# Restaurant-Reviews-Sentiment-Analysis

![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue.svg) ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![Scikit-Learn](https://img.shields.io/badge/Libraries-ScikitLearn-orange.svg)![NLTK](https://img.shields.io/badge/NLTK-brightyellow.svg)

This repository consists of files required for end to end implementation and deployment of Machine Learning NLP Restaurant Reviews Sentiment Analysis web application created with flask and deployed on the Heroku platform.

## Table of Contents
  * [App Link](#app-link)
  * [About the App](#about-the-app)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Technologies Used](#technologies-used)
  * [Bug / Feature Request](#bug---feature-request)


## App Link
If you want to view the deployed model, click on the following link:<br />
[ https://resrevsent.herokuapp.com/]( https://resrevsent.herokuapp.com/)

A glimpse of the web app:

![GIF](readme_resources/negresrev.gif)

![GIF](readme_resources/posresrev.gif)

• If you encounter this webapp as shown in the picture given below, it is occuring just because **free dynos for this particular month provided by the Heroku platform have been completely used.** You can access the webpage on 1st of the next month.

• Sorry for the inconvenience.

![Heroku-Error](readme_resources/application-error-heroku.png)

## About the App
The Restaurant Reviews Sentiment Analysis is a Flask web application which classifies/detects sentiments of customers as positive or negative sentiments. In this ML-NLP model, restaurant reviews dataset from Kaggle (also available in UCI ML Library) was used to perform Sentiment Analysis using Stemming and Bag of Words model to classify reviews into two sentiments — Liked(1) and Disliked(0). Since, the data is fairly balanced, we are only concerned with accuracy_score. From various Classifiers, highest accuracy achieved was 81% with cross_val_score of 79.4%.

 To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```
