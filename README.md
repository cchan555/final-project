# Sentiment Analysis and Topic Modeling with Machine Learning on Airline Reviews
This repository contains all the necessary information to reproduce this project, analyzing airline customer reviews using sentiment analysis and topic modeling with machine learning classifications.

**Course:** LIS 4693 Info Retrieval and Test Mining <br>
**Author:** Cody Chan and Jackson Manor <br>
**Focus:** Apply Sentiment Analysis and Topic Modeling with Machine Learning Classification <br>

## Project Overview:
This project applies sentiment analysis, topic modeling, and machine learning to predict airline recommendations based on customer text-based reviews alone. The following dataset used contains 129,455 airline reviews. Cody analyzed the sentiment analysis pattern differences between recommended vs non-recommended airlines, whether cabin classes affect review sentiment, and whether we can accurately predict airline recommendations from review text alone through machine learning classification. Jackson analyzed (FILL IN).

### Overarching Question:
How does sentiment analysis differ between recommended and non-recommended airlines? <br>
Do cabin class (Economy, Business, First, and Premium) affect airline review sentiemnt? <br>
(TOPIC MODELING FILL IN) <br>
Can we accurately predict airline recommendations based on text reviews alone? <br>

## Data
**Source:** Airline Reviews Dataset - 129,455 reviews [Kaggle Dataset](https://www.kaggle.com/datasets/joelljungstrom/128k-airline-reviews)

**Variables to Consider:**
- Review: Customer text review (Main analysis)
- Recommended: Yes/No recommendations (Our prediction target)
- CabinType: Economy, Business, First, and Premium

**Dataset Location:**
[Dataset Location](https://github.com/cchan555/final-project/blob/1f2e60a02ca37a830cec4af18475cef836aff95c/Dataset%20Files/AirlineReviews.csv)

## Methods
### Text Preprocessing:
- Fill in 824 missing reviews with empty strings
- Use CountVectorizer to convert the text into word frequency counts
- Use TF-IDF Transformer to weigh the words  by importance
- Train/Test split of 70% training (90,618 reviews) and 30% testing (38,837 reviews)
### Sentiment Analysis:
- Generated four sentiemnt scores per reviews
  - neg: Proportion of negative words that ranges from 0.0 to 1.0
  - neu: Proportion of neutral words that ranges from 0.0 to 1.0
  - pos: Proportion of positive words that ranges from 0.0 to 1.0
  - compound: Overall sentiemnt score that ranges from -1.0 to 1.0

### Topic Modeling:

### Machine Learning Classification:
There were three trained classifiers used in this analysis:
- Native Bayes
- Logistic Regression
- Random Forest

## Results
### Sentiment Analysis Findings:
- Recommended airlines have x3 more positive language
- Business Class had the highest median and smallest spread, making it the most consistent

### Topic Modeling Findings:

### Machine Learning Findings:
- Logistic Regression performed the best out of the three classifiers at 91.90% accuracy
  - High accuracy on both recommended and non-recommended airline predictions on the confusion matrix

## Contributors
### Cody Chan
- Sentiemnt Analysis
- Machine Learning Classification
### Jackson Manor
- Topic Modeling

README file written by their respective methods.
