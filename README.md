## Devanagari-Sentiment-Analysis
"Devanagari Sentiment Analysis" is a project aimed at analyzing sentiments in text data written in Devanagari script, which is used for languages like Hindi, Marathi, Punjabi & Gujarati. The project includes tools for preprocessing Devanagari text, training machine learning models for sentiment classification, and visualizing sentiment distributions through word clouds and sentiment scores. It provides insights into the emotional content of Devanagari text data, aiding in understanding public opinion, sentiment trends, and user feedback in Devanagari languages.

## Overview
Devanagari Sentiment Analysis is a project to analyze sentiment in text written in the Devanagari script. It includes data preprocessing, feature engineering, model training, evaluation, and visualization.

## Description
This project aims to perform sentiment analysis on text data written in the Devanagari script, which is commonly used for languages like Hindi, Marathi, Punjabi, and Gujarati. The goal is to develop machine learning models that can classify text into positive, negative, or neutral sentiment categories.

## Dataset Source
The project utilizes various datasets containing text data in Devanagari script, sourced from social media, news articles, and other online platforms. These datasets are preprocessed and labeled for sentiment analysis tasks.

## Project Approach
The sentiment analysis task is approached as a supervised learning problem, where machine learning algorithms, particularly Random Forest, are trained on the preprocessed text data to predict sentiment labels. Text preprocessing techniques such as tokenization, stemming, and vectorization are employed to convert raw text into numerical features suitable for model training.

## Why Random Forest
1. Robustness: Random Forest is robust to overfitting and performs well on a variety of datasets without much tuning of hyperparameters. This makes it suitable for handling diverse text data in different languages.

2. Ensemble Learning: Random Forest is an ensemble learning method that combines multiple decision trees to improve generalization and robustness. This allows it to capture complex relationships in the data and make accurate predictions.

3. Feature Importance: Random Forest provides a measure of feature importance, which can help understand the most influential features in the text data for sentiment analysis. This can aid in feature selection and interpretation of the model.

4. Handling Imbalanced Data: Random Forest can handle imbalanced datasets well, which is common in sentiment analysis tasks where the distribution of sentiment labels may be skewed.

5. Scalability: Random Forest is parallelizable and can handle large datasets efficiently. This makes it suitable for scaling up to larger text corpora if needed.

## Evaluation
The performance of the trained models is evaluated using standard evaluation metrics such as accuracy, precision, recall, and F1-score. Confusion matrices and classification reports are generated to analyze the models' performance on different sentiment categories.

## Visualization
Word clouds and other visualization techniques are employed to gain insights into the most common words and sentiments present in the text data. These visualizations help in understanding the dataset's characteristics and the trained models' behavior.

## Features
- Preprocessing of text data
- TF-IDF vectorization for feature extraction
- Training and evaluation of machine learning models
- Visualization of evaluation metrics and sentiment analysis results

## Datasets
- Hindi Sentiment Analysis Dataset
- Punjabi Sentiment Lexicon
- Gujarati Sentiment Analysis Dataset
- Marathi Sentiment Analysis Dataset

## Installation
1. Clone the repository:
`git clone https://github.com/yourusername/devanagari-sentiment-analysis.git`
3. Install dependencies:
`pip install -r requirements.txt`

## Usage
1. Explore the notebooks in the `notebooks` directory for detailed analysis and code execution.
2. Run scripts in the `scripts` directory for specific tasks such as data preprocessing, model training, and evaluation.
3. Modify the code to fit your dataset or experiment with different models.

## Contributors
- [Yash Ashok Shirsath](https://yashashokshirsath.netlify.app/)

## License

This project is licensed under the [![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT).

