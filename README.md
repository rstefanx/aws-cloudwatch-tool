aws-cloudwatch-tool
===================

Amazon CloudWatch query tool for Zabbix

Cloudwatch query script for use with Zabbix (or any other monitoring tool)
Queries for the values over the last 20 minutes and returns the most recent value
Author: Stefan Radu
Web: https://github.com/rstefanx

Parameters:
- MetricName. Eg: CurrConnections
- Function. Can be one of the following: Average, Sum, SampleCount, Maximum, or Minimum.
- Dimension. Eg: CacheClusterId=cache,CacheNodeId=0001
- Region. Eg: eu-west-1
- AWS_Access_Key
- AWS_Secret_Access_Key
