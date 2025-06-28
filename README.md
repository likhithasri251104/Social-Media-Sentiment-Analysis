# 🐦 Twitter Sentiment Analysis using Python

This project performs sentiment analysis on tweets using the Twitter API, `TextBlob`, and data visualization libraries like `matplotlib` and `seaborn`. It collects live tweets, processes them, analyzes sentiment polarity, and classifies sentiments into **Positive**, **Neutral**, or **Negative**.

---

## 📘 Overview

- **Tweet Source:** Twitter (via Tweepy and Twitter Developer API)
- **Analysis Tools:** TextBlob for sentiment polarity
- **Visuals:**
  - Word Cloud of tweet content
  - Sentiment polarity histogram
  - Sentiment classification bar chart

---

## 🚀 Features

- Fetch tweets using keyword or hashtag
- Clean raw tweet text (remove URLs, mentions, hashtags, etc.)
- Compute sentiment polarity score using TextBlob
- Visualize:
  - Sentiment distribution (histogram)
  - WordCloud of the most frequent words
  - Sentiment classification counts

---

## 🛠️ Technologies & Libraries Used

- Python
- Tweepy
- TextBlob
- Matplotlib
- Seaborn
- WordCloud
- re, nltk (text preprocessing)

---

## 🔐 Twitter API Setup

1. Create a [Twitter Developer Account](https://developer.twitter.com/)
2. Create a new project and generate:
   - API Key
   - API Secret Key
   - Access Token
   - Access Token Secret
3. Replace the placeholder values in the script:

```python
API_KEY = 'YOUR_API_KEY'
API_SECRET_KEY = 'YOUR_API_SECRET_KEY'
ACCESS_TOKEN = 'YOUR_ACCESS_TOKEN'
ACCESS_TOKEN_SECRET = 'YOUR_ACCESS_TOKEN_SECRET'


Installation
Make sure the following Python packages are installed:

pip install tweepy textblob wordcloud matplotlib seaborn nltk



Also run this to download stopwords if using them:

import nltk
nltk.download('sto





Notebook

📊 Visual Output
Word Cloud of top keywords in tweets

Sentiment Polarity Histogram showing distribution from -1 (negative) to +1 (positive)

Bar Chart showing count of Positive, Neutral, and Negative tweets




Sentiment Classification Logic

if sentiment > 0:
    return "Positive"
elif sentiment == 0:
    return "Neutral"
else:
    return "Negative"



Project Structure

twitter-sentiment-analysis/
├── twitter_sentiment_analysis.py   # Main script
├── README.md                       # Project documentation



📌 Example Use Cases
Brand sentiment analysis

Product feedback mining

Political opinion tracking

Social trend monitoring




