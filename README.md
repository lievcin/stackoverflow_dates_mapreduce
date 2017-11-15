# README #

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
