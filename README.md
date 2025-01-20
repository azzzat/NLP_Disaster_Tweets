# 📝 Disaster Tweet Classification

This repository contains an end-to-end machine learning pipeline to classify tweets as either related to a disaster or not. The project uses various natural language processing (NLP) techniques, including tokenization, stemming, and deep learning architectures like RNNs and LSTMs, to achieve high classification accuracy. The dataset comes from Kaggle, where tweets related to disasters are labeled for binary classification.

## 🧠 Problem Statement

The goal is to predict whether a tweet is related to a disaster or not based on its content. The dataset contains a mix of disaster and non-disaster tweets, and the challenge is to preprocess the text data effectively and build a model that performs well on unseen data.

## ⚙️ Key Features

Exploratory Data Analysis (EDA):

    Distribution of disaster and non-disaster tweets.
    Analysis of missing values and duplicates.

Data Preprocessing:

    Removal of irrelevant features (like location, keyword).
    Text cleaning using cleantext and stemming to normalize text.
    Tokenization and padding to prepare data for model training.

Model Training:

    Recurrent Neural Networks (RNNs) and Long Short-Term Memory (LSTM) models for sequential data processing.
    Models are evaluated with accuracy and loss metrics.

Deep Learning Techniques:

    LSTM Model: Built with a bidirectional LSTM layer for capturing long-range dependencies.
    RNN Model: A simpler RNN architecture for baseline performance.

## 🔍 Results

    RNN Model: Achieved 91.34% accuracy on the test set.
    LSTM Model: Achieved 93.11% accuracy, showing better performance for sequential data.

The LSTM model performed better by capturing long-term dependencies in the text.

## 🛠️ Tools & Libraries

    Python: Core programming language for the project.
    Pandas, NumPy: Data manipulation and preprocessing.
    Matplotlib, Seaborn: Visualization.
    TensorFlow, Keras: Deep learning frameworks for building and training neural networks.
    NLTK, cleantext: Text processing and cleaning.
    Scikit-learn: For data splitting, evaluation, and metrics.
