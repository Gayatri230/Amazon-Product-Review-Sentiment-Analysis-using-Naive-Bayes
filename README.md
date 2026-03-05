# Amazon Product Review Sentiment Analysis

This project builds a machine learning model to classify Amazon product reviews into positive and negative sentiments using the Naive Bayes algorithm.

The goal of this project is to analyze customer reviews and automatically determine whether the sentiment of the review is positive or negative.

## Dataset

The dataset contains Amazon product reviews with information such as:

- Review Title
- Review Text
- Review Rating

The rating is used to generate sentiment labels.

Rating Conversion:
- Ratings 4 and 5 → Positive Sentiment
- Ratings 1 and 2 → Negative Sentiment
- Rating 3 → Removed to avoid neutral ambiguity

## Project Workflow

1. Data Loading using Pandas
2. Data Cleaning and Handling Missing Values
3. Feature Selection
4. Text Preprocessing
5. Feature Extraction using TF-IDF
6. Train-Test Split
7. Model Training using Multinomial Naive Bayes
8. Model Evaluation

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing
- TF-IDF Vectorization
- Matplotlib / Seaborn

## Model

The model used in this project is **Multinomial Naive Bayes**, which is commonly used for text classification problems such as spam detection and sentiment analysis.

## Evaluation Metrics

The model performance is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

## Results

The model successfully classifies product reviews into positive and negative sentiments based on textual features.

## Future Improvements

- Use advanced NLP techniques
- Try different algorithms like Logistic Regression or SVM
- Perform hyperparameter tuning
- Use deep learning models like LSTM or BERT
