# AWS Practice Questions – Set 5 (Answers & Explanations)

---

### 41. Which AWS service is used for real-time data streaming?

**Correct Answer:** **Amazon Kinesis**

**Explanation:**
Amazon Kinesis enables the collection, processing, and analysis of real-time streaming data. It allows applications to ingest large amounts of data from sources like IoT devices, logs, or clickstreams, and process them in real-time. Kinesis integrates with Lambda, S3, and Redshift for downstream analytics. It provides low-latency processing and high scalability.

* **Wrong options:**

  * **SQS:** Message queuing, not streaming.
  * **SNS:** Pub/Sub notifications, not real-time streams.
  * **EMR:** Batch processing for big data, not real-time ingestion.

[Documentation: Amazon Kinesis](https://docs.aws.amazon.com/streams/latest/dev/introduction.html)

---

### 42. Which AWS service provides a fully managed data warehouse for analytics?

**Correct Answer:** **Amazon Redshift**

**Explanation:**
Amazon Redshift is a fully managed data warehouse that allows querying structured and semi-structured data using SQL. It supports petabyte-scale storage, high performance, and integrates with BI tools for analytics and reporting. Redshift is designed for OLAP workloads, making it suitable for business intelligence and complex queries.

* **Wrong options:**

  * **RDS:** Transactional database, not optimized for analytics.
  * **DynamoDB:** NoSQL database, not data warehouse.
  * **Aurora:** Relational database, not analytical storage.

[Documentation: Amazon Redshift](https://docs.aws.amazon.com/redshift/latest/mgmt/welcome.html)

---

### 43. Which service allows you to create isolated networks in the AWS Cloud?

**Correct Answer:** **Amazon VPC**

**Explanation:**
Amazon VPC (Virtual Private Cloud) provides logically isolated networks where you can control IP ranges, subnets, route tables, and gateways. It ensures security and flexibility by allowing private and public subnet configurations, VPN connections, and network ACLs. VPC is foundational for secure cloud architecture.

* **Wrong options:**

  * **IAM:** Manages identities, not networks.
  * **EC2:** Compute service, not network isolation.
  * **AWS Organizations:** Manages accounts, not networks.

[Documentation: Amazon VPC](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)

---

### 44. Which AWS service allows monitoring and setting alarms on resources?

**Correct Answer:** **Amazon CloudWatch**

**Explanation:**
CloudWatch collects metrics, logs, and events from AWS resources and applications. You can create alarms to trigger automated actions like scaling EC2 instances or sending notifications. CloudWatch dashboards provide operational visibility, helping troubleshoot performance issues and maintain system health.

* **Wrong options:**

  * **Config:** Monitors configuration, not metrics.
  * **CloudTrail:** Records API calls, not performance.
  * **Trusted Advisor:** Provides best-practice recommendations, not real-time monitoring.

[Documentation: Amazon CloudWatch](https://docs.aws.amazon.com/cloudwatch/)

---

### 45. Which service provides managed message queuing for decoupled applications?

**Correct Answer:** **Amazon SQS**

**Explanation:**
Amazon SQS (Simple Queue Service) decouples microservices and application components. It stores messages reliably and ensures delivery between producers and consumers. SQS supports Standard queues for high throughput and FIFO queues for ordered delivery, improving fault tolerance and scalability.

* **Wrong options:**

  * **SNS:** Pub/Sub messaging, not queuing.
  * **Kinesis:** Real-time streaming, not queuing.
  * **Step Functions:** Workflow orchestration, not messaging queues.

[Documentation: Amazon SQS](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html)

---

### 46. Which AWS service provides in-memory caching for fast application performance?

**Correct Answer:** **Amazon ElastiCache**

**Explanation:**
ElastiCache supports Redis and Memcached to cache frequently accessed data. It reduces database load, improves response times, and supports high availability with replication and automatic failover. Being fully managed, it eliminates administrative overhead while providing scalable and fast caching solutions.

* **Wrong options:**

  * **S3:** Storage, not caching.
  * **DynamoDB:** NoSQL database, not in-memory cache.
  * **RDS:** Relational database, not caching.

[Documentation: Amazon ElastiCache](https://docs.aws.amazon.com/AmazonElastiCache/)

---

### 47. Which service helps enforce security policies and protect applications from web attacks?

**Correct Answer:** **AWS WAF (Web Application Firewall)**

**Explanation:**
AWS WAF protects web applications from common web exploits like SQL injection and XSS attacks. You can create rules to allow, block, or monitor traffic based on IPs, headers, or patterns. WAF integrates with CloudFront and Application Load Balancer for enhanced protection.

* **Wrong options:**

  * **AWS Shield:** DDoS protection, not specific web exploits.
  * **IAM:** Identity management, not web protection.
  * **CloudTrail:** Logs API activity, not security enforcement.

[Documentation: AWS WAF](https://docs.aws.amazon.com/waf/)

---

### 48. Which service helps automate AWS infrastructure using templates as code?

**Correct Answer:** **AWS CloudFormation**

**Explanation:**
CloudFormation allows defining AWS resources in JSON or YAML templates. It automates provisioning, updates, and deletion of infrastructure. This ensures repeatable, consistent deployments and reduces human error. Templates can be version controlled and reused across accounts and regions.

* **Wrong options:**

  * **OpsWorks:** Configuration management, not full IaC.
  * **Elastic Beanstalk:** Simplifies app deployment, not infrastructure templating.
  * **Config:** Monitors resources, doesn’t provision them.

[Documentation: AWS CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)

---

### 49. Which AWS service is used for serverless event-driven compute?

**Correct Answer:** **AWS Lambda**

**Explanation:**
Lambda executes code in response to events without server management. It scales automatically and charges only for execution time. It integrates with services like S3, DynamoDB, and API Gateway for building event-driven applications, automation, and real-time processing.

* **Wrong options:**

  * **EC2:** Requires server provisioning.
  * **Fargate:** Container-based, not individual function execution.
  * **RDS:** Database service, not compute.

[Documentation: AWS Lambda](https://docs.aws.amazon.com/lambda/)

---

### 50. Which service provides a content delivery network for low-latency global access?

**Correct Answer:** **Amazon CloudFront**

**Explanation:**
CloudFront caches content at edge locations worldwide, improving load times and reducing latency. It works with S3, Lambda\@Edge, and integrates with WAF for security. CloudFront is ideal for delivering websites, videos, APIs, and static content globally.

* **Wrong options:**

  * **S3:** Storage, not a CDN.
  * **Route 53:** DNS service, not a CDN.
  * **Elastic Load Balancing:** Local traffic distribution, not global caching.

[Documentation: Amazon CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)


