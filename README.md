# BBC Article Sentiment Analysis

Utilized GCP services (Machine Learning API, Cloud Storage) and Spreedsheets to conduct Sentiment Analysis on BBC article data. The goal was to explore if the category of a article will affect it's sentiment score.

## Data
We used a public dataset from the BBC comprised of 2225 articles, each labeled under one of 5 categories: business, entertainment, politics, sport or tech.

The dataset is broken into 1490 records for training and 735 for testing.

data source:
https://www.kaggle.com/competitions/learn-ai-bbc/overview


## Google NLP API
We used the Natural Language API to perform sentiment analysis on each of the article text data.
API information:
https://cloud.google.com/natural-language/docs/analyzing-sentiment
