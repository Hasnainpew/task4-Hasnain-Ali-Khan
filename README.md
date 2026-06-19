# Sentiment Analysis Using NLP and Naive Bayes

## Overview

This project was completed as part of the Decode Labs Data Science Internship.

The objective of this project is to analyze movie reviews and classify them as Positive or Negative using Natural Language Processing (NLP) techniques and a Machine Learning model.

---

## Dataset

Dataset: IMDB Movie Reviews Dataset

The dataset contains thousands of movie reviews along with their sentiment labels:

- Positive
- Negative

---

## Project Workflow

### 1. Data Loading
- Imported dataset into Python
- Examined dataset structure

### 2. Data Exploration
- Checked dataset dimensions
- Analyzed sentiment distribution
- Inspected sample reviews

### 3. Text Preprocessing
Applied NLP preprocessing techniques:

- Lowercasing text
- Removing special characters
- Tokenization
- Stopword removal
- Lemmatization

### 4. Feature Extraction
Used TF-IDF (Term Frequency-Inverse Document Frequency) to convert text into numerical features suitable for machine learning.

### 5. Train-Test Split
- Training Data: 80%
- Testing Data: 20%

### 6. Model Building
Implemented:

- Multinomial Naive Bayes Classifier

### 7. Model Evaluation
Evaluated model performance using:

- Accuracy Score

### 8. Sentiment Prediction
Tested the model on custom movie reviews and predicted:

- Positive Sentiment
- Negative Sentiment

---

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TF-IDF Vectorizer
- Multinomial Naive Bayes
- Google Colab

---

## Machine Learning Concepts Used

- Natural Language Processing (NLP)
- Text Cleaning
- Tokenization
- Stopword Removal
- Lemmatization
- TF-IDF Vectorization
- Classification
- Naive Bayes Algorithm

---

## Results

- Successfully converted textual reviews into machine-readable features.
- Built a sentiment classification model using Naive Bayes.
- Achieved high accuracy on IMDB movie review data.
- Successfully predicted sentiment for unseen reviews.

---

## Sample Predictions

### Positive Review
```
This movie was amazing and fantastic.
```

Prediction:
```
Positive
```

### Negative Review
```
This movie was terrible and boring.
```

Prediction:
```
Negative
```

---

## Conclusion

This project demonstrates the complete NLP workflow, from text preprocessing and feature extraction to machine learning-based sentiment classification. The model can effectively identify customer opinions and classify movie reviews into positive and negative sentiments.

---

## Internship

Completed as part of the Decode Labs Data Science Internship Program.
