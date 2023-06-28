# Sentiment Analysis of Hotel Reviews in Marrakesh

This repository contains the code and resources for performing sentiment analysis and aspect-based sentiment analysis of hotel reviews in Marrakesh. The project aims to develop automated techniques to classify the sentiment of hotel reviews and identify specific aspects related to customer experiences.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Approaches](#approaches)
- [Evaluation](#evaluation)
- [Results](#results)

## Introduction
Understanding customer sentiments expressed in hotel reviews is crucial for the hospitality industry. This project focuses on sentiment classification and aspect-based sentiment analysis of hotel reviews in Marrakesh. By employing machine learning techniques, the project aims to automate the analysis process and provide valuable insights for improving customer satisfaction.

## Dataset
The dataset used in this project consists of English hotel reviews obtained from TripAdvisor. The reviews were scraped using Selenium from the TripAdvisor website specifically for hotels in Marrakesh. The dataset contains a diverse range of customer sentiments.

## Installation
To run the code and reproduce the results, follow these steps:

1. Clone this repository:
   ```shell
   git clone https://github.com/Bouaskaoun/Sentiment-Analysis-On-Trip-Advisor-Hotel-Reviews.git
   cd Sentiment-Analysis-On-Trip-Advisor-Hotel-Reviews/

## Approaches
This project employs three different approaches for sentiment classification:

1. Term Frequency Inverse Document Frequency (TF-IDF)
   - This approach represents text documents as numerical vectors using TF-IDF weighting.
   - The TF-IDF vectors are used to train a machine learning classifier for sentiment classification.

2. Recurrent Neural Networks with Bidirectional Long Short-Term Memory (LSTM)
   - This approach utilizes LSTM, a type of recurrent neural network, to capture sequential information in text.
   - The LSTM model is trained on the hotel review data to classify sentiments.

3. Bidirectional Encoder Representations from Transformers (BERT)
   - BERT is a transformer-based model that learns contextual representations of words in text.
   - This approach fine-tunes a pre-trained BERT model on the hotel review data for sentiment classification.

## Evaluation
The sentiment classification models are evaluated using various evaluation metrics, including accuracy, precision, recall, and F1 score. The evaluation is performed on a test set of labeled reviews from the dataset. The results are analyzed to determine the effectiveness of each approach.

## Results
The results of the sentiment classification models and aspect-based sentiment analysis are presented in detail in the project report. The performance of each approach, including accuracy and other evaluation metrics, is discussed. The aspect-based sentiment analysis provides insights into the strengths and weaknesses of different hotels in Marrakesh.
