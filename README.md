# Stock-Movement_Analysis
This project focuses on predicting stock market trends (upward or downward movement) using deep learning techniques. The model is designed to analyze sequential stock market data and provide binary trend predictions, utilizing various machine learning models


## Features
 **Data Scraping: Used a scraping technique to gather real time and historical data
   Collect user-generated content like reddit posts, or messages containing stock-related keywords and i focused in communities like subreddits, uses library like 
   praw to extract data

**Sentiment Analysis:** NLP are applied to analyze the sentiment of content.
   Help understand the public's emotional response to market trends

 **Stock Prediction:** Builds a machine learning model to predict stock movement trends based on sentiment and features.
    Train the model using historical stock data and social media sentiment trends to understand correlations.

 **Modular Design:** Includes separate modules for scraping, preprocessing, and prediction.
      Scraping Module: Handles data collection from social media platforms using APIs or scraping libraries.
      Preprocessing & sentiment Module: Cleans and processes raw data into a structured format suitable for analysis.
      Prediction Module: Trains the machine learning model and generates predictions on stock trends.


## Installation Instructions

Follow these steps to set up and run the project on your local machine:

1. Clone the repository:

   git clone <repository-url>
   cd stock-sentiment-analysis

2. Install required python libraries
   pip install -r requirements.txt

3. Add api key of your chosen platform
 {
  "API_KEY": "your_api_key",
  "API_SECRET": "your_api_secret",
  "ACCESS_TOKEN": "your_access_token",
  "ACCESS_SECRET": "your_access_secret"
 }

Step-1 
 Scrape the social media data of your chosen platform
	python scraping.py

Step-2
 Preprocess and Analyze the Data
       python preprocessing.py
Step-3
 Train and evaluate the Model
      python model.py

## Dependencies and Requirements
  
This project uses the following Python libraries:

- **praw**: For Reddit scraping.
- **nltk**: For natural language processing.
- **textblob**: For sentiment analysis.
- **scikit-learn**: For building machine learning models.
- **pandas**: For data manipulation.
- **matplotlib/seaborn**: For visualizations.

Install all dependencies using:
pip install -r requirements.txt

## Results
The project demonstrates:
- **Data Insights:** Sentiment analysis graphs and key trends.
- **Model Performance:** 
  - Accuracy: 100%
  - Precision: 1
  - Recall: 1
  - F1-Score: 1


  



