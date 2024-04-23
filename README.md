# NLP_Huff_News

## Data Description

**Dataset Overview:** This dataset consists of 209,527 news headlines from HuffPost, ranging from 2012 to 2022. It is a significant resource for computational linguistics, offering insights into a decade of news trends. Also, post-2018, HuffPost's comprehensive archive maintenance ceased, making this dataset a unique collection.

The dataset is available on Kaggle through: [News Category Dataset](https://www.kaggle.com/datasets/rmisra/news-category-dataset/data) and duplicates are removed.

The dataset consists of 209,527 rows and 6 columns:

1. **Category:** The news category (42 in total).
2. **Headline:** Title of the article.
3. **Authors:** Contributors to the article.
4. **Link:** URL to the original article.
5. **Short Description:** Abstract of the article.
6. **Date:** Article's publication date.
markdown
Copy
# Code Overview

The code in this repository performs the following tasks:

### Data Cleaning:

- Handling missing values
- Removing duplicates
- Preprocessing text data

### spaCy Preprocessing:
- Tokenization
- TF-IDF (Term Frequency-Inverse Document Frequency):
- Converting text data into numerical features
- Identifying important words in the headlines

### Random Forest Feature Importance:

- Training a Random Forest classifier
- Extracting feature importance scores
- Identifying the most significant words in predicting news categories

### Logistic Regression Coefficient:

- Training a Logistic Regression model
- Extracting the coefficients of the model
- Identifying the most influential words for each news category

### BERT Keyword Extractor:

- Using the BERT (Bidirectional Encoder Representations from Transformers) model
- Extracting keywords from the news headlines
- Identifying the most relevant keywords for each headline

### BERT Tech Keyword Extractor:

- Fine-tuning the BERT model for technology-related keywords
- Extracting tech-specific keywords from the news headlines

### Data Visualization:

- Creating bar graphs to visualize the distribution of news categories
- Generating tables to present the top keywords and their frequencies

### Requirements

To run the code in this repository, you'll need the following dependencies:

- Python 3.x
- pandas
- numpy
- spaCy
- scikit-learn
- TensorFlow
- Matplotlib
- Jupyter Notebook

# Brief purpose of the analysis 

- The purpose of this analysis is to explore and gain insights from a dataset of HuffPost news headlines ranging from 2012 to 2022. By applying various natural language processing (NLP) techniques and machine learning algorithms, such as TF-IDF, Random Forest, Logistic Regression, and BERT, we aim to uncover patterns, trends, and key features within the news headlines. The analysis will provide a deeper understanding of the distribution of news categories, important words for predicting categories, and relevant keywords extracted from the headlines.
The analysis provides insights into the HuffPost news headlines dataset, including:

- Distribution of news categories
- Most important words for predicting news categories
- Top keywords extracted from the headlines
- Tech-specific keywords identified by the BERT model
- 

The results are visualized using bar graphs and tables for easy interpretation.

# Acknowledgments

- The HuffPost news headlines dataset is sourced from Kaggle.
- The spaCy library is used for text preprocessing and named entity recognition.
- The scikit-learn library is used for machine learning tasks.
- The TensorFlow library is used for the BERT model.
