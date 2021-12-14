# CS_475_675 Group Project: Hate Speech Detection
dataset.csv: the original dataset - hate speech and offensive language <br>
from: https://data.world/thomasrdavidson/hate-speech-and-offensive-language  <br>
preprocessed_data.csv: save the preprocessed dataset into a new .csv file for word embedding and classification <br>
aug_data: save related data generated during the process of data augmentation <br>
aug_code: code for data augmentation, refer: https://arxiv.org/abs/1901.11196 <br>
hate_speech_classifier: the principle file, containing data analysis, visualization, data preprocess, train and test split, embedding and some simple machine learning models <br>
cnn_d2v_w2v: Extract word embeddings via Word2Vec (fastText) and Doc2vec. Create a CNN model for classification <br>
lstm_w2v: Extract word embeddings via Word2Vec. Create a simple LSTM model for classification <br>
lstm_d2v: Extract word embeddings via Doc2Vec. Use the same LSTM model as before for comparsion <br>
hate_speech_classifier-Bert: user pre-trained model Bert for this assignment <br>
