# Analysis of the Drug Comments Dataset

## Project Overview

This project analyzes the FDA's drugComments dataset, which contains over 4,000 consumer reviews of prescription drugs. The analysis focuses on understanding patient experiences, benefits, and side effects of various medications using advanced text analytics techniques.

## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Methodology](#methodology)
- [Analysis](#analysis)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Contributors](#contributors)
- [License](#license)

## Introduction

The FDA's drugComments dataset provides valuable insights into consumer reactions to prescription drugs. This analysis aims to identify patterns and trends in consumer perspectives on drug benefits.

## Problem Statement

The project addresses several challenges:
- Handling missing values, noise, and inconsistencies in the data
- Extensive text preprocessing for unstructured reviews
- Interpreting subjective patient reviews
- Extracting meaningful topics from unstructured text

## Methodology

### Text Preprocessing
- Lowercase conversion
- Removal of URLs, special characters, numbers, and punctuation
- Tokenization
- Lemmatization
- Removal of stop words
- Handling of missing data

### Analysis Techniques
1. Textual Analysis
2. Sentiment Analysis
3. Word Frequency Analysis
4. Topic Modeling (LDA)
5. N-gram Analysis

## Analysis

The analysis includes:
- Exploratory data analysis of the 'benefitsReview' column
- Sentiment classification using TextBlob
- Visualization of word frequencies and sentiments
- Topic modeling to identify underlying themes
- N-gram analysis for frequent word combinations

## Key Findings

- Overall positive sentiment towards reviewed drugs
- Common discussion topics include daily experiences and pain management
- Identification of frequent side effects and benefits
- Extraction of key themes related to treatment efficacy

## Recommendations

Based on the analysis, we recommend:
1. Improving drug communication
2. Enhancing feedback mechanisms
3. Personalizing medicine campaigns
4. Strengthening surveillance of adverse effects
5. Enhancing patient education
6. Targeting product development based on insights
7. Collaborating with healthcare professionals and regulatory bodies
8. Continuously improving analysis methods

## Getting Started

To run this project:

1. Clone the repository
2. Ensure you have Python 3.x installed
3. Install the required dependencies (see [Dependencies](#dependencies))
4. Open the Jupyter notebook `Analysis_of_Drug_Comments_Dataset.ipynb`
5. Run the cells in order

## Dependencies

This project requires the following Python libraries:

- pandas
- scikit-learn
- matplotlib
- wordcloud
- textblob
- nltk

You can install these dependencies using pip:
pip install pandas scikit-learn matplotlib wordcloud textblob nltk
Additionally, you need to download specific NLTK datasets. This is done within the notebook using:

```python
nltk.download('stopwords')
nltk.download('punkt')
nltk.download('wordnet')
nltk.download('omw-1.4')

## Code Structure

The main analysis is performed in a Jupyter notebook. Here's an overview of the key components:

1. **Data Loading and Preprocessing**
   - Using pandas to load and manipulate the dataset
   - Text cleaning and normalization

2. **Text Analysis**
   - Tokenization and lemmatization using NLTK
   - Stop word removal

3. **Word Frequency Analysis**
   - Using CountVectorizer from scikit-learn
   - Visualization with matplotlib

4. **Sentiment Analysis**
   - Utilizing TextBlob for sentiment scoring

5. **Topic Modeling**
   - Implementing Latent Dirichlet Allocation (LDA) from scikit-learn

6. **N-gram Analysis**
   - Extracting and analyzing bigrams and trigrams

7. **Visualization**
   - Creating word clouds using WordCloud
   - Plotting frequency distributions and sentiment analysis results

## Contributors

Team Blockers
