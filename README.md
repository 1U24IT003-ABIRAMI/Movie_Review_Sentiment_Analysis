# 🎬 Movie Review Sentiment Analysis

## Overview

The **Movie Review Sentiment Analysis** is an NLP-based machine learning system designed to analyze movie reviews and classify them as **Positive or Negative**. The project uses **Word2Vec** and **Sentence Transformer** embeddings to convert review text into meaningful numerical representations and applies different classification models.

## Objectives

* Analyze movie reviews automatically.
* Classify reviews into positive and negative sentiments.
* Convert textual reviews into numerical embeddings.
* Compare different machine learning and neural network models.
* Identify the best-performing model for sentiment classification.

## Technologies

* Python
* Pandas
* Word2Vec
* Sentence Transformers
* Random Forest
* Neural Network
* Scikit-learn
* TensorFlow / Keras

## Sentiment Analysis Workflow

```text
Movie Reviews
      ↓
Text Preprocessing
      ↓
Word2Vec / Sentence Transformer
      ↓
Feature Embeddings
      ↓
Classification Model
      ↓
Sentiment Prediction
      ↓
Positive / Negative
```

## Models Used

* Word2Vec + Random Forest
* **Sentence Transformer + Random Forest**
* Word2Vec + Neural Network
* Sentence Transformer + Neural Network

## Dataset

The dataset contains **9,982 movie reviews** with two main columns:

* **review** – Contains the movie review text.
* **sentiment** – Represents the sentiment, where **0 = Negative** and **1 = Positive**. 

## Key Features

* Movie review sentiment classification
* NLP-based text analysis
* Sentence Transformer embeddings
* Machine learning classification
* Positive and negative sentiment detection
* Model performance comparison
* 
## Conclusion

The project demonstrates the effectiveness of **NLP, Sentence Transformer embeddings, and Machine Learning** for movie review sentiment analysis. The **Sentence Transformer + Random Forest** model achieved a **72.81% test accuracy** and was selected as the best-performing model for classifying movie reviews.
