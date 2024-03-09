# Data Mining Labs Overview

This repository contains materials and instructions for two lab sessions focused on applying data mining techniques to analyze textual data. The primary goal of these labs is to apply theoretical knowledge from the Data Mining course in practical scenarios, including data visualization, feature generation, and classification.

## Lab 1: Text Data Analysis and Classification

### Objective

The objective of Lab 1 is to follow a predefined process for data analysis on a new dataset, leveraging and modifying existing code when necessary. This lab focuses on generating TF-IDF features, data visualization, and implementing Naive Bayes classifiers.

### Tasks

1. **Dataset Download and Preparation**: Download the new dataset containing sentences and score labels. Read the dataset's specifications for details.

2. **Data Analysis**:
   - Generate meaningful new data visualizations. Look for inspiration in online resources and the Data Mining textbook.
   - Generate TF-IDF features from the tokens of each text, creating a document matrix with TF-IDF values instead of word frequency.
   - Implement two Naive Bayes classifiers using TF-IDF features and word frequency features, respectively. Compare the differences.

### Instructions

- You are allowed to use and modify the helper functions from the first lab session's folder or create your own.
- Minimal comments explaining your code are appreciated for clarity.

### References

- For TF-IDF feature generation, refer to the [Scikit-learn guide](https://scikit-learn.org/stable/modules/feature_extraction.html#tfidf-term-weighting).
- For Naive Bayes implementation, consult [this article](https://towardsdatascience.com/naive-bayes-classifier-81d512f50a7c).

## Lab 2: Twitter Emotion Classification

### Description

In this competition-based lab, participants are provided with a dataset crawled from Twitter, labeled with emotions based on specific hashtags in the original text. The dataset includes 8 emotions: anger, anticipation, disgust, fear, sadness, surprise, trust, and joy.

### Objective

Your task is to clean and preprocess the data, apply feature engineering or any other relevant data mining techniques, and develop a model capable of predicting the emotion of each tweet.

### Instructions

- Begin by cleaning the data to remove noise and unnecessary information.
- Apply feature engineering or explore other data mining techniques discussed in the course.
- Develop and train a model to predict tweet emotions accurately.
