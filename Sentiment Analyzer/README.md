Project Title: Sentiment Analysis of Amazon Fine Food Reviews Using NLTK and RoBERTa

Project Overview:
This project aims to perform sentiment analysis on the Amazon Fine Food Reviews dataset by employing Natural Language Toolkit (NLTK) for text preprocessing and sentiment scoring using VADER, followed by a more advanced sentiment classification using the RoBERTa model. The objective was to compare the performance of these two approaches and evaluate their effectiveness in capturing sentiment nuances within customer reviews.

Dataset:

Name: Amazon Fine Food Reviews

Description: Contains over 500,000 reviews of fine foods on Amazon, including attributes like review text, rating, user ID, and time.

Purpose: To analyze the sentiment of customer reviews and derive insights into the emotional tone expressed by users.

Methodology:

Data Preprocessing:

Imported the dataset and handled missing values.

Tokenized the review text using NLTK to split sentences into words for better text handling.

Sentiment Analysis with NLTK (VADER):

Applied VADER (Valence Aware Dictionary and sEntiment Reasoner), a lexicon and rule-based sentiment analysis tool specifically designed for social media and short text.

Calculated sentiment scores (positive, negative, neutral, and compound) for each review.

Sentiment Analysis with RoBERTa:

Utilized the pre-trained RoBERTa model (cardiffnlp/twitter-roberta-base-sentiment-latest), trained on a large corpus of social media data, for more nuanced sentiment analysis.

Passed tokenized review text into the RoBERTa model to predict sentiment categories.

Comparison:

Compared the results from VADER and RoBERTa to evaluate differences in sentiment classification.

Analyzed key metrics like accuracy, precision, recall, and F1 score.

Results and Findings:

VADER showed decent performance in identifying general sentiment but struggled with detecting more complex sentiments and sarcasm.

RoBERTa demonstrated superior performance, capturing subtleties and context more effectively due to its deep learning architecture.

The comparison highlighted RoBERTa's ability to reduce false positives/negatives and improve sentiment classification accuracy.

Conclusion:
The study concluded that while NLTK's VADER is effective for quick, rule-based sentiment analysis, models like RoBERTa offer deeper insights by leveraging contextual understanding. The project illustrated the trade-offs between traditional NLP techniques and modern transformer-based approaches.