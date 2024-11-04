# Predicting Positive and Negative Reviews

### Project Overview

### A machine learning project that classifies movie reviews as positive or negative by preprocessing text data and using various classification models (Random Forest, Gradient Boosting, and optionally XGBoost). This project explores different preprocessing techniques like TF-IDF vectorization and hyperparameter tuning to improve model accuracy. Ideal for beginners and intermediate users interested in natural language processing and sentiment analysis.

Installation and Requirements
To run this project, you'll need Python 3 and the following libraries:

* pandas
* numpy
* sklearn
* nltk
* xgboost (optional)
### Install the required libraries using:
```bash
pip install -r requirements.txt
```
## Dataset Overview
The dataset contains IMDB movie reviews labeled as positive or negative. Each review consists of text data that will undergo preprocessing and feature extraction before model training. The dataset is loaded from a CSV file and checked for null values, with no missing values detected.

Data Preprocessing
The preprocessing steps involve:

Removing Punctuation: Strips unnecessary punctuation from the reviews.
  * Tokenization: Splits text into individual words.
  * Stop Words Removal: Removes common words (e.g., "and", "the") that do not contribute meaningfully to the classification.
  * Lemmatization/ Stemming: Reduces words to their root form to standardize them.
  * TF-IDF Vectorization: Converts the cleaned text data into a numerical format suitable for machine learning.
  * Model Building and Evaluation
The project uses two main classifiers, with GridSearchCV for hyperparameter tuning:

### Random Forest Classifier
### Gradient Boosting Classifier (or XGBoost if performance is slow)
### Evaluation metrics include accuracy and the classification report (precision, recall, F1-score).



How to Run
```bash
git clone https://github.com/shadrach098/Review_Sentiment_Analysis.git

```
```bash
pip install -r requirements.txt
```
