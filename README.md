# aws-cloudwatch-monitoring-scripts
Amazon CloudWatch Monitoring Scripts for Linux

Original Script Source : https://aws.amazon.com/code/8720044071969977

--namespace-prefix and --metric-name-prefix added to "mon-put-instance-data.pl" script.

Example:
/opt/aws-scripts-mon/mon-put-instance-data.pl  --disk-space-avail  --disk-space-util --disk-path=/ --namespace-prefix=MyProject --metric-name-prefix=AppServer1 --verbose

creates Cloudwatch metrics with "System/MyProject" namespace and "AppServer1 - DiskSpaceAvailable" metric name
