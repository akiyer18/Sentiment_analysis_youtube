# Sentiment Analysis of YouTube Comments

This repository contains code for sentiment analysis of YouTube comments. The sentiment analysis process involves preprocessing the data using regular expressions, Pandas, NumPy, etc., to remove URLs, HTML code, emails, emojis, punctuation, and stopwords. The comments are then tokenized to convert sentences into a list of tokens. The polarity of the comments is determined using the TextBlob library. 

## Dataset Description

The dataset includes the following columns:
- Name
- Comments
- Time
- Like Counts
- Reply Counts
- Polarity
- Score

## Models

Three separate models were trained using the dataset:
1. Linear Regression
2. GloVe Algorithm
3. BERT Algorithm

## File Structure

- `Sentiment_Analysis.ipynb`: Implements sentiment analysis using various models.
- `Requirements.txt`: Contains the required Python libraries and dependencies.

## Usage

To run the sentiment analysis code:
1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the scripts for data preprocessing and sentiment analysis.


Feel free to contribute to this project by opening issues or pull requests!
