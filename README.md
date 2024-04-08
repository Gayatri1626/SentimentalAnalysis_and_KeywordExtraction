# SentimentalAnalysis_and_KeywordExtraction

## Introduction:-
This repository contains code for sentiment analysis and keyword extraction from text data. Sentiment analysis is the process of determining the sentiment expressed in a piece of text, whether it's positive, negative, or neutral. Keyword extraction involves identifying the most important words in a text that represent its main topics or themes.


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
1. Clone the repository	- Visit the GitHub repository: https://github.com/Gayatri1626/SentimentalAnalysis_and_KeywordExtraction.git <br> - Click on the green "Code" button <br> - Select "HTTPS" and copy the repository URL <br> - Open your terminal <br> - Navigate to the directory where you want to clone the repository <br> - Run git clone [repository URL] in the terminal
2. Download the script	- Visit the GitHub repository: https://github.com/Gayatri1626/SentimentalAnalysis_and_KeywordExtraction.git  <br> - Find the "Code" button and click on it <br> - Click on "Download ZIP" <br> - Extract the ZIP file to the desired directory on your computer
4. Install dependencies	Run all the required dependencies in your terminal to install the required dependencies(re,nltk,beautifulsoup4)
5. Run the script	Execute the script by running .py in your terminal


## Customization

- **Keywords**: You can modify the script to add more urls,use pretrained models like GPT,BEERT to enhance performance.
- **Output**: You can customize the output format or save the extracted keywords to a file instead of printing them to the console.

## Acknowledgements

- This project was inspired by the need for extracting relevant information from Wikipedia articles based on user-specified keywords and anlyzing the sentiments.
- We would like to thank the contributors to the Requests ,BeautifulSoup and nltk libraries for enabling web scraping and HTML parsing functionalities.

## Contact

For any inquiries or feedback, please contact (gayatrighorpade409@gmail.com).
