#   Sentiment Analysis on Amazon Product Reviews

This project performs **sentiment analysis** on Amazon product reviews to classify them as **positive**, **neutral**, or **negative**. It uses natural language processing (NLP) techniques to preprocess the data, build a machine learning model, and visualize sentiment distribution with a pie chart.

## Features

- Loads and cleans Amazon product review data.
- Applies sentiment labels based on review scores.
- Transforms review text using `CountVectorizer`.
- Trains a **Naive Bayes** classifier for sentiment prediction.
- Plots a pie chart showing the distribution of sentiments.


## Required Libraries
- **Pandas**
- **Scikit-learn**
- **Matplotlib**
  
- **Preferred IDE :Jupyter Notebook / VS Code/Google Collab**


##  Dataset

The dataset used is `Reviews.csv`, which includes:
- `Text`: The review content.
- `Score`: An integer score (1 to 5) given by users.


##  Sentiment Mapping

| Score | Sentiment  |
|-------|------------|
| 1-2   | Negative   |
| 3     | Neutral    |
| 4-5   | Positive   |



### Install libraries:
pip install pandas scikit-learn matplotlib
### Dataset:
***Kaggle***: https://www.kaggle.com/datasets/arhamrumi/amazon-product-reviews?select=Reviews.csv
