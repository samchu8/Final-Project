# Final-Project
`Data being used from the Yelp Dataset Challenge: http://www.yelp.com/dataset_challenge

`To minimize size of repo, pull data from yelp and convert to csv using json_to_csv_converter.py

`Other data in \data folder can be found in comments of the code

##1. Specific Aim:
#####    - Datasource: Yelp data from Yelp Dataset Chalelnge Round 6.
#####    - Size: 1.6M Reviews, 61K businesses, 10 different cities, over past 11 years.
#####    - Goal: Create a model that predicts how many stars a review for a restaursnt is based on the review text. (If necessary, group 1-3 stars and 4-5 stars for "bad" and "good" ratings).
##2. Methods:
#####    - Outcome: Predict how many stars a review gives a restaurant.
#####    - Predictors / covariants - Phrases & words in a review, location
#####    - Algorithms under consideration:
        - Word2Vec, Doc2Vec, NLTK Library
        - Decision Tree
        - Random Forests
        - Logistic Regression
##3. Result:
#####    - Given a specific review text, we can predict how many stars the reviewer gave the restaurant
##4. Limitations / assumptions of your data
#####    - People generally use the same language when writing reviews
#####    - People are thoughtful and rational when writing reviews and rating restaurants, meaning there is a correlation between text sentiment and star-ratings.
##5. Expected hurdles
#####    - Working with large dataset
#####    - Getting data to a place where it can be processed with Word2Vec or Doc2Vec
#####    - Accounting for symbols or grammatical differences
##6. Where you need help
#####    - Natural Language Processing
#####    - Formatting / cleaning data
##7. Repeat for secondary hypothesis
#####    - Pending first hypothesis, will test depending on location / city of review and look for similarities/differences in language correlated to good reviews