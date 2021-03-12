# Tweet Popularity
This work is as a project for the Web Science course (2017), at Politecnico of Milan. 



**Research goal**: given a specific museum, predict the number of retweets that a tweet about it will have.  With this information a museum could tune it's social media interactions in order to be more popular.

## Tools
The code is developed and run on the free version of databricks (https://databricks.com/), called "databricks community edition". Databricks is an industry-leading, cloud-based data engineering tool used for processing and transforming massive quantities of data and exploring the data through machine learning models.

Some consideration on this tool and the limitations of the free version are written in the project conclusions.

## Dataset
The starting dataset contains 2376642 tweets about 120 museums, collected from 16/06/2016 to 01/12/2016. I decided to enlarge this dataset by scraping the Twitter page.

## Repository organization
There are 4 notebook inside the "databricks notebooks" folder:

- Introduction: a small introduction to the work
- Data Ingestion: the initial analysis of the dataset and the collection of data from Twitter
- Data Ingestion Function: python functions to collect data about museums.
- Popularity Predictor: training and testing a model to predict the "number of retweet" of a tweet
- Conclusion: display of the results and consideration about the problem, how it was approached and the tools that were used