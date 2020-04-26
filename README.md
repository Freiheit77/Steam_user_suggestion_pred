# Steam_user_suggestion_pred

## Objective:
This project used steam game review data to predict user suggestions (binary variable: 0 or 1). The natural language processing, word embedding techniques such as word2vec and sentiment scores are applied to do feature engineering and extraction. The SVM and logistic regression are used to predict whether the user will recommend this game to other users or not.

## Dataset description: 
1. train data: 
  1) review_id: unique user id
  2) title: game title
  3) year: release year
  4) user_review: user comments
  5) user_suggestion: binary data with 0 (not recommend) or 1 (recommend)
2. test data
3. game overview:
  1) title: game title
  2) developer: game developer
  3) publisher: game publisher
  4) tags: game tags to represent its type or features
  5) overview: game introduction
