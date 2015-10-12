# Final-Project
Data being used from the Yelp Dataset Challenge: http://www.yelp.com/dataset`_`challenge
To minimize size of repo, pull data from yelp and convert to csv using json`_`to`_`csv`_`converter.py

##1. Specific Aim:
###    - Datasource: Yelp data from Yelp Dataset Chalelnge Round 6.
###    - Size: 1.6M Reviews, 61K businesses, 10 different cities, over past 11 years.
###    - Goal: Create a model that predicts how many stars a review for a restaursnt is based on the review text. (If necessary, group 1-3 stars and 4-5 stars for "bad" and "good" ratings).
##2. Methods:
###    - Outcome: Predict how many stars a review gives a restaurant.
###    - Predictors / covariants - Phrases & words in a review, location
###    - Algorithms under consideration:
#####        - Word2Vec, Doc2Vec, NLTK Library
#####        - Classification Tree
#####        - Random Forests
#####        - Logistic Regression
##3. Result:
###    - Given a specific review text, we can predict how many stars the reviewer gave the restaurant
##4. Limitations / assumptions of your data
###    - People generally use the same language when writing reviews
###    - People give thought to writing reviews and their words correlate to how many stars they give, in a similar way to other people.
##5. Expected hurdles
###    - Working with large dataset
###    - Getting data to a place where it can be processed with Word2Vec or Doc2Vec
###    - Accounting for symbols or grammatical differences
##6. Where you need help
###    - Natural Language Processing
###    - Formatting / cleaning data