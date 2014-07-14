aws-cloudwatch-tool
===================
Author: Stefan Radu <br>
Web: https://github.com/rstefanx


Amazon CloudWatch query tool is a script that can be used with Zabbix or any other monitoring tool to get values from AWS Cloudwatch. It queries for the values over the last 20 minutes and returns the most recent value. Can be modified to be used with Nagios or turned into a Munin plugin.<br>
It needs Python 2.7 and Boto library.


Parameters:
- MetricName. Eg: CurrConnections
- Function. Can be one of the following: Average, Sum, SampleCount, Maximum, or Minimum.
- Dimension. Eg: CacheClusterId=cache,CacheNodeId=0001
- Region. Eg: eu-west-1
- AWS_Access_Key
- AWS_Secret_Access_Key
