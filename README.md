# Lita_EC2_Project 
Building a Scalable Web Infrastructure for "SmartShop"
## Introduction 
This Project documents the process of launching EC2 Instance displaying Apache Web Server.
Amazon EC2 instances offer a scalable, flexible, and cost-effective solution for hosting web applications like Apache.
### Created VPC
Amazon Virtual Private Cloud (VPC)creates a secure, isolated virtual network in the AWS environment. 
It has a CIDR O 10.0.0.0/16. Below is the image 
![vpc image](/VPC.png)
### Created Subnets
I created both public and private subnets.The VPC supports public and private subnets, ensuring secure and optimized traffic flow. Public subnets handle internet-facing components, while private subnets secure sensitive backend operations.
#### Private Subnet
![PrivateSubnet image](/Private_Subnet.png)
#### Public Subnet
![PublicSubnet image](/Public_Subnet.png)
### Created Security Group
Created security group with inbound rule. Security Groups act as virtual firewalls, restricting inbound and outbound traffic to EC2 instances.
HTTP traffic are allowed for web access, while SSH is restricted to specific IPs for administrative access, protecting against unauthorized access.
Below is the image
![Security Group image](/Security_Group.png)
### Instance ID
Below is the image
![Instance ID image](/Instance_ID.png)
### Apache
Below is an image showing Apache is successfully running on the EC2 Instance. This was configured on EC2 instances using Amazon Linux 2 AMI.
![Apache image](/Test_Page_Apache.png)
## EC2 Details
Below is an image of the EC2 details after creation with Apache running on it.
This will provide SmartShop with a secure, scalable, and cost-efficient infrastructure, ensuring seamless user experiences allowing on-demand scaling and supporting traffic surges.
![EC2 image](/EC2_Instance_Details.png)
