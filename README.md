# Project Overview
This repository contains code for analyzing disaster-related tweets using Natural Language Processing **(NLP)** techniques. The goal is to classify tweets as containing information about a **disaster or not**.

## Dataset
The dataset used for this project is the **Disaster Tweets** Dataset. It consists of a **CSV file** containing the following columns:

- **id**: Unique identifier for the tweet. 
- **keyword**: Keyword extracted from the tweet.
- **location**: Location mentioned in the tweet. 
- **text**: The full text of the tweet.
- **target**: Label indicating whether the tweet is about a disaster **(1) or not (0)**.

## Code Structure
The code is organized into the following Python files:

- **data_preprocessing.py**: Preprocesses the tweet data, including cleaning, tokenization, and feature extraction.
- **model_training.py**: Trains various NLP models (e.g., Naive Bayes, Random Forest, Support Vector Machine) on the preprocessed data.
- **model_evaluation.py**: Evaluates the trained models using metrics like accuracy, precision, recall, and F1-score.
- **prediction.py**: Uses a trained model to predict whether a new tweet is about a disaster or not.

## Requirements
To run the code, you'll need the following Python libraries:

- pandas
- numpy
- nltk
- scikit-learn
- matplotlib
- seaborn
