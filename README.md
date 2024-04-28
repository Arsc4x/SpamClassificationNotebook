# Spam Classifier

## Overview
This project focuses on building a spam classifier to distinguish between spam and non-spam ("ham") messages. The classifier utilizes several machine learning models to evaluate their effectiveness in spam detection.

## Dataset
The dataset used in this project consists of two columns:
- `text_type`: Indicates the type of the message, where "ham" represents a normal message and "spam" signifies a spam message.
- `text`: The actual text of the message.

## Methodology

### Data Preparation
The dataset is split into training and testing sets to evaluate the performance of the models.

### Preprocessing
Text data is preprocessed and vectorized using the TF-IDF (Term Frequency-Inverse Document Frequency) method to transform text into a suitable format for model training.

### Modeling
Several models are explored in this project:
- Support Vector Machine (SVM)
- Naive Bayes
- Random Forest
- Catboost
- XGBoost
- Logistic Regression
- Stacking Classifier
- Fully connected Neural Network
- Recurrent Neural Networks (RNN, Bidirectional LSTM, GRU)

### Model Selection
Models are evaluated based on their performance metrics, and the best performing model is selected.

