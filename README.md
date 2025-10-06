Terraform Infrastructure Project – AWS Cloud Automation

This project demonstrates how to automate cloud infrastructure setup and scaling using Terraform and AWS.
It provisions a complete environment with EC2 instances, VPC networking, load balancing, auto scaling, and monitoring via AWS CloudWatch — all defined as Infrastructure as Code (IaC).

Project Overview

The goal of this project was to gain hands-on experience with Terraform and AWS services by automating a real-world infrastructure setup.
A PHP website was deployed on EC2 instances, and the infrastructure was designed to scale dynamically based on CloudWatch metrics.

Technologies Used

Terraform

AWS EC2, S3, VPC, IAM, Security Groups

AWS CloudWatch

Auto Scaling Groups and Load Balancer

Linux / Bash

Git and GitHub

Architecture

VPC Setup:

Created a custom VPC with public and private subnets

Configured route tables, Internet Gateway, and NAT Gateway

Compute Resources:

Provisioned EC2 instances for the PHP web application

Deployed application code automatically via user data scripts

Load Balancing and Scaling:

Configured Application Load Balancer (ALB)

Set up Auto Scaling Group (ASG) triggered by CloudWatch metrics

Defined scale-up and scale-down policies in Terraform

Monitoring:

Integrated AWS CloudWatch for metrics and alarms

Created scaling triggers based on CPU utilization

Automation and Modularity:

Used Terraform modules for reusable configurations

Managed resource dependencies and maintained consistent state

Wrote Bash scripts to validate and format Terraform configuration
