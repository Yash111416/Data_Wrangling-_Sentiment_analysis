# Data Wrangling and Sentiment Analysis

## Introduction
This project involves data wrangling from 113 websites using Beautiful Soup for web scraping, followed by sentiment analysis. The sentiment analysis includes calculating various scores such as Positive Score, Negative Score, Polarity Score, Subjectivity Score, Average Sentence Length, Percentage of Complex Words, Fog Index, Average Number of Words per Sentence, Complex Word Count, Word Count, Syllables per Word, Personal Pronouns, and Average Word Length.

## Data Wrangling
- **Method**: Data wrangling is performed using Beautiful Soup, a Python library for pulling data out of HTML and XML files.
- **Websites**: Information is extracted from 113 websites using web scraping techniques.
- **Data Extraction**: Relevant text data is extracted from the HTML content of each webpage.
- **Cleaning**: Text data is cleaned to remove unnecessary characters, HTML tags, and noise.

## Sentiment Analysis
- **Objective**: The main objective of sentiment analysis is to analyze the sentiment of the extracted text data.
- **Metrics Calculated**:
  - **Positive Score**: Number of positive words in the text.
  - **Negative Score**: Number of negative words in the text.
  - **Polarity Score**: Difference between the positive and negative scores.
  - **Subjectivity Score**: Degree of subjectivity in the text.
  - **Average Sentence Length**: Mean length of sentences in the text.
  - **Percentage of Complex Words**: Percentage of words considered complex in the text.
  - **Fog Index**: Measure of readability.
  - **Average Number of Words per Sentence**: Mean number of words per sentence.
  - **Complex Word Count**: Number of complex words in the text.
  - **Word Count**: Total number of words in the text.
  - **Syllables per Word**: Average number of syllables per word.
  - **Personal Pronouns**: Frequency of personal pronouns in the text.
  - **Average Word Length**: Mean length of words in the text.
- **Method**: Sentiment analysis is performed using Natural Language Processing (NLP) techniques and sentiment lexicons.
- **Libraries Used**: NLTK (Natural Language Toolkit) and other relevant Python libraries for text processing and analysis.

## Conclusion
The data wrangling and sentiment analysis process provides valuable insights into the sentiment and characteristics of the text data extracted from the websites. The calculated metrics help in understanding the sentiment polarity, subjectivity, readability, and other linguistic features of the text. This information can be further utilized for various applications such as content analysis, opinion mining, and sentiment-based decision making.
