# Cloud-projects

Here are some of the most relevant projects that I made during my preparation for the AWS Solution Architect Associate certification. They consist in different IaaC deployments using Terraform (HCL) and the AWS Cloudformation service:

+ **First steps on AWS.** Create an architecture which recieves user requests over ACL's port 80/443 in public subnet and then the private subnet over MySQL and MicrosoftSQL ports (1433 and 3306).

+ **Static website on S3.** Use the object-oriented storage of AWS to build a static website using Terraform.

+ **AWS CloudWatch.** Configure a metric alarm to send a SNS topic when the ALB gets greater than the threshold.

+ **AWS Application Load Balancer.** Configure both routing protocols available for ALB:  "Host-Header" and "Path Based" routing over the Cloudformation service.

I'm currently deploying a serverless application on AWS using the following technologies:

+ **OAuth2:** Autentication for end users
+ **Amazon API Gateway:** calling of the Spotify APIs
+ **AWS Secrets Manager:** Storage of refresh tokens and user credentials
+ **Amazon Cognito:** SSO service for end users.
+ **AWS Lambda:** Logic processing of events.
+ **DynamoDB:** Flexible and easy-to-scale Database.

Any help on OAuth2 issues will be appreciated! :smile:
