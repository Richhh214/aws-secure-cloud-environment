# AWS Secure Cloud Environment

This project demonstrates how to build and secure an AWS cloud environment using network segmentation, identity access management, logging, and monitoring.

## Architecture

The environment includes:

- VPC with public and private subnets
- Internet gateway and route tables
- EC2 web server
- Security groups
- IAM role for instance permissions
- CloudTrail logging
- VPC Flow Logs
- S3 secure storage

## VPC Architecture

![VPC](vpc-overview.png)

## Subnet Configuration

![Subnets](subnets.png)

## Route Table

![Route Table](route-table.png)

## Security Group Rules

![Security Group](security-group.png)

## EC2 Instance

![EC2](ec2-instance.png)

## Web Server Test

![Web Server](web-server-test.png)

## CloudTrail Monitoring

![CloudTrail](cloudtrail-events.png)

## VPC Flow Logs

![Flow Logs](flow-logs.png)

## S3 Secure Storage

![S3 Bucket](s3-bucket.png)

## Security Controls Implemented

- Network segmentation using public and private subnets
- Least-privilege IAM role for EC2 access
- Security group restrictions for SSH and HTTP
- CloudTrail API activity logging
- VPC Flow Logs network monitoring
- Secure S3 storage configuration

## Author

Richard Holley
