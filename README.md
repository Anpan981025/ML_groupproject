# CS_475_675 Group Project: Hate Speech Detection
## Introduction
Hate speech and offensive language have plagued the online community for years and are found to be closely linked to adolescent depression. Our project aims to use simple Machine Learning algorithms (Decision Tree, Logistic regression, Naive Bayes etc.) as well as more complex models (CNN, LSTM, Bert) to identify hate speech in preprocessed Twitter Tweets.

## Dataset
We use the dataset ‘Hate Speech and Offensive Language’, which has 24k tweets labeled as hate speech, offensive language, or neither. <br>
From: https://data.world/thomasrdavidson/hate-speech-and-offensive-language 

## Description of Files
dataset.csv: the original dataset - hate speech and offensive language <br>
preprocessed_data.csv: save the preprocessed dataset into a new .csv file for word embedding and classification <br>
aug_data: save related data generated during the process of data augmentation <br>
aug_code: code for data augmentation, refer: https://arxiv.org/abs/1901.11196 <br>
hate_speech_classifier: the principle file, containing data analysis, visualization, data preprocess, train and test split, embedding and some simple machine learning models <br>
cnn_w2v: Extract word embeddings via Word2Vec (fastText) and Doc2vec. Create a CNN model for classification <br>
lstm_w2v: Extract word embeddings via Word2Vec. Create a simple LSTM model for classification <br>
lstm_d2v: Extract word embeddings via Doc2Vec. Use the same LSTM model as before for comparsion <br>
hate_speech_classifier-Bert: user pre-trained model Bert for this assignment <br>
