<!-- 
This project aims to classify product reviews as positive (4–5 stars) or negative (1–2 stars) using VADER and RoBERTa sentiment analysis models. The goal is to compare their accuracy, identify strengths and weaknesses, and determine the most effective approach for binary sentiment classification.
Data Sources
    source – Kaggle
Amazon reviews for sentiment analysis./Adam Bittlingmayer/ (2019, November 18). Kaggle. https://www.kaggle.com/datasets/bittlingmayer/amazonreviews


Features
- 	NLTK’s SentimentIntensityAnalyzer was used to compute neg, neu, pos, and compound scores for each review, and these were mapped into the binary label scheme.
- pretrained RoBERTa model from Hugging was imported using the transformers library, applied to each review to obtain logits, SoftMax was applied, and probabilities for sentiment were extracted.
-models were evaluated

 Project Status & Intended Use

This is a personal data exploration project created for learning and insight. While you're welcome to view the structure and ideas, it's not intended for public reuse, redistribution, or commercial application. 
 -->
