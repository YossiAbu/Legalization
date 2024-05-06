# Legalization
Investigating the discourse on legalization in the Twitter social network


## Problem Statement

The aim of this project is to explore public opinions on the legalization of drugs and weapons among different internet users, particularly on the social network Twitter. We will analyze various perspectives, considering both viewpoints for and against legalization. To achieve this, we will utilize natural language processing (NLP) tools to analyze and extract data from public discourse on Twitter, providing a comprehensive overview of the conversation surrounding legalization.

## Dataset Information

Our dataset is sourced from Twitter using the sntwitter tool of the snscrape library. This powerful tool enabled us to gather a significant volume of data collected over the period of 2015-2022. The dataset comprises more than 30 million tweets, providing a rich source of information for our investigation into public sentiment towards the legalization of drugs and weapons.

We carefully curated a dataset focusing on tweets with high engagement (measured by likes, replies, and retweets) to ensure relevance and meaningfulness. The data collection process spanned several months, covering 16 pre-defined topics related to legalization, ensuring broad coverage of public opinion on key social issues.

To ensure data quality and relevance, we eliminated entries with NaN values and aimed for a balanced dataset by selecting approximately 10,000 tweets for each topic. We also balanced the dataset by year to avoid temporal bias. After preprocessing, our dataset was reduced to 150,000 tweets, maintaining robustness and representativeness.

## Repository Structure

- `Data Organization.ipynb`: Jupyter Notebook for preprocessing and cleaning the data.
- `EDA.ipynb`: Jupyter Notebook for exploratory data analysis on the clean data.
- `Model.ipynb`: Jupyter Notebook containing the model built on the data, attempting to predict the topic of the tweet.
- `Tweets Downloader New.ipynb`: Jupyter Notebook detailing the process of downloading tweets.
- `sentiment_df.csv`: Dataset containing the cleaned and preprocessed tweet data.
