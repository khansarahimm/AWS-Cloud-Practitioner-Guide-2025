# AWS Cloud Practitioner Exam – Set 1 Answers & Explanations

## Q1. Which AWS service is primarily used for object storage?
**Correct Answer:** B. Amazon S3  

**Explanation:**  
Amazon S3 (Simple Storage Service) is designed for storing and retrieving any amount of data in the form of objects. It is durable, scalable, and widely used for backup, static website hosting, and data archiving.  
- **Why not A (EBS)?** EBS is block storage, used with EC2 instances, not object storage.  
- **Why not C (RDS)?** RDS is for relational databases, not raw file/object storage.  
- **Why not D (DynamoDB)?** DynamoDB is a NoSQL database, not a storage service for objects.  

🔗 [Learn more about Amazon S3](https://docs.aws.amazon.com/s3/index.html)  

---

## Q2. Which AWS service helps you decouple applications?
**Correct Answer:** A. Amazon SQS  

**Explanation:**  
Amazon SQS (Simple Queue Service) enables decoupling by letting different application components communicate asynchronously using message queues. This prevents dependency on real-time availability between services.  
- **Why not B (EC2)?** EC2 provides compute, not decoupling.  
- **Why not C (SNS)?** SNS is a pub/sub messaging service but doesn’t provide message queuing like SQS.  
- **Why not D (CloudTrail)?** CloudTrail records AWS API calls, not used for application decoupling.  

🔗 [Learn more about SQS](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html)  

---

## Q3. What does the AWS Shared Responsibility Model state?
**Correct Answer:** C. AWS manages security *of* the cloud, customers manage security *in* the cloud.  

**Explanation:**  
In the Shared Responsibility Model, AWS secures the underlying infrastructure (hardware, global network, data centers), while customers are responsible for securing their applications, data, and identity configurations.  
- **Why not A?** AWS does not manage *everything*—customers have responsibilities.  
- **Why not B?** Customers do not manage the physical infrastructure.  
- **Why not D?** It is not a "shared account access" model, it’s about security boundaries.  

🔗 [AWS Shared Responsibility Model](https://aws.amazon.com/compliance/shared-responsibility-model/)  

---

## Q4. Which service provides a fully managed NoSQL database?
**Correct Answer:** C. Amazon DynamoDB  

**Explanation:**  
Amazon DynamoDB is a fully managed, highly available NoSQL database service that provides single-digit millisecond latency. It is designed for workloads requiring high scalability and flexible schema.  
- **Why not A (Aurora)?** Aurora is a relational database (SQL-based).  
- **Why not B (Redshift)?** Redshift is a data warehouse for analytics, not NoSQL.  
- **Why not D (Elasticache)?** Elasticache provides in-memory caching, not a primary NoSQL database.  

🔗 [Learn more about DynamoDB](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html)  

---

## Q5. Which service is best suited for delivering content globally with low latency?
**Correct Answer:** A. Amazon CloudFront  

**Explanation:**  
CloudFront is AWS’s Content Delivery Network (CDN) that caches content in edge locations worldwide, reducing latency for global users. It integrates with S3, EC2, and other services for fast delivery.  
- **Why not B (EFS)?** EFS is a shared file system, not a CDN.  
- **Why not C (RDS)?** RDS manages relational databases, not global content delivery.  
- **Why not D (Route 53)?** Route 53 is DNS, not a CDN service.  

🔗 [Learn more about CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)  

---

## Q6. Which AWS service is used for Infrastructure as Code (IaC)?
**Correct Answer:** B. AWS CloudFormation  

**Explanation:**  
AWS CloudFormation automates the provisioning of AWS resources using templates (JSON/YAML). It helps manage infrastructure consistently and repeatably across environments.  
- **Why not A (Config)?** AWS Config is for monitoring compliance, not provisioning.  
- **Why not C (IAM)?** IAM manages identity and access, not infrastructure.  
- **Why not D (Trusted Advisor)?** Trusted Advisor provides recommendations but doesn’t deploy infrastructure.  

🔗 [AWS CloudFormation Documentation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)  

---

## Q7. Which pricing model offers the biggest discount for long-term commitments?
**Correct Answer:** C. Reserved Instances  

**Explanation:**  
Reserved Instances provide significant savings (up to 75%) when you commit to using EC2 or other services for 1–3 years. This is ideal for predictable workloads.  
- **Why not A (On-Demand)?** On-demand is flexible but most expensive.  
- **Why not B (Spot)?** Spot offers deep discounts but instances can be terminated at any time.  
- **Why not D (Savings Plans)?** Savings Plans also provide discounts but are broader in scope; Reserved Instances are specific and usually higher discount for EC2.  

🔗 [Reserved Instances Overview](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-reserved-instances.html)  

---

## Q8. Which AWS service monitors resources and applications in real time?
**Correct Answer:** A. Amazon CloudWatch  

**Explanation:**  
Amazon CloudWatch provides real-time monitoring for metrics, logs, and events, allowing you to set alarms and automate responses. It helps maintain application health and resource performance.  
- **Why not B (CloudTrail)?** CloudTrail tracks API calls, not real-time performance metrics.  
- **Why not C (Inspector)?** Inspector analyzes EC2 instances for vulnerabilities.  
- **Why not D (Shield)?** Shield protects against DDoS attacks, not monitoring.  

🔗 [CloudWatch Documentation](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html)  

---

## Q9. Which service is a serverless compute service?
**Correct Answer:** B. AWS Lambda  

**Explanation:**  
AWS Lambda lets you run code without provisioning or managing servers. You pay only for execution time, making it cost-effective for event-driven workloads.  
- **Why not A (EC2)?** EC2 requires managing servers.  
- **Why not C (Elastic Beanstalk)?** Beanstalk automates deployments but still uses underlying servers.  
- **Why not D (Lightsail)?** Lightsail is simplified VPS, not serverless.  

🔗 [AWS Lambda Documentation](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)  

---

## Q10. Which service provides centralized identity and access management?
**Correct Answer:** C. AWS IAM  

**Explanation:**  
AWS Identity and Access Management (IAM) enables fine-grained access control by defining users, roles, and permissions across AWS services. It ensures secure account management.  
- **Why not A (Organizations)?** Organizations manage multiple AWS accounts, not user permissions directly.  
- **Why not B (KMS)?** KMS is for key management and encryption, not identity.  
- **Why not D (Cognito)?** Cognito is for managing end-user identities in apps, not AWS resource access.  

🔗 [AWS IAM Documentation](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)  
