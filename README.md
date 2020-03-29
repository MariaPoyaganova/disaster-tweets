# disaster-tweets
This repository contains notebooks with codes used for the Kaggle competition "Real or Not? NLP with Disaster Tweets"

*The competition description*

Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).
The **goal** of the present competition is to predict which Tweets are about real disasters and which one’s aren’t. 

The team: Mazunina Zoya, Minnigulova Alina, Poyaganova Maria 

Preprocessing: SpaCy. 
Word representation techniques used: tf-idf, word2vec.
Models used: Logistic Regression, Sequential, CNN.
Transformer models used: RoBERTa, Albert.
The best score achieved: **0.82** on **RoBERTa Large** 

The repository contains 2 notebooks:
1) basic.ipynb - the implementation of simple word representations, LogReg and NN models.  
2) transfer.ipynb - the implementation of trasfer-learning techniques. 
The notebooks include comments in Russian. 

The data can be found on the page of the competition (https://www.kaggle.com/c/nlp-getting-started/data) 
