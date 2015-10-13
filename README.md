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
        - Classification Tree
        - Random Forests
        - Logistic Regression
##3. Result:
#####    - Given a specific review text, we can predict how many stars the reviewer gave the restaurant
##4. Limitations / assumptions of your data
#####    - People generally use the same language when writing reviews
#####    - People give thought to writing reviews and their words correlate to how many stars they give, in a similar way to other people.
##5. Expected hurdles
#####    - Working with large dataset
#####    - Getting data to a place where it can be processed with Word2Vec or Doc2Vec
#####    - Accounting for symbols or grammatical differences
##6. Where you need help
#####    - Natural Language Processing
#####    - Formatting / cleaning data
##7. Repeat for secondary hypothesis
#####    - Pending first hypothesis, will test depending on location / city of review and look for similarities/differences in language correlated to good reviews

1.	Specific Aim

    a.	Datasource: Yelp data from Yelp Dataset Challenge Round 6.
    b.	Size: 1.6M reviews, 61K businesses, 10 cities
    c.	Timeframe: 2004 – 2015
    d.	Goal: Create a model that predicts how many stars a restaurant review has based on the review text.
2.	Methods
    a.	Outcome: Predict how many stars a review gives a restaurant	
    b.	Predictors/covariants
        i.	Phrases / words in review
        ii.	Location
    c.	Algorithms under consideration
        i.	Word2Vec, Doc2Vec, NLTK Library
        ii.	Logistic Regression
        iii.	Classification Tree (decision tree)
        iv.	Random Forests (?)
3.	Result
    a.	Given a specific review text, we can predict how many stars the reviewer gave the restaurant.
4.	Limitations / Assumptions of your data
    a.	People generally use the same language, in particular across different locations.
    b.	People are thoughtful and rational when writing reviews and rating restaurants, meaning there is a correlation between text sentiment and star-ratings.
5.	Expected hurdles
    a.	Working with large dataset
    b.	Pre-processing data
6.	Where you need help
    a.	Natural Language Processing
    b.	Cleaning & formatting data
7.	Repeat for secondary hypothesis
    a.	If first pass goes well, the second test will be to split reviews by region and see if there are differences in positive/negative language between different cities.

