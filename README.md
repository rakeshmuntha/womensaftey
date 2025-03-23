Women's Safety Based on Tweets Using Machine Learning

Overview

The Women's Safety Based on Tweets project leverages Machine Learning and NLP techniques to analyze Twitter data and identify patterns, trends, and harmful content related to women's safety. This system is designed to classify tweets as Positive, Negative, or Neutral to assess sentiment and identify potential risks.

Features

Sentiment Analysis:

Uses RoBERTa for improved accuracy in sentiment classification.

Identifies tweets that reflect social concerns, harassment, or violence against women.

Bias-Aware Classification:

Implemented a custom dataset to detect implicit biases in tweet content.

Uses contextual analysis to spot stereotype phrases and comparative language.

Data Preprocessing:

Cleaned data by removing irrelevant symbols, special characters, and URLs.

Tokenized text for efficient feature extraction.

Model Training and Evaluation:

Utilizes VADER for feature extraction and Logistic Regression for classification.

Achieved 92% accuracy with the improved RoBERTa model.

Data Balancing Techniques:

Applied weighted loss to address class imbalance.

Exploring oversampling to further enhance model performance.

Technologies Used

Python (Core language for development)

NLP Libraries: VADER, RoBERTa

Machine Learning Libraries: Scikit-learn, Transformers

Pandas, NumPy (For data handling and analysis)
