# Social Media Sentiment Analysis

## Overview
This project focuses on sentiment analysis of text-based data, particularly comments or tweets, to predict polarity (positive or negative sentiment). Leveraging machine learning algorithms such as Naive Bayes, Support Vector Machine (SVM), and Bagging techniques, the goal is to classify sentiments expressed in text with high accuracy. The model preprocesses the data, tokenizes it, removes noise like URLs and punctuation, and converts it to lowercase to enhance machine learning algorithm performance. The sentiment analysis model aims to categorize text into positive or negative sentiments and can be evaluated for accuracy. The insights derived from this model can be valuable for various applications including business decisions, marketing strategies, and opinion analysis.

## Key Features
- Developed sentiment analysis model using Twitter’s Sentiment140 dataset achieving 82% accuracy in classifying tweets as positive or negative.
- Implemented Bagging with SVM and feature selection techniques, significantly improving accuracy compared to traditional methods like logistic regression and naive Bayes.
- Preprocessing steps include lowercasing, URL replacement, emoji replacement, username replacement, removal of non-alphabets, removing consecutive letters, removing short words, removing stopwords, and lemmatization.

## Preprocessing Steps
1. **Lowercasing**: Texts are converted to lowercase.
2. **URL Replacement**: Any URLs starting with "http" or "https" or "www" are substituted with the term "LINK".
3. **Emoji Replacement**: Emojis are replaced using a predefined dictionary mapping emojis to their descriptions (e.g., ":)" to "happy").
4. **Username Replacement**: Usernames preceded by "@" are replaced with the term "USER" (e.g., "@JohnDoe" to "USER").
5. **Removing Non-Alphabets**: All characters except digits and alphabets are replaced with a space.
6. **Removing Consecutive Letters**: Sequences of 3 or more repeated letters are shortened to 2 letters (e.g., "Heyyyy" to "Heyy").
7. **Removing Short Words**: Words with less than 3 characters are eliminated.
8. **Removing Stopwords**: English stopwords are removed to filter out words that contribute minimally to the meaning of a sentence (e.g., "the", "and", "but").
9. **Lemmatizing**: Words are lemmatized to convert them to their base form (e.g., “running” to “run”).

## Conclusion
This project provides a comprehensive solution for sentiment analysis of social media text data. By employing advanced preprocessing techniques and machine learning algorithms, it achieves high accuracy in classifying sentiments. The model's ability to extract insights from text data can be invaluable for various real-world applications.

