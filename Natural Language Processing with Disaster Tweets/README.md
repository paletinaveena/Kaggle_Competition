# Natural Language Processing with Disaster Tweets

## Overview
This repository contains code for a machine learning model to predict whether a given tweet is about a real disaster or not. It is based on the Kaggle competition ["Natural Language Processing with Disaster Tweets"](https://www.kaggle.com/c/nlp-getting-started). The model is built using logistic regression and utilizes text vectorization and preprocessing techniques.

## Problem Statement
Twitter has become an important communication channel in times of emergency. The challenge is to build a machine learning model that predicts which Tweets are about real disasters and which ones aren't.

## Dataset
The dataset consists of three files:
- `train.csv`: Training set containing tweets with associated labels.
- `test.csv`: Test set containing tweets without associated labels.
- `sample_submission.csv`: Sample submission file with the required format for submission.

Each sample in the train and test set has the following information:
- The text of a tweet
- A keyword from that tweet (although this may be blank)
- The location the tweet was sent from (may also be blank)

## Kaggle Competition Link
["Kaggle Competition Link"](https://www.kaggle.com/competitions/nlp-getting-started)

## Requirements
- Python 3.x
- pandas
- scikit-learn
- seaborn
- matplotlib
