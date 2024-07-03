# IMDb Movie Reviews Sentiment Analysis using LSTM

## Overview
This project demonstrates how to use Long Short Term Memory (LSTM) neural networks to analyze sentiment in IMDb movie reviews. The model is trained to classify movie reviews as positive or negative and achieves an accuracy of 89%.

## Introduction
Sentiment analysis is a common task in natural language processing (NLP) where the goal is to determine the sentiment expressed in a piece of text. This project uses a deep learning approach with LSTM, a type of recurrent neural network (RNN), to perform sentiment analysis on IMDb movie reviews.

## Dataset
The dataset used in this project is the IMDb movie reviews dataset, which contains 50,000 reviews labeled as positive or negative. It can be downloaded from the [Kaggle website](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).

## Model Architecture
The LSTM model used in this project consists of the following layers:
- Embedding Layer: Converts the input words into dense vectors of fixed size.
- LSTM Layer: Processes the sequences of vectors to capture dependencies and context.
- Dense Layer: Outputs the final classification (positive or negative).

The model is trained using the binary cross-entropy loss function and the Adam optimizer.
