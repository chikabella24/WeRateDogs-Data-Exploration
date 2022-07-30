WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. The account was started in 2015 by college student Matt Nelson, and has received international media attention both for its popularity and for the attention drawn to social media copyright law. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. There are three dataset to be explored in this data analysis, which would be wrangled for proper exploration of the data, analysed to find patterns and trends, and visualize the insights gained through charts and graphs.

This project has two main parts

In Part I, Exploratory data visualization, i used use Python visualization libraries to systematically explore this dataset(consists of information regarding 2,174 tweets from the WeRateDogs Twitter account with 21 attributes columns), starting from plots of single variables and building up to plots of multiple variables.
The WeRateDogs data consists of 2,174 tweets and 21 features('tweet_id', 'timestamp', 'source', 'text', 'rating_numerator', 'rating_denominator', 'name', 'stage', 'jpg_url', 'img_num', 'p1', 'p1_conf', 'p1_dog', 'p2', 'p2_conf', 'p2_dog', 'p3', 'p3_conf', 'p3_dog', 'retweet_count', 'favorite_count'), after data cleaning the dataset was transformed to 24 features(additional features: 'hour', 'month', 'date').

In Part II, Explanatory data visualization, i produced a short presentation that illustrates interesting properties, trends, and relationships that were discovered in my dataset. The primary method of conveying my findings were through transforming my exploratory visualizations from the first part into polished, explanatory visualizations.

Summary of Findings
* The Year 2016 was the highest tweets,followed by 2015 and lastly 2017
This shpws that tweets increased in 2016 and declined in 2017

* using the prediction 1 dog to verify that the image is truly a golden retriever and is true with a high prediction confidence of above0.99
THis showing the most frequent dog prediction for a given dog is golden retriever followed by labrador retriever 

* The most common dog name is Charlie

* Pupper being the most popular Dog stage classification

* There is a positive correlation between favorite count and retweet count
