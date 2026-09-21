AWS Infrastructure Lab

Project Overview

This project documents my hands-on practice building and managing a small cloud infrastructure environment using Amazon Web Services (AWS).

The project focuses on networking, compute, storage, identity and access management, security, and monitoring.

Objectives

* Create an AWS VPC
* Configure public and private subnets
* Deploy an EC2 instance
* Configure security groups
* Practice IAM and least-privilege access
* Create and manage an S3 bucket
* Configure CloudWatch monitoring
* Troubleshoot cloud connectivity problems
* Document cloud infrastructure

AWS Services

Service	Purpose
VPC	Network infrastructure
EC2	Virtual server
IAM	Identity and access management
S3	Object storage
CloudWatch	Monitoring
Security Groups	Network access control

Architecture

                    AWS Cloud
                        |
                       VPC
                  10.0.0.0/16
                        |
              ┌─────────┴─────────┐
              │                   │
        Public Subnet        Private Subnet
         10.0.1.0/24          10.0.2.0/24
              │
            EC2
              │
         Web Server

The architecture may be modified as the lab develops.

Tasks

* [ ]	Create VPC
* [ ]	Create subnets
* [ ]	Configure route tables
* [ ]	Configure internet connectivity
* [ ]	Create security group
* [ ]	Launch EC2 instance
* [ ]	Connect to EC2
* [ ]	Install/configure web server
* [ ]	Create S3 bucket
* [ ]	Practice IAM
* [ ]	Apply least-privilege permissions
* [ ]	Configure CloudWatch monitoring
* [ ]	Troubleshoot a controlled connectivity problem
* [ ]	Document the architecture

Security

Security is a key part of this project.

The lab will follow principles including:

* Least privilege
* Minimal network exposure
* Restricted security-group rules
* Strong authentication
* No unnecessary public access
* Protection of credentials and secrets

Troubleshooting

EC2 Connectivity Problem

Problem:

To be documented after introducing or encountering a controlled connectivity problem.

Symptoms:

To be documented.

Investigation:

The investigation may include checking:

* Security Group rules
* Route tables
* Subnet configuration
* Network connectivity
* Instance status
* Operating-system firewall
* Service status

Root Cause:

To be documented.

Solution:

To be documented.

Verification:

Connectivity will be tested again after applying the fix.

Skills Demonstrated

* AWS
* VPC
* EC2
* S3
* IAM
* Security Groups
* CloudWatch
* Cloud networking
* Cloud security
* Troubleshooting
* Infrastructure documentation

Evidence

Architecture diagrams and screenshots will be added as the project progresses.

Security Notice

No AWS access keys, secret keys, passwords, private keys, or other credentials will be uploaded to this repository.

Lessons Learned

This section will be updated with the AWS concepts, troubleshooting techniques, and security practices learned during the project.
