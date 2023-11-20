# SpamEmailDetection
This project implements a Naive Bayes classifier to detect spam emails. The model analyzes the content of emails to classify them as either spam or legitimate (ham). The goal is to provide an efficient tool for identifying and filtering out unwanted emails.

## Project Overview
Spam emails pose a significant challenge in the realm of email communication. The ability to automatically identify and filter out spam is crucial to ensuring a clean and secure email environment. This project focuses on utilizing the Naive Bayes classification algorithm to create a model capable of distinguishing between spam and legitimate emails based on their content.

## Data
The SMS Spam Collection dataset is employed for training and evaluating the model. This dataset consists of 5,574 SMS messages in English, each tagged as either "ham" (legitimate) or "spam." The content of the messages is used as the primary input for the Naive Bayes classifier.

The dataset is structured with two columns:

- spam: Contains the label, indicating whether the message is "ham" (legitimate) or "spam."
- text: Contains the raw text of the SMS message.

The model learns patterns and characteristics of both legitimate and spam emails from this dataset, enabling it to make predictions on new, unseen emails.

## Naive Bayes Classifier
The Naive Bayes algorithm is a probabilistic classification technique that calculates the probability of a given input belonging to a particular class. In the context of this project, the Naive Bayes classifier learns from the content of emails to estimate the probability of an email being spam or legitimate.

