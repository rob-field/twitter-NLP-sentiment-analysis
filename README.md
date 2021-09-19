# twitter-NLP-sentiment-analysis

This repository includes a project that involves natural language processing (NLP) using a neural network, along with sentiment analysis of unseen tweets using the Twitter API.  
It highlights the use of:
- **Data processing/engineering in Python**
- **Machine learning pipelines and model optimisation** 
- **API functionality**
 
The dataset used was sourced from Kaggle (https://www.kaggle.com/praveengovi/emotions-dataset-for-nlp), and data preprocessing included encoding, tokenisation and embedding. Model hyperparameter tuning was carried out using Keras tuning, and the optimal hyperparameters were used during model training with early stopping, before model evluation was carried out on the test set. 

The tweepy was used to provide access to the Twitter API, therefore allowing functions to be defined that allow a user to pass a specific query term (either a search term or a hashtag) and a dataframe of tweets and relevant information (user, timestamp, location) was then returned. The pre-trained model could then be used to predict the sentiment of each tweet.
