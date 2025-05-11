# Sentiment_Analysis_Tweets

# Beginner Sentiment Analysis on Tweets (NLP Project)

This is my **first Natural Language Processing (NLP)** project, created as part of my learning journey. It uses a large dataset of tweets to classify sentiment as **positive or negative** using Logistic Regression.

I followed step-by-step instructions to:
- Preprocess and clean tweet text
- Convert it into numerical features using TF-IDF
- Train a Logistic Regression model
- Evaluate the model’s performance

### Dataset
- **Source**: [Sentiment140 (Kaggle)](https://www.kaggle.com/datasets/kazanova/sentiment140)
- **Size**: 1.6 million tweets
- **Labels**: 0 (negative), 4 (positive) – I converted 4 into 1 to simplify it into a binary classification

### Steps I Performed
- Loaded and explored the dataset
- Cleaned the tweets (removed punctuation, links, etc.)
- Used `TfidfVectorizer` to turn text into features
- Trained a logistic regression model
- Evaluated accuracy and visualized the confusion matrix

### Results
- **Accuracy**: ~79%
- The model does well in identifying both positive and negative tweets

### What I Learned
- How to clean and prepare text data
- Basics of TF-IDF and how it transforms text
- How to train a simple model on unstructured data
- How to interpret basic model evaluation metrics



This project is part of my goal to learn NLP and apply for internships in the field. I'm currently learning through projects like this and planning to take a full NLP course next.
