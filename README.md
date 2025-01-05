
# Airline Tweets Sentiment Analysis

This project performs **sentiment analysis** on airline-related tweets using **Natural Language Processing (NLP)** techniques. The dataset contains tweets categorized into positive, negative, and neutral sentiments. The objective is to classify tweets based on their sentiment and gain insights into customer feedback for airlines.

---

## Table of Contents
1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Technologies Used](#technologies-used)
4. [Key Features](#key-features)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Results](#results)
8. [References](#references)
9. [Contributors](#contributors)

---

## Overview

This project applies NLP methods and libraries to analyze and classify tweets. The steps include:
- Data cleaning and preprocessing.
- Sentiment analysis using machine learning algorithms.
- Data visualization to understand the trends in sentiment.

---

## Dataset

The dataset is sourced from Kaggle:
[Twitter Airline Sentiment Dataset](https://www.kaggle.com/crowdflower/twitter-airline-sentiment?select=Tweets.csv)

### Features:
- **Text**: The content of the tweet.
- **Sentiment**: Classification of the tweet as positive, neutral, or negative.

---

## Technologies Used

- **Python Libraries**:
  - `Pandas` and `NumPy`: For data manipulation and analysis.
  - `NLTK`: For text preprocessing, tokenization, and lemmatization.
  - `Matplotlib` and `Seaborn`: For data visualization.
  - `WordCloud`: For generating word cloud visualizations.

- **Other Tools**:
  - Google Colab: For running the code.
  - Kaggle: For dataset sourcing.

---

## Key Features

- **Text Preprocessing**:
  - Tokenization, stemming, and lemmatization.
  - Removal of stopwords, punctuation, and special characters.

- **Sentiment Classification**:
  - Machine learning models to classify sentiment into positive, neutral, and negative categories.

- **Visualizations**:
  - Word clouds to display the most frequent terms.
  - Sentiment distribution plots.

---

## Installation

### Prerequisites:
1. Install Python 3.8 or above.
2. Install Jupyter Notebook (optional).

### Steps:
1. Clone the repository:
   ```bash
   git clone <repo-link>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Load the dataset and place it in the same directory as the notebook file.
2. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook Airline_Tweets_Sentiment_Analysis.ipynb
   ```
3. Follow the step-by-step instructions in the notebook to execute the analysis.

---

## Results

The results include:
- Classification of tweets into sentiment categories.
- Visual representation of common keywords and sentiment trends.
- Insights into customer feedback for airlines.

---

## References

1. Dataset: [Twitter Airline Sentiment on Kaggle](https://www.kaggle.com/crowdflower/twitter-airline-sentiment?select=Tweets.csv)
2. Libraries: [NLTK](https://www.nltk.org/), [Matplotlib](https://matplotlib.org/), [Seaborn](https://seaborn.pydata.org/)

---

## Contributors

- **Raj Dineshbhai Adroja**  
  Master of Science in Software Engineering  
  San Jose State University  
  [Email](mailto:rajdineshbhai.adroja@sjsu.edu)

---

## License

This project is licensed under the MIT License. See `LICENSE` for more details.
