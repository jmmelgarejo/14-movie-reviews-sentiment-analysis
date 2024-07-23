## Movie Reviews Sentiment Analysis

This project uses analytics and language models to develope a system for filtering and categorizing movie reviews.
Data was sourced from a dataset of IMBD movie reviews with polarity labeling to build a model for classifying positive and negative reviews (sentiment analysis). Logistic Regression and Gradient Boosting algorithms were utilized.

Link: https://github.com/jmmelgarejo/14-movie-reviews-sentiment-analysis/blob/main/14-movie-reviews-sentiment-analysis.ipynb

## Table of Contents
- Introduction
- Objectives
- Methodology
- Conclusions

### Introduction

The client, nicknamed "Film Junky Union," is developing a system for categorizing movie reviews. The goal is to train a model to automatically detect negative reviews. Prior to building the model, data cleaning and text normalization was performed. In EDA, there are various vizualizations that tell the story movie releases and movie review growth over time.

### Objectives
- Build a model to categorize negative reviews.
- Achieve a model accuracy F1 score below 0.85.

### Methodology
- Data Import and Exploratory Data Analysis: Import and normalize data; develop descriptive statistics and visualize trends to inform model.
- Model Selection and Training: Select, test, and fine-tune a language model to categorize negative reviews, using data splits for training, and testing, and evaluate boosting methodologies for accuracy. Train a model to automatically detect negative reviews with an F1 score of below 0.85 using various methodologies across two language libraries - spaCy, NLTK, logistic regression, gradient boosting.
- Conclusions and Recommendations: Compile final recommendations and action steps for reducing churn, including strategies for model deployment and monitoring.

### Conclusions
- Models 1 and 3 have more meaningful difference in the the scores given to the predictions - ie sentiments that are clearly positive show a score closer to 1 and those that are negative show a score closer to 0, whereas Model 4 does not. This aligns with the lower accuracy scores of Model 4 on the test set.
- LR is noted to be better at capturing linear or binary relationships, and sentiment analysis for movies aligns well with this algorithm.
- Further work on this data set could include fine tuning the LGBM model and adjusting parameters.


