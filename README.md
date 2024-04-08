# SentimentalAnalysis_and_KeywordExtraction

Introduction:-
This repository contains code for sentiment analysis and keyword extraction from text data. Sentiment analysis is the process of determining the sentiment expressed in a piece of text, whether it's positive, negative, or neutral. Keyword extraction involves identifying the most important words in a text that represent its main topics or themes.

# Wikipedia Keyword-based Text Extraction

## Introduction

This Python script scrapes content from Wikipedia articles and extracts sentences containing user-specified keywords. It utilizes the Requests library to fetch web pages and the BeautifulSoup library for HTML parsing. The extracted sentences are then printed to the console.

## Features

- **Web Scraping**: Utilizes the Requests library to fetch HTML content from Wikipedia URLs.
- **HTML Parsing**: Utilizes the BeautifulSoup library to parse HTML content and extract relevant text.
- **Proprocessing**:Using Nltk library preprocess the data by removing stopwords,punctuation marks
- **Sentimental Analysis**:Analyze the sentiments of the URL’S -positive score,negative score and overall polarity.
- **User Interface using Tkinter**:Prompts user to enter URL and parses it to give sentiments.
- **Keyword-based Extraction**: Extracts sentences from the scraped text and visualize it.
- **Performance Metrics**:Considering Ground truth keywords for URL’S ,recall is calculated.

## Requirements

- Python 3.x
- requests library
- BeautifulSoup library
-nltk library
-re 
-matplotlib

## Usage
-- Clone the repository or download the script
-- Git clone https://github.com/Gayatri1626/SentimentalAnalysis_and_KeywordExtraction.git
-- Install necessary dependencies
   pip install requests beautifulsoup4
   Pip install re
  Pip install nltk
--run the script SentimentAnalysis_and_KeywordExtraction.py

## Customization

- **Keywords**: You can modify the script to add more urls,use pretrained models like GPT,BEERT to enhance performance.
- **Output**: You can customize the output format or save the extracted keywords to a file instead of printing them to the console.

## Acknowledgements

- This project was inspired by the need for extracting relevant information from Wikipedia articles based on user-specified keywords and anlyzing the sentiments.
- We would like to thank the contributors to the Requests ,BeautifulSoup and nltk libraries for enabling web scraping and HTML parsing functionalities.

## Contact

For any inquiries or feedback, please contact (gayatrighorpade409@gmail.com).
