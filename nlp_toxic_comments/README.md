# Sentiment analysis: Toxic comments identification

[Jupyter NoteBook viewer](https://nbviewer.jupyter.org/github/abatomunkuev/Yandex_Practicum_DS_EN/blob/main/nlp_toxic_comments/nlp_text_sentiment.ipynb)

This project shows: 
- ability to write structured code in Python. 
- ability to use existing utilities (libraries) for processing
- preprocessing skills
- Text preprocessing:
    - lemmatization
    - working with regular expressions
    - text conversion tf-idf
- using Machine Learning models

The project includes:
1. Working with NLP:
    - Pre-processing, text transformation for Machine Learning models
2. Working with Machine Learning models:
    - Logistic Regression.
    - Decision Tree
    - Random Forest
    - XGBoost
    - LightGBM

## Data description

Provided data - comments with markup about the toxicity of edits.

|Column           |Description         |Column type
 |:---------------|:------------------------|:-------------|
 |text    | Comment|features  |
 |toxic   | Indicator whether comment is toxic or not | target |

## Task

The online store is launching a new service. The store needs a tool that will detect toxic comments and send them to be edited or viewed. Build a model that will classify comments into positive and negative.

## Task details 

The customer is concerned about:
- The value of the F1 metric must be at least 75.


## Libraries used
*pandas*
*numpy*
*matplotlib*
*seaborn*
*scipy*
*nltk*
*xgboost*
*lightgbm*
*time*
*re*
