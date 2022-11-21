# First Steps on AWS

Recently I get the AWS SAA certification on my way to achieve a cloud position role for the next year. During my preparation in AWS exams I learned about some
elements that I want to get in touch with:

-Least privilege policy attached to admin
-VPC setup and Subnetting
-Internet Gateway
-Route tables and ACL's
  
In this way, I created an architecture which recieves user requests over ACL's port 80/443 in public subnet and then the private subnet over MySQL and
MicrosoftSQL ports (1433 and 3306).

Next step will be the automation of these and more services with Cloudformation!



![AWS-Diagram-Project (1)](https://user-images.githubusercontent.com/88206475/203133983-5fbb8edf-5477-43ac-92f7-92d8e2c83d16.png)
