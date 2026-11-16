# AWS Cloud Infrastructure & EC2 Deployment

A hands-on, production-oriented AWS Cloud and DevOps learning project focused on designing, deploying, securing, monitoring, and managing cloud infrastructure using Amazon Web Services.

The project provides practical experience with AWS core services, cloud networking, Linux server administration, infrastructure security, automation, monitoring, and application deployment.

---

## Project Overview

| Attribute | Details |
|---|---|
| Project Name | AWS Cloud Infrastructure & EC2 Deployment |
| Project Number | 11 |
| Project Type | Cloud Infrastructure & DevOps Lab |
| Difficulty | Beginner to Intermediate |
| Primary Cloud | Amazon Web Services (AWS) |
| Infrastructure Management | AWS Console and AWS CLI |
| Operating System | Ubuntu Linux |
| Career Target | Junior DevOps Engineer |
| Repository Status | In Progress |

## Objectives

- Understand AWS cloud computing and global infrastructure.
- Configure IAM users, groups, roles, and policies securely.
- Design and implement AWS VPC networking.
- Launch and administer EC2 instances.
- Connect to Linux servers securely using SSH.
- Understand EBS volumes and persistent storage.
- Store and manage objects using Amazon S3.
- Automate AWS operations using AWS CLI.
- Configure security groups and network access controls.
- Monitor infrastructure using Amazon CloudWatch.
- Explore AWS Systems Manager for server administration.
- Deploy and maintain a web application on AWS.
- Apply cost optimization and cloud security best practices.

## Technology Stack

### AWS Services

- AWS IAM
- Amazon VPC
- Amazon EC2
- Amazon EBS
- Amazon S3
- AWS Security Groups
- Network ACLs
- Internet Gateway
- Route Tables
- Elastic IP
- Amazon CloudWatch
- AWS Systems Manager

### Tools and Technologies

- AWS Management Console
- AWS CLI
- Linux / Ubuntu
- SSH
- Git
- GitHub
- Nginx
- Bash

---

## Learning Modules

### Module 01 — AWS Fundamentals

- Cloud computing fundamentals
- AWS global infrastructure
- Regions and Availability Zones
- AWS shared responsibility model
- AWS pricing fundamentals
- AWS Free Tier and billing concepts

### Module 02 — Identity and Access Management (IAM)

- IAM users and groups
- IAM policies
- IAM roles
- Managed and inline policies
- Least privilege principle
- MFA and account security
- IAM best practices

### Module 03 — AWS Networking and VPC

- VPC fundamentals
- CIDR and IP addressing
- Public and private subnets
- Internet Gateway
- Route Tables
- Network ACLs
- VPC architecture and connectivity

### Module 04 — Amazon EC2

- EC2 fundamentals
- Instance types and families
- Amazon Machine Images (AMI)
- Key pairs
- Instance launch configuration
- Instance lifecycle management
- EC2 pricing and cost considerations

### Module 05 — Linux Server Administration on EC2

- Secure SSH access
- Linux users and permissions
- Package management
- Process and service management
- Disk and memory monitoring
- Firewall configuration
- Server troubleshooting

### Module 06 — Amazon EBS and Storage

- EBS volume fundamentals
- Volume types
- Attach and detach operations
- Filesystem creation and mounting
- Persistent storage
- Snapshots and backup concepts

### Module 07 — Amazon S3

- S3 buckets and objects
- Bucket configuration
- Object permissions
- Versioning
- Lifecycle policies
- Encryption
- Secure storage practices

### Module 08 — AWS CLI and Automation

- AWS CLI installation and configuration
- Profiles and credentials
- AWS CLI commands
- Resource inspection
- Scripting AWS operations
- Safe automation practices

### Module 09 — AWS Network and Infrastructure Security

- Security Groups
- Network ACLs
- Inbound and outbound rules
- SSH access restrictions
- Network segmentation
- Secure architecture design
- Cloud security best practices

### Module 10 — Elastic IP and DNS Concepts

- Public and private IP addresses
- Elastic IP fundamentals
- DNS fundamentals
- Domain and server connectivity
- Route 53 concepts
- Application access configuration

### Module 11 — Monitoring and Systems Management

- Amazon CloudWatch fundamentals
- EC2 metrics
- CloudWatch alarms
- Log monitoring
- AWS Systems Manager overview
- Session Manager
- Infrastructure health checks

### Module 12 — Secure Application Deployment

- Application deployment on EC2
- Nginx installation and configuration
- Reverse proxy fundamentals
- Application service management
- Domain connectivity
- HTTPS and SSL concepts
- Deployment verification

### Module 13 — Final Production-Oriented Project

- Design a secure AWS architecture
- Configure IAM permissions
- Build VPC networking
- Provision an EC2 application server
- Configure storage
- Deploy a web application
- Configure monitoring
- Document infrastructure
- Review security and costs
- Perform verified lab-resource cleanup

---

## Planned Repository Structure

```text
AWS-Cloud-Infrastructure-EC2-Deployment/
│
├── README.md
├── .gitignore
│
├── docs/
│   ├── architecture/
│   ├── aws-fundamentals/
│   ├── iam/
│   ├── networking/
│   ├── ec2/
│   ├── storage/
│   ├── security/
│   ├── monitoring/
│   └── deployment/
│
├── labs/
│   ├── 01-aws-fundamentals/
│   ├── 02-iam/
│   ├── 03-vpc-networking/
│   ├── 04-ec2/
│   ├── 05-linux-server-administration/
│   ├── 06-ebs-storage/
│   ├── 07-s3/
│   ├── 08-aws-cli/
│   ├── 09-infrastructure-security/
│   ├── 10-elastic-ip-dns/
│   ├── 11-monitoring-systems-manager/
│   ├── 12-application-deployment/
│   └── 13-final-project/
│
├── scripts/
│   ├── aws/
│   ├── bash/
│   └── monitoring/
│
├── configs/
│
├── diagrams/
│
└── reports/
```

The directory structure will be created gradually as the corresponding modules are completed.

## AWS Security Principles

This project follows practical cloud security principles:

- Apply least-privilege IAM permissions.
- Never commit AWS access keys or secret keys.
- Never upload private SSH keys or certificates.
- Avoid exposing SSH to the entire internet.
- Restrict inbound and outbound network access.
- Use secure authentication methods.
- Review resource permissions before deployment.
- Verify infrastructure configuration after every change.
- Keep credentials outside the Git repository.

## AWS Cost Management

Cloud resources may generate charges even when they are not actively used.

Before provisioning resources:

- Review the AWS pricing model.
- Check the current Free Tier eligibility and applicable limits.
- Understand EC2 instance pricing.
- Review EBS storage and snapshot costs.
- Understand Elastic IP charges.
- Avoid creating NAT Gateways unless specifically required and cost-approved.
- Monitor resource usage and billing.
- Identify lab-created resources before cleanup.
- Never delete existing production or assignment infrastructure.

No AWS resources should be provisioned as part of repository initialization.

## Learning Methodology

Each module will follow a practical learning workflow:

1. Understand the concepts.
2. Review the architecture.
3. Prepare the lab environment.
4. Perform practical exercises.
5. Verify the actual AWS resource state.
6. Troubleshoot errors.
7. Document the work.
8. Complete assessment questions.
9. Review security and cost implications.

## Project Safety Rules

- Existing AWS infrastructure must remain untouched.
- Lab resources must be isolated from existing projects.
- Never modify production resources without explicit authorization.
- Check the active AWS account and region before AWS operations.
- Review potential costs before creating paid resources.
- Never run destructive cleanup commands without reviewing the target resources and obtaining explicit approval.
- Do not store credentials in source code or Git history.

## Project Progress

| Module | Topic | Status |
|---|---|---|
| 01 | AWS Fundamentals | Not Started |
| 02 | IAM | Not Started |
| 03 | VPC Networking | Not Started |
| 04 | EC2 | Not Started |
| 05 | Linux Server Administration | Not Started |
| 06 | EBS Storage | Not Started |
| 07 | Amazon S3 | Not Started |
| 08 | AWS CLI and Automation | Not Started |
| 09 | Infrastructure Security | Not Started |
| 10 | Elastic IP and DNS | Not Started |
| 11 | Monitoring and Systems Manager | Not Started |
| 12 | Secure Application Deployment | Not Started |
| 13 | Final Project | Not Started |

## Author

**Arifuzzaman Hredoy**

- GitHub: [arifuzzaman-hredoy](https://github.com/arifuzzaman-hredoy)
- Project Repository: [AWS-Cloud-Infrastructure-EC2-Deployment](https://github.com/arifuzzaman-hredoy/AWS-Cloud-Infrastructure-EC2-Deployment)

---

This project is part of a practical DevOps learning portfolio focused on developing real-world cloud infrastructure, automation, deployment, security, and troubleshooting skills.
