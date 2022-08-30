# Restaurant-Reviews-Sentiment-Analysis



This repository consists of files required for end to end implementation and deployment of Machine Learning NLP Restaurant Reviews Sentiment Analysis web application created with flask and deployed on the Heroku platform.



## App Link
If you want to view the deployed model, click on the following link:<br />
[ https://review-sentiment-by-abdulmanan.herokuapp.com/]( https://review-sentiment-by-abdulmanan.herokuapp.com/)



## About the App
The Restaurant Reviews Sentiment Analysis is a Flask web application which classifies/detects sentiments of customers as positive or negative sentiments. In this ML-NLP model, restaurant reviews dataset from Kaggle (also available in UCI ML Library) was used to perform Sentiment Analysis using Stemming and Bag of Words model to classify reviews into two sentiments — Liked(1) and Disliked(0). Since, the data is fairly balanced, we are only concerned with accuracy_score. From various Classifiers, highest accuracy achieved was 81% with cross_val_score of 79.4%.

 To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```
