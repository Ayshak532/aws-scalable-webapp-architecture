# Security Policy – AWS Scalable Web Application Architecture

1. Identity and Access Management (IAM)
- Least privilege principle
- IAM roles for EC2 and RDS
- MFA enabled
- Root account restricted

2. Network Security
- VPC with private and public subnets
- Security Groups and Network ACLs
- ALB restricted to trusted traffic

3. Data Protection
- KMS encryption for S3, EBS, RDS
- S3 bucket policies and block public access
- SSL/TLS encryption for in-transit data

4. Monitoring and Auditing
- CloudWatch and CloudTrail enabled
- AWS Config to track configuration changes
- CloudWatch alarms for abnormal activities

5. Backup and Recovery
- Automated RDS backups
- S3 cross-region replication
- Periodic disaster recovery tests

Outcome: Achieved a secure, compliant, and well-monitored AWS environment
