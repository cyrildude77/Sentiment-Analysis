Sentiment Analysis Using Multiple Techniques
This project demonstrates sentiment analysis on text data using three different techniques:

TextBlob: A simple NLP library for polarity-based sentiment analysis.
VADER: A specialized tool for sentiment analysis, especially for social media and short texts.
Transformers (DistilBERT): A pre-trained transformer model (DistilBERT) for advanced sentiment analysis.
Features
Preprocess text data (remove punctuation, lowercase, numbers).
Perform sentiment analysis using three methods: TextBlob, VADER, and Hugging Face's DistilBERT.
Visualize sentiment distributions for each method using bar charts and histograms.
Calculate and compare sentiment scores across all methods.
Requirements
To run this project, you need to have Python 3.x installed along with the following libraries:

pandas
numpy
matplotlib
seaborn
textblob
vaderSentiment
transformers
re (Python's regular expression library)
Install Dependencies
Install all required libraries using pip:

bash
Copy code
pip install pandas numpy textblob vaderSentiment transformers matplotlib seaborn
Project Structure
bash
Copy code
├── sentiment_analysis.py   # Main Python script for sentiment analysis
├── README.md               # This file
└── requirements.txt        # Optional: List of dependencies
Python Script: sentiment_analysis.py
This Python script performs the following:

Data Preprocessing:

Cleans input text by converting it to lowercase, removing punctuation, and removing numbers.
Sentiment Analysis:

TextBlob: Computes polarity score.
VADER: Computes sentiment scores and returns compound score.
Transformers (DistilBERT): Uses a pre-trained model to classify text as positive or negative.
Visualization:

Sentiment distributions are visualized using:
Count Plots for sentiment labels from TextBlob and VADER.
Bar Plot for Transformers' sentiment distribution.
Histogram for the average sentiment score across all three methods.
