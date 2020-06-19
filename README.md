# aws_cloudwatch
This is a python script for Nagios chec_nrpe 

The script assumes you are running it on a server with IAM role assigned with read access to the relevant AWS account

It returns an exit code of 0 for success and 2 for critical alert to Nagios including what alarms descriptions are returned
