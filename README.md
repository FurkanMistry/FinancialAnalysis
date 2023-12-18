# Sentiment Analysis of Financial News

The primary goal of this project is to develop a sentiment analysis system that can automatically determine the sentiment of financial news articles as positive, negative, or neutral. This analysis aims to assist investors and financial professionals in making more informed decisions by quickly gauging market sentiment.

## Project Overview

The "Sentiment Analysis of Financial News Article" project addresses the growing need for automated sentiment analysis in the financial industry. The interpretation of news and events can significantly impact investment decisions. By providing a tool that can quickly and objectively assess sentiment, this project aims to empower investors, traders, and financial professionals with valuable insights for more informed decision-making in the fast-paced world of finance.

## Project Objectives

1. **Data Collection:** Collect financial news headlines and descriptions from the provided dataset.
2. **Data Preprocessing:** Preprocess the text data to prepare it for analysis, including tasks like lowercase conversion, punctuation removal, stopwords removal, and stemming or lemmatization.
3. **Sentiment Analysis:** Perform sentiment analysis on the financial news data using NLTK and a machine learning model (e.g., Logistic Regression) to predict sentiment labels.
4. **Model Evaluation:** Evaluate the performance of the sentiment analysis models using metrics like accuracy, precision, recall, and F1-score.
5. **Compare Models:** Compare the performance of different models (e.g., LinearSVC, Logistic Regression, Multinomial Naive Bayes, and Bernoulli Naive Bayes) to determine the most effective model for sentiment analysis.
6. **Real-time Prediction:** Implement a function to make real-time predictions on new financial news articles to classify their sentiment.
7. **Text Analysis:** Analyze the text for the count of verbs, adverbs, and nouns to gain insights into the language used in financial news articles.

## Data Collection

### Context

Scraped from CNBC, the Guardian, and Reuters official websites, the headlines in these datasets reflect the overview of the U.S. economy and stock market every day for the past year to 2 years.

### Content

- Data scraped from CNBC contains headlines, last updated date, and preview text of articles from the end of December 2017 to July 19th, 2020.
- Data scraped from Reuters contains headlines, last updated date, and preview text of articles from the end of March 2018 to July 19th, 2020.

## Data Exploration

In the initial exploratory data analysis (EDA) of the `cnbc_headlines` and `reuters_headlines` datasets, the following key insights were observed:

### For `cnbc_headlines` dataset:

1. The dataset contains the following columns:
   - `time`: Timestamp of the news headline.
   - `headlines`: Financial news headlines.
   - `description`: Descriptions of the news headlines.
2. No missing values in the dataset after dropping rows with missing data.
3. No duplicate rows in the dataset after dropping duplicates.

### For `reuters_headlines` dataset:

1. The dataset contains the following columns:
   - `time`: Timestamp of the news headline.
   - `headline`: Financial news headlines.
   - `description`: Descriptions of the news headlines.
2. No missing values in the dataset after dropping rows with missing data.
3. No duplicate rows in the dataset after dropping duplicates.

...

(Continue with further sections such as Data Preparation, Analysis Methods, Model Building, Model Evaluation, Results and Interpretation, etc.)

## Dependencies

1. **NLTK (Natural Language Toolkit):** For natural language processing (NLP) tasks.
2. **pandas:** For data manipulation and analysis.
3. **numpy:** For numerical operations and mathematical computations.
4. **scikit-learn (sklearn):** For machine learning model building and evaluation.
5. **seaborn and matplotlib.pyplot:** For data visualization.
6. **nltk.sentiment.vader:** A specific module within NLTK for sentiment analysis.
7. **requests:** For making HTTP GET requests to scrape online articles.
8. **BeautifulSoup:** For web scraping.
9. **spacy:** Another NLP library for parts-of-speech analysis.

## Data Sources and Licensing

- **Dataset Link:** [click to view dataset](link_to_dataset)
- **Usability:** 10.00
- **License:** CC0: Public Domain

## Version Control

For this project, Google Colab was utilized as the primary development environment, offering integrated version control features. The detailed revision history within Google Colab tracked changes, additions, and deletions, providing a comprehensive record of the project's development.

## Summary

The "Sentiment Analysis of Financial News Using NLTK" project lays the groundwork for automated sentiment analysis in the financial sector. The logistic regression model outperformed other models, achieving an accuracy of approximately 80.77%. The project provides valuable insights for investors and financial experts, aiding in decision-making in the dynamic world of finance.

## Future Research and Improvements

1. **Fine-Grained Sentiment Categorization:** Enable more precise sentiment categorization.
2. **Real-Time Analysis:** Implement a system for real-time sentiment analysis.
3. **Multi-Language Support:** Add multi-language support for a broader audience.

## Recommendations

1. **User Feedback Integration:** Integrate user feedback into the sentiment analysis system.
2. **Enhanced Data Sources:** Include more sources of information for a comprehensive market mood.
3. **Security and Data Protection:** Maintain strong data security measures.
4. **Visualization Tools:** Create interactive visualization tools for understanding sentiment trends.

