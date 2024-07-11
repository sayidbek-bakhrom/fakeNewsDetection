# Fake News Detection

## Overview

This repository contains a machine learning model for fake news detection. The project includes a text preprocessing pipeline and a `RandomForestClassifier` model to classify news articles as either "Real" or "Fake." The preprocessing pipeline includes text normalization steps such as lemmatization and stopword removal, and the classifier uses TF-IDF features for prediction.

## Features

### Text Preprocessing

- **Removal of Special Characters and Punctuation**: Clean the text data by removing non-alphanumeric characters.
- **Conversion to Lowercase**: Standardize the text by converting all characters to lowercase.
- **Tokenization**: Split text into individual words (tokens).
- **Lemmatization**: Reduce words to their base or root form.
- **Stopword Removal**: Filter out common words that are not useful for classification.

### Machine Learning Model

- **RandomForestClassifier**: A robust classifier for binary classification tasks.
- **TF-IDF Vectorization**: Converts text data into numerical features based on term frequency-inverse document frequency.

### Prediction

- **Predicts** whether a given news article is fake or real based on the trained model.
