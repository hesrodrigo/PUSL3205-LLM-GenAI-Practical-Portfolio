 # Lab 01 - Sentiment Analysis Using Traditional Machine Learning

## Overview
This lab focuses on building a basic sentiment analysis model using Natural Language Processing (NLP) and Machine Learning. The main objective was to classify customer reviews as positive or negative using text data.

## Objectives
- Explore and understand the given review dataset.
- Perform text preprocessing and cleaning.
- Apply Bag-of-Words for feature extraction.
- Train a Logistic Regression classification model.
- Evaluate the model using different performance metrics.
- Test the model with new sentences.

## Tools and Libraries
- Python
- Google Colab
- Pandas and NumPy
- NLTK
- Scikit-learn
- Matplotlib

## Implementation
The practical involved loading and exploring the Amazon, IMDb and Yelp review datasets, cleaning the text data, removing stop words and analysing frequently occurring words.

The processed text was converted into numerical features using Bag-of-Words. A Logistic Regression model was then trained using an 80:20 train-test split.

## Results
The Logistic Regression model achieved an accuracy of **82.83%** on the test dataset.

The model was also evaluated using precision, recall, F1-score and a confusion matrix. Additionally, six new sentences were tested to observe how the model predicts unseen reviews.

## Conclusion
Through this practical, I gained a better understanding of text preprocessing, feature extraction and sentiment classification. I also learned how to train and evaluate a machine learning model using Python.

Overall, this lab provided practical experience in applying basic NLP techniques to a real-world text classification problem.
