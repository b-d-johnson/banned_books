To run the notebooks:

1. `git lfs clone git@github.com:b-d-johnson/banned_books.git`
2. `cd banned_books`
3. `pip install requirements.txt` or `pip3 install requirements.txt`

## Datasets

- The list of banned books (provided by the ALA and PEN) may be found in `data/pen_dataset.csv`.
- The scraped Amazon.com reviews on the banned books may be found in `data/scraped_amz_reviews.csv`. 

## Supervised Sentiment Analysis

To run the best performing supervised sentiment analysis model (Logistic Regression):

`jupyter notebook supervised_sentiment_analysis/supervised_logistic_regression_full.ipynb`

To run a full search for the best performing supervised sentiment analysis model:

`jupyter notebook supervised_sentiment_analysis/supervised_model_selection_random_search_cv.ipynb`


## Unsupervised Topic Modeling

To run the LDA topic modelling analysis (before) the first book ban:

`jupyter notebook unsupervised_topic_modeling/2_LDA_Topics_Before_Book_Ban.ipynb`

To run the LDA topic modelling analysis (after) the first book ban:

`jupyter notebook unsupervised_topic_modeling/3_LDA_Topics_After_Book_Ban.ipynb`


## EDA of Banned Books Dataset

To run some exploratory data analysis:

`jupyter notebook Appendix_EDA.ipynb`

## To Re-Run the Amazon.com customer review scraper on the banned books list:

`jupyter notebook amazon_review_scraper.ipynb`
