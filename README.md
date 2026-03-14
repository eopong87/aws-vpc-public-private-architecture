# aws-vpc-public-private-architecture# AWS VPC Public / Private Architecture Lab

## Project Overview
This project demonstrates a basic AWS cloud architecture using a Virtual Private Cloud (VPC) with both public and private EC2 instances.

The goal of this lab was to understand how cloud networks isolate internal services while allowing controlled communication between servers.

## Architecture

Internet
   │
Public Web Server (Nginx)
   │
AWS VPC Internal Network
   │
Private Application Server

## Technologies Used

- AWS EC2
- AWS VPC
- Security Groups
- Ubuntu Linux
- Nginx

## Deployment Steps

1. Created a VPC environment
2. Launched a public EC2 instance
3. Installed Nginx on the public web server
4. Launched a private EC2 instance without a public IP
5. Configured security groups
6. Tested internal communication using ping

## Key Concepts Learned

Public vs Private Infrastructure  
Security Groups (AWS Firewall)  
Internal VPC Networking  
Basic Linux Administration

## Screenshots

Add screenshots of:
- EC2 instances
- Security group rules
- Ping communication
- Nginx web page


## Future Improvements

Implement an Application Load Balancer  
Add multiple web servers for high availability  
Create an Auto Scaling Group  
Add a private database tier  
Automate infrastructure using Terraform
