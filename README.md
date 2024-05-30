# Fake News Classification

## Introduction

Fake news is a type of yellow journalism that encompasses pieces of news that may be hoaxes and is generally spread through social media and other online platforms. It is often disseminated to further or impose certain ideas, frequently aligned with political agendas. Such news items may contain false and/or exaggerated claims and can become viral through algorithms, potentially placing users in a filter bubble where they are only exposed to information that aligns with their existing beliefs.

## Project Overview

This project aims to classify fake news using various machine learning models. We will use the following models:

- PassiveAggressiveClassifier
- Naive Bayes
- Logistic Regression
  
The goal is to train these models on a dataset of news articles, extract features using TF-IDF vectorization, and evaluate their performance in distinguishing between fake and real news.

## Data
We use a dataset of news articles labeled as either "fake" or "real." The dataset is split into training and testing sets to evaluate the performance of the models.
