# Natural Language Processing: Chatbot, Language Model, and News Classifier

## What
This repository contains implementations of three NLP systems: a rule-based chatbot using regular expressions, a bigram language model for authorship attribution, and a Naive Bayes classifier for fake vs real news detection.

## How
- **Regex Chatbot:** Matches user input with predefined regular expressions and generates responses based on detected patterns.  
- **Bigram Language Model:** Counts unigrams and bigrams, calculates smoothed probabilities, and computes sentence log-probabilities to predict the likely author.  
- **News Classification:** Preprocesses articles, builds word frequency dictionaries per class, applies a Naive Bayes classifier, and evaluates predictions using a confusion matrix.

## Why
Human language is complex and highly contextual. This project demonstrates how foundational NLP techniques can interpret patterns, capture stylistic differences, and classify text, providing practical examples of processing and understanding natural language.
