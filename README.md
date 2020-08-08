# Spark-Project---Apache-log-parsing
In this project, we will parse Apache logs to get some meaningful insights from the logs.

Data set -

Dataset is located in /data/spark/project/NASA_access_log_Aug95.gz directory in HDFS

Above dataset is access log of NASA Kennedy Space Center WWW server in Florida.

The logs are an ASCII file with one line per request, with the following columns:

host - making the request. A hostname when possible, otherwise the Internet address if the name could not be looked up.
timestamp - in the format "DAY MON DD HH:MM:SS YYYY", where DAY is the day of the week, MON is the name of the month, DD is the day of the month, HH:MM:SS is the time of day using a 24-hour clock, and YYYY is the year. The timezone is -0400.
request URL - given in quotes.
HTTP reply code.
Bytes returned by the server.
Note that from 01/Aug/1995:14:52:01 until 03/Aug/1995:04:36:13 there are no accesses recorded, as the Web server was shut down, due to Hurricane Erin.
