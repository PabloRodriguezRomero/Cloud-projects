# Cloud-projects

Here are some of the most relevant projects that I made during my preparation for the AWS Solution Architect Associate certification. These consist of various IaaC deployments using Terraform (HCL) and the AWS Cloudformation service:

+ **First steps on AWS.** Create an architecture that receives user requests over ACL's port 80/443 in the public subnet and then in the private subnet over MySQL and Microsoft SQL ports (1433 and 3306).

+ **Static website on S3.** Use the object-oriented storage of AWS to build a static website using Terraform.

+ **AWS CloudWatch.** Configure a metric alarm to send an SNS topic when the ALB gets greater than the threshold.

+ **AWS Application Load Balancer.** Configure both routing protocols available for ALB:  "Host-Header" and "Path-Based" routing over the Cloudformation service.

I'm currently deploying a serverless application on AWS using the following technologies:

+ **OAuth2:** End-user authentication.
+ **Amazon API Gateway:** access to Spotify APIs
+ **AWS Secrets Manager:** Storage of refresh tokens and user credentials
+ **Amazon Cognito:** SSO service for end users.
+ **AWS Lambda:** Event logic processing.
+ **DynamoDB:** A flexible and easy-to-scale Database.

Any help on OAuth2 issues will be appreciated! :smile:
