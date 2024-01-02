# AWS-Auto-Terminate-Services
Testing a Lambda service to auto-terminate any zombie instances or services to stop incurring costs

For the permissions JSON, this is an AWS Super role for "AWS Lambda Service" that is trying to automate the closure of services before incuring costs. This doesn't follow the "Least Privilege Model" and is not recommended for root users.
