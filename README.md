# TCS-iON-RIO-125---Automate-emotion-analysis-of-textual-comments-and-feedback

# Project Overview:
This project was developed as part of the TCS iON RIO 125 internship program, a three-month initiative focused on automating emotion analysis within textual comments and feedback. The primary objective was to create a system capable of recognizing and categorizing emotions such as sadness, joy, love, anger, fear, and surprise expressed in text data.

# Project Environment:

* Programming Environment: Google Colab – Jupyter Notebook, Anaconda Navigator.

* Tools Utilized: Hugging Face Dataset (leveraging the 'emotion' dataset), NLTK, LSTM, TensorFlow 2.0, Keras.

# Dataset

For this project I have used HuggingFace Emotion dataset. Emotion is a dataset of English Twitter messages with six basic emotions: anger, fear, joy, love, sadness, and surprise. The dataset comprises two columns, namely 'text' and 'label.' The 'text' column contains strings consisting of tweets from different users, while the 'label' column consists of categorical values representing emotions. These emotions include sadness (0), joy (1), love (2), anger (3), fear (4), and surprise (5).

https://huggingface.co/datasets/dair-ai/emotion
# Description

Using Google Colab's Jupyter Notebook environment, this project harnessed the power of Natural Language Processing (NLP) techniques and deep learning methodologies. The main focus was on sentiment analysis, specifically targeting textual feedback and comments. The project incorporated the Hugging Face 'emotion' dataset, along with various tools such as NLTK for text preprocessing, LSTM neural networks for sequence modeling, and TensorFlow/Keras for building and training deep learning models.

# Key Objectives Achieved

* Text Preprocessing: Utilized NLTK for tokenization, stopwords removal, and lemmatization.
  
* Model Building: Constructed Bidirectional LSTM (Long Short-Term Memory) neural networks using TensorFlow 2.0 and Keras.
  
* Training and Validation: Trained the model to recognize emotional states in text data using the provided 'emotion' dataset.

* Evaluation and Prediction: Evaluated model performance and made emotion predictions on test data.

# Future Work

The project sets the stage for further enhancements and extensions. Future work could involve refining the model's accuracy, exploring additional datasets, incorporating advanced deep learning techniques, and deploying the system for real-time emotion analysis in diverse textual contexts.
