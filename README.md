# Toxicity Classifier — TF-IDF vs BERT

This project explores toxicity detection in text comments using two NLP approaches:

1. Classical NLP: TF-IDF + Logistic Regression
2. Transformer NLP: BERT

## Goal

Demonstrate the limitation of word-frequency models and the advantage of contextual transformers in detecting subtle toxicity.

## Key Insight

Example sentence:

"You are a horrible person"

- TF-IDF model score: 31%
- BERT model score: 78%

TF-IDF relies on word frequency, while BERT understands context and meaning.

## Dataset

Civil Comments toxicity dataset loaded via HuggingFace.

## What this project shows

- Text vectorization with TF-IDF
- Handling imbalanced data
- Logistic Regression baseline
- Transformer-based classification with BERT
- Practical comparison between classical NLP and modern NLP

## How to run

Open the notebook in Google Colab and run all cells.

## Author

Syed Fateen Ahmed
