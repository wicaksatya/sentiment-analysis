# Sentiment Analysis of Twitter Data using Support Vector Classifier (SVC)

## Introduction

In this project, we will perform sentiment analysis on Twitter data using a Support Vector Classifier (SVC). Sentiment analysis involves classifying the polarity of a given text, which can be positive, negative, or neutral. Here, we will use a dataset of tweets and classify them as positive or negative.

## Dataset

The dataset used for this project consists of Indonesian tweets labeled with sentiments (e.g., positive and negative)

## Project Overview

1. **Data Preprocessing**: Cleans and prepares text data for machine learning. This may involve steps like tokenization, removing stop words, and stemming/lemmatization.
2. **Feature Extraction**: Convert tweets into numerical features using techniques such as TF-IDF.
3. **Model Training**: Train a Support Vector Classifier (SVC) on the extracted features.
4. **Model Evaluation**: Evaluate the performance of the classifier using metrics such as accuracy, precision, recall, and F1-score.

## Prerequisites
Ensure you have the following libraries installed:
- `pandas`
- `scikit-learn`
- `nltk`
- `Sastrawi`
- `matplotlib`
- `wordcloud`

## Usage
1. **Clone the repository:**
   `git clone git@github.com:wicaksatya/sentiment-analysis.git`
2. **Preprocess data:**
   Edit the `sentiment-analysis.ipynb` script to load your text data and perform and adjust necessary preprocessing steps to your dataset.

## Additional Notes
* This project assumes you have a pre-labeled dataset for sentiment analysis.
* You can find sentiment analysis datasets online from various sources.
