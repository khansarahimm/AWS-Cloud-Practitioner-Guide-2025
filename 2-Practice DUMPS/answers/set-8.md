# AWS Practice Questions – Set 8 (Answers & Explanations)

---

### 71. Which AWS service is used for big data processing using Hadoop and Spark?

**Correct Answer:** **Amazon EMR**

**Explanation:**
Amazon EMR (Elastic MapReduce) provides a managed Hadoop and Spark platform for big data processing. It allows analyzing large datasets with distributed computing. EMR automatically provisions EC2 instances, scales clusters, and integrates with S3 for storage. This service reduces the operational overhead of managing big data infrastructure.

* **Wrong options:**

  * **Redshift:** Data warehouse, not distributed processing.
  * **Athena:** Serverless SQL queries, not Hadoop/Spark jobs.
  * **RDS:** Relational database, not big data processing.

[Documentation: Amazon EMR](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-what-is-emr.html)

---

### 72. Which service is used to send email from AWS applications?

**Correct Answer:** **Amazon SES**

**Explanation:**
Amazon SES (Simple Email Service) is a scalable email service for sending transactional, marketing, or notification emails. It integrates with other AWS services like Lambda and S3, supports DKIM and SPF for authentication, and provides analytics for email delivery. SES eliminates the need to manage email servers.

* **Wrong options:**

  * **SNS:** Publishes notifications, not full email service.
  * **SQS:** Queues messages, not email.
  * **CloudWatch:** Monitors metrics and logs, not email delivery.

[Documentation: Amazon SES](https://docs.aws.amazon.com/ses/)

---

### 73. Which AWS service allows serverless SQL querying of S3 data?

**Correct Answer:** **Amazon Athena**

**Explanation:**
Amazon Athena enables querying structured and unstructured data stored in S3 using SQL without provisioning servers. It integrates with AWS Glue for schema management and charges based on the amount of data scanned. Athena is ideal for ad hoc analytics and quick data exploration.

* **Wrong options:**

  * **Redshift:** Requires data warehouse setup.
  * **RDS:** Relational database, not serverless querying.
  * **EMR:** Distributed processing, not serverless SQL.

[Documentation: Amazon Athena](https://docs.aws.amazon.com/athena/)

---

### 74. Which service helps distribute incoming traffic across multiple targets?

**Correct Answer:** **Elastic Load Balancing (ELB)**

**Explanation:**
ELB automatically distributes incoming application traffic across EC2 instances, containers, and IP addresses in multiple Availability Zones. It improves fault tolerance, scalability, and application availability. ELB supports Application Load Balancer, Network Load Balancer, and Gateway Load Balancer for different use cases.

* **Wrong options:**

  * **Route 53:** DNS routing, not load balancing.
  * **CloudFront:** Content distribution, not local traffic balancing.
  * **VPC:** Network isolation, not traffic distribution.

[Documentation: Elastic Load Balancing](https://docs.aws.amazon.com/elasticloadbalancing/)

---

### 75. Which AWS service is used to manage secrets and credentials securely?

**Correct Answer:** **AWS Secrets Manager**

**Explanation:**
Secrets Manager allows storing, rotating, and managing secrets such as API keys, passwords, and database credentials. It integrates with RDS, Redshift, and other services for secure secret injection. Automated rotation reduces the risk of exposure and improves security compliance.

* **Wrong options:**

  * **IAM:** Identity and access management, not secret storage.
  * **KMS:** Key management for encryption, not credential storage.
  * **S3:** Storage service, not secrets management.

[Documentation: AWS Secrets Manager](https://docs.aws.amazon.com/secretsmanager/)

---

### 76. Which AWS service provides a fully managed NoSQL database?

**Correct Answer:** **Amazon DynamoDB**

**Explanation:**
DynamoDB is a fully managed NoSQL database offering fast and predictable performance with seamless scalability. It supports key-value and document data models, provides built-in security, backup, and replication. DynamoDB integrates with Lambda for serverless applications and reduces the operational burden of database management.

* **Wrong options:**

  * **RDS:** Relational database, not NoSQL.
  * **Redshift:** Data warehouse, not NoSQL.
  * **Aurora:** Relational database engine, not NoSQL.

[Documentation: Amazon DynamoDB](https://docs.aws.amazon.com/amazondynamodb/)

---

### 77. Which AWS service is used to provide managed GraphQL APIs?

**Correct Answer:** **AWS AppSync**

**Explanation:**
AppSync allows creating scalable GraphQL APIs with real-time data synchronization. It integrates with DynamoDB, Lambda, and other AWS services. AppSync automatically scales, provides offline data access, and secures APIs with IAM, Cognito, and API keys. It simplifies building modern, data-driven applications.

* **Wrong options:**

  * **API Gateway:** RESTful APIs, not managed GraphQL.
  * **Lambda:** Executes functions, does not provide GraphQL API management.
  * **RDS:** Database, not API management.

[Documentation: AWS AppSync](https://docs.aws.amazon.com/appsync/)

---

### 78. Which AWS service is used to monitor user activity and API usage?

**Correct Answer:** **AWS CloudTrail**

**Explanation:**
CloudTrail records AWS API calls and user activity across accounts. It provides logs for auditing, compliance, and troubleshooting security incidents. CloudTrail integrates with CloudWatch for monitoring and alerts. It is essential for governance and operational transparency in AWS environments.

* **Wrong options:**

  * **CloudWatch:** Monitors metrics and logs, not API usage.
  * **Config:** Monitors resource configurations, not API calls.
  * **Trusted Advisor:** Provides recommendations, not activity monitoring.

[Documentation: AWS CloudTrail](https://docs.aws.amazon.com/cloudtrail/)

---

### 79. Which AWS service provides distributed caching to improve performance?

**Correct Answer:** **Amazon ElastiCache**

**Explanation:**
ElastiCache offers in-memory caching using Redis or Memcached to accelerate application performance. It reduces database load, provides high availability, and supports replication and automatic failover. Being fully managed, ElastiCache simplifies setup and scaling for fast and reliable caching.

* **Wrong options:**

  * **S3:** Object storage, not caching.
  * **DynamoDB:** NoSQL database, not in-memory cache.
  * **RDS:** Relational database, not caching.

[Documentation: Amazon ElastiCache](https://docs.aws.amazon.com/AmazonElastiCache/)

---

### 80. Which service provides a global content delivery network for low-latency access?

**Correct Answer:** **Amazon CloudFront**

**Explanation:**
CloudFront caches content at edge locations globally to reduce latency and improve performance. It integrates with S3, Lambda\@Edge, and WAF for security. CloudFront is ideal for delivering websites, videos, APIs, and static content to users worldwide.

* **Wrong options:**

  * **S3:** Storage, not global content distribution.
  * **Route 53:** DNS routing, not a CDN.
  * **ELB:** Balances traffic, not global caching.

[Documentation: Amazon CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)
