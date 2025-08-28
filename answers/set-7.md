# AWS Practice Questions – Set 7 (Answers & Explanations)

---

### 61. Which AWS service allows you to schedule and automate tasks across AWS resources?

**Correct Answer:** **Amazon EventBridge**

**Explanation:**
EventBridge is a serverless event bus that enables routing events between AWS services, SaaS applications, and custom applications. You can schedule recurring tasks, respond to system events, or integrate applications across accounts. EventBridge provides near real-time processing and simplifies automation of workflows across AWS.

* **Wrong options:**

  * **CloudWatch:** Primarily monitors metrics and logs; can trigger events but not full event routing.
  * **Step Functions:** Orchestrates workflows, not event scheduling.
  * **Lambda:** Executes code, but doesn’t schedule or route events natively.

[Documentation: Amazon EventBridge](https://docs.aws.amazon.com/eventbridge/)

---

### 62. Which AWS service provides managed relational database with automatic multi-AZ replication?

**Correct Answer:** **Amazon RDS**

**Explanation:**
Amazon RDS supports high availability through Multi-AZ deployments, where it automatically replicates data to a standby instance in a different Availability Zone. This ensures failover capability, durability, and minimal downtime. RDS automates backups, patching, and maintenance tasks, reducing administrative overhead.

* **Wrong options:**

  * **DynamoDB:** NoSQL database, not relational.
  * **Redshift:** Data warehouse, optimized for analytics, not transactional databases.
  * **Aurora:** A specialized high-performance RDS engine, not a separate generic service.

[Documentation: Amazon RDS Multi-AZ](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Concepts.MultiAZ.html)

---

### 63. Which AWS service allows secure management of encryption keys?

**Correct Answer:** **AWS KMS (Key Management Service)**

**Explanation:**
AWS KMS enables centralized creation, management, and control of cryptographic keys used to encrypt data. It integrates with many AWS services like S3, EBS, and RDS. KMS supports automatic key rotation, IAM policies for access control, and auditing via CloudTrail, ensuring secure data encryption.

* **Wrong options:**

  * **IAM:** Identity management, not key management.
  * **Shield:** DDoS protection, unrelated to encryption.
  * **WAF:** Protects web applications, not encryption.

[Documentation: AWS KMS](https://docs.aws.amazon.com/kms/)

---

### 64. Which service enables analyzing logs and metrics across AWS resources?

**Correct Answer:** **Amazon CloudWatch**

**Explanation:**
CloudWatch collects logs, metrics, and events from AWS resources and applications. It enables creating dashboards, setting alarms, and automating responses. CloudWatch Logs Insights allows querying log data for operational insights. It provides a central platform for monitoring performance and troubleshooting issues in real-time.

* **Wrong options:**

  * **AWS Config:** Monitors resource configuration, not performance metrics.
  * **CloudTrail:** Records API calls, not logs/metrics analytics.
  * **Trusted Advisor:** Provides recommendations, not log analysis.

[Documentation: Amazon CloudWatch](https://docs.aws.amazon.com/cloudwatch/)

---

### 65. Which AWS service is used for queuing messages between distributed application components?

**Correct Answer:** **Amazon SQS**

**Explanation:**
Amazon SQS decouples application components by storing messages in a queue until they are processed by consumers. It supports Standard queues for high throughput and FIFO queues for ordered message delivery. SQS ensures reliability, scalability, and fault tolerance in distributed systems.

* **Wrong options:**

  * **SNS:** Publishes messages to multiple subscribers, not a queue.
  * **Kinesis:** Real-time streaming service, not message queuing.
  * **Step Functions:** Orchestration, not messaging.

[Documentation: Amazon SQS](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html)

---

### 66. Which AWS service allows serverless running of containerized workloads?

**Correct Answer:** **AWS Fargate**

**Explanation:**
AWS Fargate runs containers without requiring EC2 instance management. It integrates with ECS and EKS, handling scaling, patching, and provisioning automatically. Fargate simplifies container deployments, supports secure and isolated workloads, and reduces operational overhead.

* **Wrong options:**

  * **Lambda:** Executes individual functions, not full container workloads.
  * **EC2:** Requires manual provisioning and management of containers.
  * **Elastic Beanstalk:** Simplifies app deployment but doesn’t focus on container orchestration.

[Documentation: AWS Fargate](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/fargate.html)

---

### 67. Which AWS service helps protect applications against common web exploits?

**Correct Answer:** **AWS WAF**

**Explanation:**
AWS WAF (Web Application Firewall) protects web applications from threats like SQL injection and cross-site scripting (XSS). You can configure rules based on IP addresses, HTTP headers, or patterns. WAF integrates with CloudFront and Application Load Balancer for comprehensive protection.

* **Wrong options:**

  * **Shield:** Protects against DDoS attacks, not web exploits.
  * **IAM:** Manages identities and access, not security rules.
  * **CloudTrail:** Logs API activity, not active threat protection.

[Documentation: AWS WAF](https://docs.aws.amazon.com/waf/)

---

### 68. Which AWS service provides real-time analytics on streaming data?

**Correct Answer:** **Amazon Kinesis**

**Explanation:**
Amazon Kinesis collects and processes streaming data in real time. It allows applications to ingest data from multiple sources, analyze it, and respond immediately. Kinesis can integrate with Lambda, S3, and Redshift for processing, storage, and analytics of streaming data at scale.

* **Wrong options:**

  * **SQS:** Queues messages, not real-time analytics.
  * **Athena:** Query service for stored data, not streaming.
  * **Redshift:** Data warehouse, optimized for batch analytics.

[Documentation: Amazon Kinesis](https://docs.aws.amazon.com/streams/latest/dev/introduction.html)

---

### 69. Which AWS service provides object storage with versioning and lifecycle management?

**Correct Answer:** **Amazon S3**

**Explanation:**
Amazon S3 allows storing objects with versioning enabled to protect against accidental deletion or overwrites. Lifecycle rules automate moving objects to cheaper storage classes like Glacier or deletion after a period. It integrates with analytics, CloudFront, and Lambda for scalable data management.

* **Wrong options:**

  * **EBS:** Block storage, no versioning or lifecycle.
  * **EFS:** File storage, not object lifecycle management.
  * **RDS:** Database service, unrelated to object versioning.

[Documentation: Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Versioning.html)

---

### 70. Which AWS service allows defining infrastructure as code using JSON or YAML templates?

**Correct Answer:** **AWS CloudFormation**

**Explanation:**
CloudFormation automates provisioning and management of AWS resources using JSON or YAML templates. It allows repeatable, consistent deployments across environments. Templates can be version controlled, reused, and updated with minimal risk, reducing manual errors and improving operational efficiency.

* **Wrong options:**

  * **OpsWorks:** Configuration management using Chef/Puppet, not full IaC.
  * **Elastic Beanstalk:** Simplifies deployment but not full infrastructure templating.
  * **Config:** Monitors resources, does not provision them.

[Documentation: AWS CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)

