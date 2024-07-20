# SENTIMENT ANALYSIS USING LSTM ARCHITECTURE
This project demonstrates a sentiment analysis model using Long Short-Term Memory (LSTM) networks. The objective is to classify text data into positive or negative sentiment based on the content of the text. LSTM networks are a type of recurrent neural network (RNN) capable of learning order dependence in sequence prediction problems, making them particularly suited for text classification tasks like sentiment analysis.

## Dataset

The dataset used for this project is the [Twitter US Airline Sentiment](https://www.kaggle.com/crowdflower/twitter-airline-sentiment) dataset from Kaggle. It contains tweets about different airlines with sentiment labels (positive, neutral, negative).

## Requirements

- Python 3.7 or higher
- TensorFlow 2.x
- Keras Tuner
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- NLTK

## Model Architecture

The deep learning model used in this project is a bidirectional LSTM with dropout layers to prevent overfitting. The architecture is as follows:

- Embedding Layer
- Spatial Dropout Layer
- Bidirectional LSTM Layer
- Dropout Layer
- Bidirectional LSTM Layer
- Dense Layer with Sigmoid Activation



