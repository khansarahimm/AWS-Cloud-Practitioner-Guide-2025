# Set 1 - AWS MCQ Answers with Explanations

## Question 1: Which AWS service is primarily used for object storage?
**Correct Answer:** Amazon S3  

**Explanation:**  
Amazon S3 (Simple Storage Service) is specifically designed for storing and retrieving any amount of unstructured data (objects) such as files, images, and backups. It offers durability, scalability, and integration with many AWS services.  
- **Why not EBS?** Elastic Block Store is block storage, best suited for attaching to EC2 instances for persistent storage.  
- **Why not RDS?** Relational Database Service is used for structured relational data, not general object storage.  
- **Why not EFS?** Elastic File System is a managed file system, not optimized for object storage.  

[Read more in AWS Docs](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)

---

## Question 2: Which service helps in decoupling applications using message queues?
**Correct Answer:** Amazon SQS  

**Explanation:**  
Amazon SQS (Simple Queue Service) is a fully managed message queuing service that allows decoupling between components of a distributed system. Producers send messages into a queue, and consumers process them asynchronously, improving scalability and fault tolerance.  
- **Why not SNS?** Simple Notification Service is used for pub/sub messaging but not for message queuing.  
- **Why not Kinesis?** Kinesis is designed for real-time streaming data, not asynchronous queue processing.  
- **Why not Step Functions?** Step Functions orchestrate workflows but don’t handle message queuing.  

[Read more in AWS Docs](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html)

---

## Question 3: Which AWS service is best suited for running containers without managing servers?
**Correct Answer:** AWS Fargate  

**Explanation:**  
AWS Fargate is a serverless compute engine for containers that lets you run Docker containers without managing the underlying EC2 instances or clusters. It abstracts away server provisioning and scaling.  
- **Why not ECS?** Amazon ECS is the container orchestration service but still requires managing servers unless used with Fargate.  
- **Why not EKS?** Amazon EKS is Kubernetes service; still requires some cluster management unless combined with Fargate.  
- **Why not Lambda?** Lambda runs functions, not full containers for long-running workloads.  

[Read more in AWS Docs](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/what-is-fargate.html)

---

## Question 4: Which AWS service is ideal for content delivery globally with low latency?
**Correct Answer:** Amazon CloudFront  

**Explanation:**  
Amazon CloudFront is a Content Delivery Network (CDN) that delivers content to users globally with low latency by caching copies of content in edge locations near the users.  
- **Why not S3?** S3 stores data but doesn’t distribute globally with caching.  
- **Why not Route 53?** Route 53 is DNS service, not for content delivery.  
- **Why not Global Accelerator?** Global Accelerator improves routing to applications but is not a CDN for caching content.  

[Read more in AWS Docs](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)

---

## Question 5: Which service is used for infrastructure as code (IaC) on AWS?
**Correct Answer:** AWS CloudFormation  

**Explanation:**  
AWS CloudFormation automates infrastructure provisioning using templates written in YAML or JSON. It allows you to manage infrastructure as code and ensures consistency across deployments.  
- **Why not OpsWorks?** OpsWorks is a configuration management service, not as widely used for IaC as CloudFormation.  
- **Why not Elastic Beanstalk?** Beanstalk is for deploying applications, not full IaC templates.  
- **Why not Systems Manager?** Systems Manager manages configurations and operations, but not full infrastructure templates.  

[Read more in AWS Docs](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)

---

## Question 6: Which AWS service allows secure management of encryption keys?
**Correct Answer:** AWS KMS (Key Management Service)  

**Explanation:**  
AWS KMS allows you to create, manage, and control cryptographic keys used to encrypt data across AWS services. It integrates seamlessly with S3, RDS, and EBS.  
- **Why not Secrets Manager?** Secrets Manager stores credentials, not cryptographic keys.  
- **Why not IAM?** IAM controls permissions but not encryption keys.  
- **Why not CloudHSM?** CloudHSM is a hardware-based key storage but requires more management, unlike managed KMS.  

[Read more in AWS Docs](https://docs.aws.amazon.com/kms/latest/developerguide/overview.html)

---

## Question 7: Which AWS service is fully managed for relational databases?
**Correct Answer:** Amazon RDS  

**Explanation:**  
Amazon RDS (Relational Database Service) manages relational databases like MySQL, PostgreSQL, SQL Server, and Oracle. It automates backups, patching, scaling, and replication.  
- **Why not DynamoDB?** DynamoDB is NoSQL, not relational.  
- **Why not Redshift?** Redshift is a data warehouse, not general relational DB service.  
- **Why not Aurora?** Aurora is part of RDS family but considered a specific engine, not the service itself.  

[Read more in AWS Docs](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)

---

## Question 8: Which service is designed for monitoring and observability of AWS resources?
**Correct Answer:** Amazon CloudWatch  

**Explanation:**  
Amazon CloudWatch collects logs, metrics, and events, providing insights into system performance, application monitoring, and alerting.  
- **Why not AWS Config?** Config tracks configuration changes, not full monitoring.  
- **Why not CloudTrail?** CloudTrail tracks API activity, not metrics/logs.  
- **Why not X-Ray?** X-Ray traces applications, not overall AWS resource monitoring.  

[Read more in AWS Docs](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html)

---

## Question 9: Which service is best suited for serverless functions?
**Correct Answer:** AWS Lambda  

**Explanation:**  
AWS Lambda lets you run code in response to events without provisioning or managing servers. It scales automatically and charges per execution and runtime.  
- **Why not Fargate?** Fargate is for containers, not short serverless functions.  
- **Why not EC2?** EC2 requires manual provisioning and server management.  
- **Why not Step Functions?** Step Functions orchestrate workflows, not execute serverless functions themselves.  

[Read more in AWS Docs](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)

---

## Question 10: Which AWS service helps in DNS management?
**Correct Answer:** Amazon Route 53  

**Explanation:**  
Amazon Route 53 is a highly available DNS web service that routes end users to applications, supports domain registration, and integrates with AWS resources.  
- **Why not CloudFront?** CloudFront is a CDN, not DNS.  
- **Why not Global Accelerator?** Accelerator optimizes routing but not DNS resolution.  
- **Why not VPC?** VPC is a networking construct, not DNS management.  

[Read more in AWS Docs](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html)
