# final-year-project

# Stock Market Prediction Using Sentiment Analysis

## Overview
This project explores the application of deep learning and natural language processing techniques to predict stock market movements based on sentiment analysis. The study focuses on integrating sentiment extracted from news headlines and congressional tweets to predict price movements of the S&P 500 index.

## Project Structure
The repository consists of several Jupyter notebooks corresponding to different phases of the project:
- `LSTM_price_target.ipynb` - Initial LSTM model predicting closing prices using historical price data and experiments highlighting its limitationa
- `aggregate_daily_sentiment.ipynb` - Aggregation of sentiment scores from same-day news and tweets, with mean daily sentiment scores and sentiment metric.
- `sentiment.ipynb` - Sentiment analysis models comparison and dataset labelling using fine-tuned BERT models and LM dictionary.
- `predictive_models.ipynb` - Predictive models forecasting stock market movements.

## Datasets
The project utilizes the following external datasets:
- **[Financial PhraseBank](https://www.kaggle.com/datasets/ankurzing/sentiment-analysis-for-financial-news/data)**: Manually annotated sentences reflecting financial sentiments.
- **[S&P 500 News Dataset](https://github.com/pmoe7/Stock-Market-Data)**: A collection of news articles related to S&P 500 companies.
- **[Congress Tweets](https://github.com/alexlitel/congresstweets)**: Tweets from over 1000 campaign, office, committee, and party accounts related to U.S. Congress.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
