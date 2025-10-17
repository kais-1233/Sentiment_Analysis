# Sentiment Analysis on Amazon Product Reviews

This project performs **sentiment analysis** on **5,000 Amazon product reviews** using **VADER (Valence Aware Dictionary and Sentiment Reasoner)**.  
It classifies reviews into **Positive, Neutral, or Negative**, even for short or subtle reviews like "okay, not great" or negated phrases like "not good".

---

## Features

- **Text Cleaning & Preprocessing**: Lowercasing, punctuation removal, tokenization, and stopword removal.  
- **VADER Sentiment Analysis**: Accurate detection of Positive, Neutral, and Negative sentiments.  
- **Simple Prediction Function**: Real-time user review prediction.  
- **Optional ML Fallback**: You can extend with TF-IDF + Logistic Regression for strongly polarized reviews.  

---

## Dataset

The project uses a dataset of **5,000 Amazon reviews** with at least the following columns:

- `reviewText`: The text of the customer review.  
- `overall`: The rating given by the customer (1–5 stars).  

Example preview:

| reviewText                                   | overall |
|----------------------------------------------|--------|
| "No issues."                                 | 4      |
| "This product is bad!"                        | 1      |
| "I love this item!"                           | 5      |
| "The quality is okay, not great"             | 3      |
| "Worst product ever"                          | 1      |

 
 
