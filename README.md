# Twitter Sentiment Analysis

A Python-based project for performing sentiment analysis on Twitter data.

## Table of Contents

- [Introduction](#twitter-sentiment-analysis)
- [Installation](#installation)
- [Usage](#usage)
- [Data Collection](#data-collection)
- [Sentiment Analysis](#sentiment-analysis)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to analyze the sentiment of tweets gathered from Twitter. It employs Natural Language Processing (NLP) techniques to classify tweets as positive, negative, or neutral, providing insights into the overall sentiment of a specific topic, keyword, or hashtag on Twitter.

## Installation

To set up the project locally, follow these steps:

1. Clone this repository:
2. Install the required Python packages:


## Usage

To perform sentiment analysis on Twitter data, use the following steps:

1. Obtain Twitter API credentials (consumer key, consumer secret, access token, and access token secret) and update the `config.py` file.

2. Run the data collection script to gather tweets based on a specific keyword, hashtag, or user:

3. Analyze the sentiment of the collected tweets:


4. View the results and visualizations in the generated output files.

## Data Collection

We collect Twitter data using the Twitter API. Ensure you have valid API credentials and specify your search parameters in the `collect_tweets.py` script.

## Sentiment Analysis

We use a pre-trained NLP model to perform sentiment analysis on the collected tweets. The sentiment labels include positive, negative, and neutral.

## Results

View the sentiment analysis results in the output files generated during the analysis process.

We got 84% accuracy on SVM( Support vector machine algorithm)

## Contributing

We welcome contributions from the community. Feel free to fork this repository, make improvements, and submit pull requests.

