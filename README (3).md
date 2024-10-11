
# NLP EMOTION ANALYSIS 

# Emotion Classification in Text Using NLP

## Overview
This project focuses on developing machine learning models to classify emotions in text samples. Using Natural Language Processing (NLP) techniques, we preprocess the text data, extract meaningful features, and train classifiers to predict emotions from textual input.

## Dataset
The dataset used in this project is accessible [here](https://drive.google.com/file/d/1HWczIICsMpaL8EJyu48ZvRFcXx3_pcnb/view?usp=drive_link). It contains a collection of text samples labeled with corresponding emotions.

## Key Components
1. **Loading and Preprocessing**: 
   - Loaded the dataset and performed necessary preprocessing steps, including text cleaning, tokenization, and stopword removal.
   - Techniques such as stemming and lemmatization were applied to refine the text data.

2. **Feature Extraction**:
   - Implemented feature extraction using **TfidfVectorizer** to transform text data into numerical features suitable for machine learning models.

3. **Model Development**:
   - Trained multiple machine learning models, including:
     - Naive Bayes
     - Support Vector Machine (SVM)

4. **Model Comparison**:
   - Evaluated the models using accuracy and F1-score metrics to determine their performance in emotion classification.

## Requirements
- Python 3.x
- NLTK
- Scikit-learn
- Pandas
- NumPy

## Installation
To install the required libraries, run:
```bash
pip install nltk scikit-learn pandas numpy


