# Steam_user_suggestion_pred

## Objective:
This project used steam game review data to predict user suggestions (binary variable: 0 or 1). The natural language processing, word embedding techniques such as word2vec and sentiment scores are applied to do feature engineering and extraction. The SVM and logistic regression are used to predict whether the user will recommend this game to other users or not.

## Dataset description: 
1. train data features: 
   - review_id: unique user id
   - title: game title
   - year: release year
   - user_review: user comments
   - user_suggestion: binary data with 0 (not recommend) or 1 (recommend)
2. test data
3. game overview features: 
   - title: game title
   - developer: game developer
   - publisher: game publisher
   - tags: game tags to represent its type or features
   - overview: game introduction

## Machine learning techniques: 
1. natural language processing: word tokenization (nltk)
2. sentiment analysis: review scoring as negative, netural, and positive
3. word embedding: word2vec (considering the word context)
4. predictive / classification models: SVM and logistic regression

## Results: 
1. 
