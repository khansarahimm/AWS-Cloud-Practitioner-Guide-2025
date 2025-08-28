# AWS Cloud Practitioner Practice Exam 2 – 65 Questions

**Version:** 120  
**Time Allowed:** 60 minutes  
**Total Questions:** 65  

---

## Instructions

- Each question has four options (A, B, C, D).  
- Choose the **best answer**.  
- Attempt all questions **within 60 minutes**.  
- Do not look at answers until you finish.  
- Exam includes **knowledge-based, scenario-based, and best-practice questions**.  

---

## Questions

1. A startup wants to host a web application without managing servers. They expect unpredictable traffic spikes. Which AWS service is most suitable?  
A) EC2 with Auto Scaling  
B) Lambda  
C) S3  
D) RDS  

2. Your company stores monthly financial reports in S3. The files are rarely accessed but must be retained for years. Which storage class provides the lowest cost?  
A) S3 Standard  
B) S3 Standard-IA  
C) Glacier Deep Archive  
D) EBS  

3. Your application requires a relational database with automatic failover across multiple availability zones. Which AWS service is appropriate?  
A) DynamoDB  
B) Aurora  
C) RDS Multi-AZ  
D) Redshift  

4. Your team wants to automate code deployment and infrastructure provisioning for multiple environments. Which service should you use?  
A) CloudFormation  
B) Lambda  
C) EC2  
D) Step Functions  

5. A company needs to deliver a global marketing website with low latency and caching. Which combination of services is best?  
A) S3 + CloudFront  
B) EC2 + ELB  
C) DynamoDB + Lambda  
D) RDS + S3  

6. Your security team wants to enforce organization-wide encryption policies for all S3 buckets. Which service is best?  
A) KMS + Bucket Policies  
B) IAM  
C) Secrets Manager  
D) CloudTrail  

7. Your application must process real-time IoT sensor data and push insights to dashboards. Which service combination is appropriate?  
A) Kinesis Data Streams + Lambda + CloudWatch  
B) SQS + EC2  
C) SNS + S3  
D) DynamoDB + RDS  

8. You want to allow temporary, limited access to S3 objects for external partners. Which approach is best?  
A) Pre-signed URLs  
B) IAM Roles  
C) Bucket Policies only  
D) KMS  

9. Your organization has multiple AWS accounts and wants centralized billing and consolidated reporting. Which service should you use?  
A) AWS Organizations  
B) IAM  
C) Trusted Advisor  
D) Config  

10. Your finance team wants to see projected AWS costs and receive alerts when costs exceed thresholds. Which services are required?  
A) Cost Explorer + AWS Budgets  
B) CloudWatch  
C) Trusted Advisor  
D) Billing Dashboard  

11. You want to run containerized workloads without managing servers and pay only for what you use. Which service is most suitable?  
A) Fargate  
B) ECS on EC2  
C) Lambda  
D) Elastic Beanstalk  

12. Your company wants to monitor API activity, including failed login attempts and resource changes. Which service should you enable?  
A) CloudTrail  
B) CloudWatch Logs  
C) Config  
D) Trusted Advisor  

13. A company wants to enable multi-factor authentication for all users and centrally manage permissions. Which combination should they implement?  
A) IAM + MFA  
B) KMS + IAM  
C) SSO + CloudTrail  
D) Cognito + KMS  

14. Your team wants to store frequently accessed data in memory for low-latency application access. Which service is best?  
A) ElastiCache  
B) DynamoDB  
C) RDS  
D) S3  

15. You want to run batch analytics jobs on a large dataset stored in S3 without managing servers. Which AWS service should you use?  
A) Athena  
B) EMR  
C) Lambda  
D) Redshift  

16. A company wants to deliver personalized email notifications to customers based on events in their application. Which service combination is most suitable?  
A) SNS + SES  
B) SQS + Lambda  
C) CloudFront + S3  
D) DynamoDB + Lambda  

17. Your organization needs to track configuration changes, resource compliance, and audit history across accounts. Which service is appropriate?  
A) Config  
B) CloudWatch  
C) Trusted Advisor  
D) CloudTrail  

18. A mobile app requires real-time push notifications for user activity. Which service should you use?  
A) SNS  
B) SQS  
C) Lambda  
D) CloudFront  

19. Your team wants to enforce cost optimization recommendations across all AWS accounts. Which service should they use?  
A) Trusted Advisor  
B) CloudWatch  
C) Config  
D) Cost Explorer  

20. You want to enable global DNS routing and failover for high availability. Which service is best?  
A) Route 53  
B) CloudFront  
C) ELB  
D) VPC  

21. Your application needs a managed NoSQL database with single-digit millisecond latency. Which service should you choose?  
A) DynamoDB  
B) RDS  
C) S3  
D) Redshift  

22. You want to allow developers to store API keys and database credentials securely. Which service should you use?  
A) Secrets Manager  
B) IAM  
C) KMS  
D) CloudTrail  

23. You need to distribute incoming application traffic across multiple EC2 instances. Which service combination is most appropriate?  
A) ELB + Auto Scaling  
B) CloudFront + S3  
C) Lambda + DynamoDB  
D) RDS + S3  

24. Your team wants to analyze video content to detect objects and activities in real-time. Which service should they use?  
A) Rekognition Video  
B) Polly  
C) Transcribe  
D) Comprehend  

25. You want a managed service to schedule and orchestrate serverless workflows visually. Which service is appropriate?  
A) Step Functions  
B) Lambda  
C) CloudFormation  
D) ECS  

26. A company wants to perform sentiment analysis on social media text data. Which AWS service should be used?  
A) Comprehend  
B) Lex  
C) Polly  
D) Translate  

27. You want to query structured and unstructured data stored in S3 using standard SQL. Which service is best?  
A) Athena  
B) Redshift  
C) EMR  
D) DynamoDB  

28. Your application requires a managed message queue to decouple services and ensure delivery. Which service should you use?  
A) SQS  
B) SNS  
C) Kinesis  
D) Lambda  

29. You want to monitor AWS resource usage, set alarms, and trigger automated actions. Which service provides this functionality?  
A) CloudWatch  
B) CloudTrail  
C) Config  
D) Trusted Advisor  

30. You want to deliver streaming media globally with low latency. Which service is most suitable?  
A) CloudFront  
B) S3  
C) ELB  
D) Route 53  

31. Your team wants to analyze log files for operational insights. Which service should you use?  
A) CloudWatch Logs  
B) CloudTrail  
C) Config  
D) Trusted Advisor  

32. A company wants to host multiple static websites under the same domain with routing control. Which service should be used?  
A) Route 53  
B) CloudFront  
C) ELB  
D) S3  

33. Your mobile app requires user authentication with social identity providers. Which AWS service is best?  
A) Cognito  
B) IAM  
C) KMS  
D) SSO  

34. You want to provide temporary, least-privilege access to resources in another AWS account. Which is the best approach?  
A) IAM Role with AssumeRole  
B) Pre-signed URL  
C) Bucket Policy  
D) KMS Key  

35. You need to reduce storage costs by automatically transitioning older objects in S3 to lower-cost tiers. Which feature should you use?  
A) Lifecycle Policies  
B) Versioning  
C) MFA Delete  
D) Object Lock  

36. You want to process events asynchronously from multiple producers and deliver them to consumers reliably. Which service is appropriate?  
A) SQS  
B) SNS  
C) Lambda  
D) CloudFront  

37. Your team wants to collect and analyze streaming clickstream data in near real-time. Which service should you use?  
A) Kinesis Data Streams  
B) SQS  
C) Lambda  
D) CloudWatch  

38. Your organization wants to perform cost optimization checks across AWS accounts. Which service is most suitable?  
A) Trusted Advisor  
B) Config  
C) CloudWatch  
D) CloudTrail  

39. Your web application needs a relational database for high-performance transactions with automatic backups. Which service should you use?  
A) RDS  
B) DynamoDB  
C) Redshift  
D) S3  

40. You want to store session state for a web application with low latency. Which service is best?  
A) ElastiCache  
B) S3  
C) DynamoDB  
D) RDS  

41. Your company wants to audit API activity for compliance. Which AWS service is required?  
A) CloudTrail  
B) CloudWatch  
C) Config  
D) Trusted Advisor  

42. You want to convert speech to text in real-time for customer support calls. Which AWS service should you use?  
A) Transcribe  
B) Polly  
C) Lex  
D) Comprehend  

43. You need a managed graph database to store and query highly connected datasets. Which service should you use?  
A) Neptune  
B) DynamoDB  
C) RDS  
D) Redshift  

44. You want to monitor service limits and receive optimization recommendations. Which service provides this?  
A) Trusted Advisor  
B) CloudWatch  
C) Config  
D) CloudTrail  

45. Your application requires automatic scaling based on CPU usage. Which service combination should be used?  
A) EC2 + Auto Scaling  
B) Lambda + CloudWatch  
C) ECS + CloudFront  
D) S3 + CloudFront  

46. You need to create a data warehouse for analytical workloads. Which service is most suitable?  
A) Redshift  
B) RDS  
C) DynamoDB  
D) S3  

47. Your team wants a fully managed search service with real-time indexing. Which service is appropriate?  
A) OpenSearch Service  
B) Athena  
C) Redshift  
D) S3  

48. You want to enforce encryption for all EBS volumes by default. Which AWS feature should you use?  
A) Default EBS encryption  
B) KMS + IAM  
C) CloudTrail  
D) Trusted Advisor  

49. Your team needs a managed workflow service to coordinate microservices and serverless tasks visually. Which AWS service should you choose?  
A) Step Functions  
B) Lambda  
C) ECS  
D) CloudFormation  

50. You want to analyze images and detect inappropriate content. Which service is best?  
A) Rekognition  
B) Lex  
C) Polly  
D) Comprehend  

51. Your application requires near real-time analytics on clickstream data. Which service combination is appropriate?  
A) Kinesis Data Streams + Kinesis Data Analytics  
B) SQS + Lambda  
C) CloudWatch + Lambda  
D) DynamoDB + RDS  

52. You need to store large datasets for analytics without managing servers and query them using SQL. Which combination should you use?  
A) S3 + Athena  
B) Redshift  
C) RDS  
D) DynamoDB  

53. You want to enable MFA-protected API access for your users. Which service supports this?  
A) IAM  
B) KMS  
C) Secrets Manager  
D) CloudTrail  

54. Your company wants to deliver content globally with caching and SSL termination. Which service is most appropriate?  
A) CloudFront  
B) ELB  
C) S3  
D) Route 53  

55. You need a fully managed, high-performance, and scalable key-value NoSQL database. Which service is best?  
A) DynamoDB  
B) RDS  
C) Aurora  
D) S3  

56. You want to track AWS spending for each department in your organization. Which service combination should you use?  
A) Cost Explorer + AWS Organizations  
B) CloudWatch  
C) Trusted Advisor  
D) Billing Dashboard  

57. Your team wants to host a static website with versioned content. Which service is appropriate?  
A) S3  
B) EC2  
C) CloudFront  
D) Route 53  

58. You need to migrate an on-premises database to AWS with minimal downtime. Which service should you use?  
A) Database Migration Service (DMS)  
B) RDS  
C) S3  
D) EC2  

59. You want to run a machine learning model without managing servers. Which service is appropriate?  
A) SageMaker Endpoint  
B) Lambda  
C) ECS  
D) Fargate  

60. Your mobile app needs secure user authentication with social logins. Which service should you implement?  
A) Cognito  
B) IAM  
C) KMS  
D) SSO  

61. You want to archive compliance data with long-term retention and write-once-read-many protection. Which service is best?  
A) S3 Glacier Vault Lock  
B) S3 Standard  
C) EBS  
D) DynamoDB  

62. Your application requires asynchronous processing for image uploads. Which combination is best?  
A) S3 + SQS + Lambda  
B) S3 + EC2  
C) DynamoDB + Lambda  
D) CloudFront + S3  

63. You need to centrally manage and rotate database credentials automatically. Which service should you use?  
A) Secrets Manager  
B) KMS  
C) IAM  
D) CloudTrail  

64. Your organization wants a managed service for scalable in-memory caching for a web application. Which service is appropriate?  
A) ElastiCache  
B) DynamoDB  
C) RDS  
D) S3  

65. You want to deploy an application that automatically scales based on traffic and uses multiple Availability Zones for high availability. Which approach is best?  
A) EC2 + Auto Scaling + ELB  
B) Lambda + S3  
C) ECS + CloudFront  
D) RDS + DynamoDB  

