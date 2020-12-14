# Twitter Sentiment Analysis Logistic Regression
In this project I performed sentiment analysis with PySpark on a twitter dataframe consisting of 100,000 tweets. The tweets.csv file contains the following columns:

- target: the polarity of the tweet (0 = negative, 4 = positive)
- ids: The id of the tweet ( 2087) 
- date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
- flag: The query (lyx). If there is no query, then this value is NO_QUERY.
- user: the user that tweeted (robotickilldozr)
- text: the text of the tweet (Lyx is cool)

The data was vectorized via TF-IDF and modeled using Logisic Regression to asses whether it's sentiment either was positive or negative. The testing ROC AUC was improved from 68% to 88% via L2 Regularization and hyperparameter tuning.
