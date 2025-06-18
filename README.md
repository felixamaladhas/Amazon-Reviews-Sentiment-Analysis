# Amazon-Reviews-Sentiment-Analysis

# Objective
To analyze customer reviews from Amazon and determine their sentiment (Positive, Negative, or Neutral) using Natural Language Processing techniques.

# Business Understanding
Understanding customer feedback helps businesses improve products, services, and customer experience. This project aims to extract insights from customer reviews to support data-driven decisions.

# Dataset Description
The dataset contains Amazon product reviews with fields like Review Text, Rating, and Product Category. These are used to label and train sentiment classification models.

# Processing of Analysis
Data Cleaning: Removed duplicates, stopwords, and special characters.

Labeling: Sentiment labels assigned based on ratings (e.g., 1-2 = Negative, 3 = Neutral, 4-5 = Positive).

Feature Extraction: Applied TF-IDF/Bag of Words for vectorization.

Modeling: Trained models like Logistic Regression, Naive Bayes, and SVM.

Evaluation: Used accuracy, precision, recall, and F1-score to evaluate performance.

# Conclusion

We've performed a comprehensive analysis of the Amazon reviews dataset and built a simple sentiment analysis model. The analysis includes:

1. Basic statistics about the reviews
2. Distribution of review lengths
3. Most common words in positive and negative reviews
4. A TF-IDF based sentiment classification model
5. Analysis of the most important features for sentiment classification

The model can be improved further by:
1. Using more sophisticated text preprocessing
2. Trying different models (e.g., BERT, RoBERTa)
3. Performing hyperparameter tuning
4. Using cross-validation for more robust evaluation
