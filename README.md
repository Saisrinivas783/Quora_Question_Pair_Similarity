# Quora_Question_Pair_Similarity

## Overview

This project aims to identify duplicate questions on Quora using Natural Language Processing (NLP) and Machine Learning techniques. By accurately detecting similar questions, we can improve user experience and streamline knowledge sharing on the platform.

## Features

- Data preprocessing and feature extraction
- Implementation of various ML models:
  - Logistic Regression (baseline)
  - XGBoost
  - Siamese BERT
- Evaluation metrics including accuracy and Spearman's rank correlation

## Requirements
- Python
- Libraries: pandas, numpy, scikit-learn, xgboost, torch, transformers
- 
## Preprocessing
- Text cleaning
- Lemmatization
- Stopword removal
- Contraction expansion
- Special character handling

## Feature Extraction
- Basic features (question lengths, word counts)
- Word overlap features
- Token-based features
- Fuzzy string matching features
- TF-IDF weighted word vectors
- Additional features (question length ratios, Jaccard similarity, etc.)
  
## Results
- For Logistic Regression: Test Accuracy: 0.76137
- For XG-Boost : Test Accuracy: 0.82481
- For Bert: Test Loss: 0.0548, Test Correlation: 0.6199

## Future Work

- Implement more advanced NLP techniques
- Explore other deep learning architectures
- Optimize for scalability and real-time prediction

## Contributors

- Sai Srinivas Lakkoju
