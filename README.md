# metis_projects

This repository contains the machine learning projects built during my Metis instruction. For each project, you can find the code that was used in the Python notebooks, and any other miscellaneous files that were integral to the final product.

Stroke Classification: Built a random forest model that classified patients as at risk or not at risk of a stroke. Created an engineered heart disease feature from a cardiovascular disease dataset to input into my stroke classifier. Determined model effectiveness using a weighted average of recall and specificity. Achieved out-of-sample recall of 84% and specificity of 73%. Hosted a flask app on Heroku to predict user stroke risk. (pandas, scikit-learn, Flask)

Reddit Recommender: Created a recommendation system for Reddit users using Natural Language Processing. Used the Reddit API to scrape comments from the top 100 subreddits. Used a TF-IDF vectorizer and Non-Negative Matrix Factorization model to extract 8 distinct topics from the corpus. Matched each subreddit by cosine similarity and created a Flask app to recommend subreddits to a user based on their favorite one. (pandas, RedditAPI, Flask, NLTK)

Michelin-Yelp Classification: Built a logistic regression model to classify a restaurant's likelihood of getting a Michelin star according to different Yelp metrics. Scraped data for Michelin star restaurants from Wikipedia and Yelp using BeautifulSoup. Created a Flask app which let users input a restaurant's properties to predict probability of being Michelin-worthy and hosted it on Heroku. Achieved recall of 91% (pandas, BeautifulSoup, Flask, scikit-learn)

Phone Price Prediction: Built a linear regression model to predict the prices of mobile phones given its physical specifications and hardware. Scraped data of 8000+ phones from the phone listings found at GSMArena.com (pandas, BeautifulSoup, StatsModels, scikit-learn)
