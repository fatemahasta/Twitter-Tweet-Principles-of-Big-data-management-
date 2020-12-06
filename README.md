# Twitter Tweet (Principles-of-Big-data-management)

## Objective:
• The main aim of this phase is to develop a system to store, analyze, and visualize a social network data.
• Tasks:
1. Collect social network data (e.g. tweets) in JSON format.
2. Extracting the hashtags, URLs from the collected tweets.
3. Store the text content (e.g. tweet’s text) from the data into a file in HDFS.
4. Run a Word Count program in Apache Spark, Apache Hadoop on extracted hashtags, URLs files and store the output and log files locally.
5. Analyzing and Visualizing Twitter data on Mobiles

## Applications/Software’s Used: Apache Spark, Hadoop, Scala, Cloudera, Twitter Developer Account, Python.

## Collecting tweets from Twitter:
• Firstly, we have created a developer account in Twitter using below link. https://apps.twitter.com/
• We have written python program that is used to fetch tweets in JSON format. (TweetsExtract.py)
• The extracted file in JSON format contains all the tweet details such as id, created at, text, URL, hashtags etc.
• From JSON tweets file only the hashtags and URLs content is extracted using scala programs each for hastags and URLs. Then fetched details are stored in files.
Run the Word Count program in Apache Spark and Apache Hadoop the extracted hashtags/URLs and collect the output and log files:
1. Word Count Program in Apache Spark: 
* We have used IntelliJ IDEA software to run word count program on extracted hastags/URLs using Apache Spark and Scala. 
2. Word Count Program in Apache Hadoop: 
* In order to run the word count program using Apache Hadoop we have written the code in java. In the program TokenizerMapper class is created by extending the Mapper class and the map function is implemented by overriding the map method in the Mapper class. The mapper functions takes a key-value pair as an input and outputs a key-values pair as an output

## Analyzing and Visualizing Twitter data on Mobiles

The main theme of this phase is to do big data analytics on the Mobile phones. Based on the twitter tweets, we predicted few interesting query analysis and visualization on mobile phone twitter data. First, we collected the tweets regarding the mobile phone data from the twitter API. By using the collected data, we build 10 interesting queries which results a data analysis on the twitter data. Visualization is done for on the result sets and viewed in some pictorial representations like pie chart and bar graphs
