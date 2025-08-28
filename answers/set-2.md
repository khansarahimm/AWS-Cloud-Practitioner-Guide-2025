# AWS Practice Questions – Set 2 (Answers & Explanations)

---

### 11. Which AWS service helps decouple application components using messaging queues?

**Correct Answer:** **Amazon SQS (Simple Queue Service)**

**Explanation:**
Amazon SQS is a fully managed message queuing service that allows distributed application components to communicate asynchronously. It ensures messages are delivered reliably between producers and consumers. SQS helps improve fault tolerance and scalability because message senders and receivers do not need to interact directly. It also supports Standard queues (high throughput) and FIFO queues (ordered delivery).

* **Wrong options:**

  * **Amazon SNS:** Pub/Sub service, not designed for queue storage.
  * **Amazon Kinesis:** Real-time streaming, not a queue.
  * **AWS Step Functions:** Workflow orchestration, not messaging.

[Documentation: Amazon SQS](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html)

---

### 12. Which AWS service provides serverless compute for running code without provisioning servers?

**Correct Answer:** **AWS Lambda**

**Explanation:**
AWS Lambda allows you to run code in response to events without managing servers. It automatically scales and only charges for compute time used. Lambda integrates with many AWS services and is ideal for microservices, data processing, and real-time event handling. This serverless model eliminates the overhead of EC2 instance management.

* **Wrong options:**

  * **Amazon EC2:** Requires server management.
  * **AWS Fargate:** Runs containers, not individual functions.
  * **Amazon RDS:** Database service, not compute.

[Documentation: AWS Lambda](https://docs.aws.amazon.com/lambda/)

---

### 13. Which service provides object storage with virtually unlimited scalability?

**Correct Answer:** **Amazon S3**

**Explanation:**
Amazon S3 stores and retrieves unlimited amounts of data at any time. It offers durability of 99.999999999% and integrates with many AWS services for analytics, backup, and content delivery. S3 supports multiple storage classes to optimize costs based on access frequency. It is the backbone of storage for AWS.

* **Wrong options:**

  * **Amazon EBS:** Block storage attached to EC2, limited to single instance usage.
  * **Amazon EFS:** Shared file storage, not object storage.
  * **Amazon RDS:** Relational database, unrelated to object storage.

[Documentation: Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)

---

### 14. Which service provides a fully managed relational database?

**Correct Answer:** **Amazon RDS**

**Explanation:**
Amazon RDS is a managed relational database service supporting MySQL, PostgreSQL, Oracle, and SQL Server. It automates backups, patching, scaling, and replication. RDS reduces administrative overhead, allowing developers to focus on applications rather than database management.

* **Wrong options:**

  * **Amazon DynamoDB:** NoSQL database, not relational.
  * **Amazon Redshift:** Data warehouse, not transactional DB.
  * **Amazon Aurora:** Relational, but specifically MySQL/PostgreSQL compatible with higher performance.

[Documentation: Amazon RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)

---

### 15. Which AWS service provides a Content Delivery Network for low-latency delivery?

**Correct Answer:** **Amazon CloudFront**

**Explanation:**
CloudFront is a global CDN that caches content at edge locations worldwide, improving access speed for end users. It integrates with S3, Lambda\@Edge, and other AWS services. CloudFront enhances performance and reduces latency for web applications and media distribution.

* **Wrong options:**

  * **Amazon S3:** Storage, not content delivery optimization.
  * **Amazon Route 53:** DNS service, not CDN.
  * **AWS Elastic Load Balancing:** Balances traffic, not global content delivery.

[Documentation: Amazon CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)

---

### 16. Which service allows you to monitor AWS resources and set alarms?

**Correct Answer:** **Amazon CloudWatch**

**Explanation:**
CloudWatch monitors AWS resources and applications in real-time, collecting metrics and logs. You can create alarms to automatically respond to changes in CPU utilization, memory usage, or application errors. It also integrates with auto-scaling and Lambda for automated responses, providing operational visibility.

* **Wrong options:**

  * **AWS Config:** Tracks resource configuration and compliance, not performance metrics.
  * **CloudTrail:** Tracks API calls, not metrics.
  * **AWS Trusted Advisor:** Gives recommendations, not real-time monitoring.

[Documentation: Amazon CloudWatch](https://docs.aws.amazon.com/cloudwatch/)

---

### 17. Which service helps enforce compliance by continuously evaluating AWS resource configurations?

**Correct Answer:** **AWS Config**

**Explanation:**
AWS Config continuously monitors and records AWS resource configurations. It evaluates these against rules for compliance, helping detect drift or unauthorized changes. Config provides snapshots of resources and a history of changes, making governance and audits easier.

* **Wrong options:**

  * **CloudWatch:** Monitors performance, not compliance.
  * **CloudTrail:** Logs API calls for auditing, not configuration evaluation.
  * **Trusted Advisor:** Provides recommendations, not continuous evaluation.

[Documentation: AWS Config](https://docs.aws.amazon.com/config/)

---

### 18. Which service provides managed in-memory caching for applications?

**Correct Answer:** **Amazon ElastiCache**

**Explanation:**
ElastiCache is a managed service for Redis and Memcached. It caches frequently accessed data to reduce latency and improve performance. It supports high availability and scaling, enabling faster response times for web and mobile applications.

* **Wrong options:**

  * **S3:** Object storage, not caching.
  * **DynamoDB:** Database, not in-memory caching.
  * **RDS:** Relational database, not caching service.

[Documentation: Amazon ElastiCache](https://docs.aws.amazon.com/AmazonElastiCache/)

---

### 19. Which service provides DDoS protection for AWS applications?

**Correct Answer:** **AWS Shield**

**Explanation:**
AWS Shield provides managed protection against Distributed Denial of Service (DDoS) attacks. Shield Standard protects against common attacks automatically, while Shield Advanced offers additional detection and mitigation. This service ensures applications remain available during volumetric attacks.

* **Wrong options:**

  * **AWS WAF:** Protects against web exploits, not DDoS.
  * **IAM:** Identity management, not security protection.
  * **CloudTrail:** Logging service, not defense.

[Documentation: AWS Shield](https://docs.aws.amazon.com/waf/)

---

### 20. Which service allows infrastructure provisioning using code templates?

**Correct Answer:** **AWS CloudFormation**

**Explanation:**
CloudFormation enables Infrastructure as Code (IaC) using JSON or YAML templates. It automates provisioning, scaling, and updating AWS resources consistently across environments. Templates can be version controlled and reused, ensuring repeatable and reliable infrastructure deployments.

* **Wrong options:**

  * **AWS OpsWorks:** Configuration management using Chef/Puppet, not general IaC.
  * **Elastic Beanstalk:** Simplified app deployment, not full infrastructure templating.
  * **AWS Config:** Monitors configuration, does not provision resources.

[Documentation: AWS CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)
