# README #

<<<<<<< HEAD
### What is this repository for? ###

Part A of the Coursework1 for Big Data Processing module

### Task ###

Create a Histogram plot that depicts the distribution of tweet sizes (measured in number of characters) among the 
Twitter dataset. To make the data more readable, the histogram must aggregate bars in groups of 5 (that is, first bar 
counts tweets of length 1-5, second bar counts tweets 6-10, and so on) as part of your MapReduce job. Your MapReduce 
program must compute the histogram bins for a correct solution. Aggregating bins outside MapReduce will deduct marks 
from the complete grade.
Note 1: For considering the size of a message you should simply refer to the length() of the String provided as input.

Note 2: There are numerous tweets written in foreign languages, which contain characters with non-standard encoding that might cause some unexpected (i.e. too high) values. This is a common occurrence when dealing with real data. We recommend you filter out all the messages with a length longer than 140 characters. You can also handle them differently if you prefer so and provide an appropriate explanation.  The report has to explain the approach you took, and the reasoning behind it

### To build the project run: ###

### ant clean dist ###
To run the task on the server:
### hadoop jar dist/TweetLength.jar TweetLength /data/olympictweets2016rio out ###
to merge results
### hadoop fs -getmerge out tweets_by_length.txt ###

### chart at https://cloud.highcharts.com/show/onydime ###
=======
# stackoverflow_dates_mapreduce

### What is this repository for? ###

Getting some basic summaries by date from the objects available

### Task ###

data @ /data/stackoverflow in QMUL HDFS.

This job can be run by pointing to a particular folder, but for some schemas CreatedDate is not a valid attribute and Date is present instead.

### ant clean dist ###
To run the task on the server:
### hadoop jar dist/PostDates.jar PostDates /data/stackoverflow/Posts input ###

-rw-r--r--   3 hdfs bigdata   743053995 2015-10-14 21:50 /data/stackoverflow/Badges
-rw-r--r--   3 hdfs bigdata  6635666042 2015-10-14 21:53 /data/stackoverflow/Comments
-rw-r--r--   3 hdfs bigdata 38698669757 2015-10-14 22:04 /data/stackoverflow/PostHistory
-rw-r--r--   3 hdfs bigdata   176833315 2015-10-14 22:04 /data/stackoverflow/PostLinks
-rw-r--r--   3 hdfs bigdata 24458953143 2015-10-14 22:08 /data/stackoverflow/Posts
-rw-r--r--   3 hdfs bigdata   694791809 2015-10-14 22:08 /data/stackoverflow/Users
-rw-r--r--   3 hdfs bigdata  5282807236 2015-10-14 22:09 /data/stackoverflow/Votes

Initial outputs included in the repo
>>>>>>> b60786cce7f1dea1ad3da93aa8d9ffd58826d88e
