![Uploading AdobeStock_747313106.jpeg…]()
# Spam Message Classification Using Average Word2Vec and LSTM

## Overview

This project aims to classify messages as spam or not spam using various machine learning techniques including Average Word2Vec, LSTM, TF-IDF, Bag of Words (BOW), and Recurrent Neural Networks (RNNs). 

## Methods Used

### 1. Average Word2Vec
- **Description:** Word2Vec is a popular word embedding technique used to transform words into vector representations. In this project, we calculate the average Word2Vec for all the words in each message to obtain fixed-length feature vectors for classification.

### 2. Long Short-Term Memory (LSTM)
- **Description:** LSTM is a type of recurrent neural network (RNN) capable of learning long-term dependencies. We utilized LSTM networks to capture the sequential nature of text data for better classification performance.

### 3. Term Frequency-Inverse Document Frequency (TF-IDF)
- **Description:** TF-IDF is a statistical measure used to evaluate the importance of a word in a document relative to a collection of documents. This technique helps in transforming the text data into numerical vectors that can be fed into machine learning algorithms.

### 4. Bag of Words (BOW)
- **Description:** BOW is a text representation technique that involves converting text into fixed-length vectors by counting the occurrences of each word in the text corpus. This simple yet powerful method helps in creating a vocabulary of known words.

### 5. Recurrent Neural Networks (RNNs)
- **Description:** RNNs are neural networks with loops, allowing information to persist. They are particularly effective in processing sequences of data, such as text, where the order of elements is crucial.
