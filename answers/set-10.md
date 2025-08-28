# AWS Practice Questions – Set 10 (Answers & Explanations)

---

### 91. Which AWS service provides serverless event-driven compute?

**Correct Answer:** **AWS Lambda**

**Explanation:**
Lambda allows running code in response to events without managing servers. It scales automatically with event volume and integrates with services like S3, DynamoDB, and API Gateway. Charges are based on execution time and resource consumption. Lambda simplifies building serverless, event-driven architectures.

* **Wrong options:**

  * **EC2:** Requires manual server provisioning.
  * **Fargate:** Runs containers, not individual functions.
  * **Elastic Beanstalk:** Platform for application deployment, not serverless execution.

[Documentation: AWS Lambda](https://docs.aws.amazon.com/lambda/)

---

### 92. Which service is used for managed, scalable relational databases?

**Correct Answer:** **Amazon RDS**

**Explanation:**
Amazon RDS provides fully managed relational databases such as MySQL, PostgreSQL, and Aurora. It supports Multi-AZ deployments for high availability, automated backups, and patching. RDS reduces administrative overhead and allows developers to focus on application logic instead of database management.

* **Wrong options:**

  * **DynamoDB:** NoSQL database.
  * **Redshift:** Data warehouse, not transactional database.
  * **S3:** Object storage, not a database service.

[Documentation: Amazon RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)

---

### 93. Which AWS service provides scalable object storage?

**Correct Answer:** **Amazon S3**

**Explanation:**
S3 provides durable, highly available object storage for any type of data. Supports versioning, lifecycle policies, and encryption. S3 integrates with CloudFront for content delivery and Lambda for event-driven processing. Its scalability and durability make it suitable for backups, data lakes, and static website hosting.

* **Wrong options:**

  * **EBS:** Block storage for EC2, not object storage.
  * **EFS:** File system storage, not object storage.
  * **Glacier:** Long-term archival storage, not primary object storage.

[Documentation: Amazon S3](https://docs.aws.amazon.com/s3/)

---

### 94. Which AWS service is used for managed NoSQL databases?

**Correct Answer:** **Amazon DynamoDB**

**Explanation:**
DynamoDB is a fully managed NoSQL database that offers low-latency performance and automatic scaling. Supports key-value and document data models. Integrates with Lambda and other AWS services for serverless architectures. DynamoDB reduces operational complexity by automating hardware provisioning, patching, and replication.

* **Wrong options:**

  * **RDS:** Relational database, not NoSQL.
  * **Redshift:** Data warehouse for analytics.
  * **Aurora:** Managed relational database engine.

[Documentation: Amazon DynamoDB](https://docs.aws.amazon.com/amazondynamodb/)

---

### 95. Which AWS service provides a global content delivery network?

**Correct Answer:** **Amazon CloudFront**

**Explanation:**
CloudFront caches content at edge locations worldwide for low-latency delivery. Integrates with S3, WAF, and Lambda\@Edge. Supports static and dynamic content, streaming, and secure delivery with SSL/TLS. CloudFront improves website performance and reduces latency for global users.

* **Wrong options:**

  * **Route 53:** DNS service, not CDN.
  * **ELB:** Distributes traffic regionally, not globally.
  * **S3:** Storage, not content delivery.

[Documentation: Amazon CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)

---

### 96. Which AWS service allows orchestration of multiple services into workflows?

**Correct Answer:** **AWS Step Functions**

**Explanation:**
Step Functions orchestrate AWS services into workflows using state machines. Supports error handling, retries, and sequential or parallel execution. Integrates with Lambda, SQS, and other services. Simplifies complex process automation while providing monitoring and visualization of execution steps.

* **Wrong options:**

  * **Lambda:** Executes single functions, not workflows.
  * **CloudFormation:** Infrastructure provisioning, not orchestration.
  * **SQS:** Message queuing, not workflow orchestration.

[Documentation: AWS Step Functions](https://docs.aws.amazon.com/step-functions/)

---

### 97. Which service is used for real-time streaming data analytics?

**Correct Answer:** **Amazon Kinesis**

**Explanation:**
Kinesis collects, processes, and analyzes streaming data in real time. Supports ingestion from multiple sources and integration with Lambda, S3, and Redshift. Kinesis enables instant insights from data streams, such as logs, metrics, and IoT telemetry. Ideal for applications requiring low-latency analytics.

* **Wrong options:**

  * **SQS:** Message queuing, not streaming analytics.
  * **Athena:** Queries stored data, not streaming.
  * **Redshift:** Data warehouse for batch analytics.

[Documentation: Amazon Kinesis](https://docs.aws.amazon.com/streams/latest/dev/introduction.html)

---

### 98. Which AWS service allows managing user identities for applications?

**Correct Answer:** **Amazon Cognito**

**Explanation:**
Cognito provides user sign-up, sign-in, and access control for web and mobile applications. Supports social identity providers, SAML federation, and multi-factor authentication. Integrates with API Gateway and Lambda for secure access to AWS resources. Cognito reduces complexity of identity management for developers.

* **Wrong options:**

  * **IAM:** Manages AWS resource access, not application users.
  * **Secrets Manager:** Stores secrets, not identity management.
  * **KMS:** Key management, not user identities.

[Documentation: Amazon Cognito](https://docs.aws.amazon.com/cognito/)

---

### 99. Which AWS service provides automated auditing of AWS account activity?

**Correct Answer:** **AWS CloudTrail**

**Explanation:**
CloudTrail records API calls and user activity across AWS accounts. Provides audit logs for compliance, security monitoring, and troubleshooting. Logs can be sent to S3 or CloudWatch for analysis. CloudTrail ensures visibility into AWS resource usage and changes over time.

* **Wrong options:**

  * **Config:** Monitors resource configurations, not API calls.
  * **CloudWatch:** Monitors metrics/logs, not auditing.
  * **Trusted Advisor:** Provides best-practice checks, not detailed logging.

[Documentation: AWS CloudTrail](https://docs.aws.amazon.com/cloudtrail/)

---

### 100. Which AWS service provides in-memory caching for faster data access?

**Correct Answer:** **Amazon ElastiCache**

**Explanation:**
ElastiCache offers Redis or Memcached in-memory caching to improve application performance. Reduces database load, supports replication and automatic failover, and ensures low-latency access to frequently accessed data. Fully managed, eliminating operational overhead for setup and maintenance.

* **Wrong options:**

  * **S3:** Storage, not cache.
  * **DynamoDB:** Database, not caching.
  * **RDS:** Relational database, not in-memory caching.

[Documentation: Amazon ElastiCache](https://docs.aws.amazon.com/AmazonElastiCache/)
