# Text Classification - Using ABC News, and SparkML
The motivation of this example was text classification to determine what
topic some text is about.  
For example, you could look at a series of tweets, and determine the topics
discussed.

I used the ABC news for the labelled data, by downloading the RSS feeds from
different news 'topics' (business, sport, etc).  
Then I used Spark + MLlib to make a simple classifier.  

The file structure is:
- [download_news_rss.ipynb](./download_news_rss.ipynb) helps you download the news data.
  (This is a python notebook)
    - You need requirements_py.txt in your python to download/parse the data
- news_data.csv contains pre-downloaded data, if you want to skip the above step
- [abc_news_spark_scala.ipynb](./abc_news_spark_scala.ipynb) prepares the classifier (a spark/scala notebook)
- [models](./models) dir, contains the output models
