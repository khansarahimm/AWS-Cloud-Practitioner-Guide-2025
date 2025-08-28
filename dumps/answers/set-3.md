
# AWS Practice Questions – Set 3 (Answers & Explanations)

---

### 21. Which AWS service provides a managed NoSQL database with single-digit millisecond latency?

**Correct Answer:** **Amazon DynamoDB**

**Explanation:**
Amazon DynamoDB is a fully managed NoSQL database service offering fast and predictable performance at any scale. It supports key-value and document data models, ideal for real-time applications such as gaming, IoT, and mobile apps. DynamoDB automatically scales throughput and storage to meet demand, eliminating the need for manual provisioning.

* **Wrong options:**

  * **Amazon RDS:** Relational database, not NoSQL.
  * **Amazon Redshift:** Data warehouse for analytics, not low-latency transactions.
  * **Amazon S3:** Object storage, not a database.

[Documentation: Amazon DynamoDB](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html)

---

### 22. Which service enables deployment of web applications without provisioning servers?

**Correct Answer:** **AWS Elastic Beanstalk**

**Explanation:**
Elastic Beanstalk is a Platform as a Service (PaaS) that allows developers to deploy applications without managing infrastructure. It automatically handles scaling, load balancing, patching, and monitoring. You simply upload your code, and Elastic Beanstalk provisions the required resources, reducing operational overhead.

* **Wrong options:**

  * **Amazon EC2:** Requires manual server management.
  * **AWS Lambda:** Event-driven serverless functions, not full app deployment.
  * **Amazon S3:** Storage, not an application hosting platform.

[Documentation: AWS Elastic Beanstalk](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/Welcome.html)

---

### 23. Which AWS service provides scalable block storage for EC2 instances?

**Correct Answer:** **Amazon EBS (Elastic Block Store)**

**Explanation:**
Amazon EBS provides persistent block-level storage for EC2 instances. It is highly available and durable, supporting snapshots for backup. EBS is ideal for applications requiring frequent read/write operations and low-latency storage directly attached to compute resources.

* **Wrong options:**

  * **Amazon S3:** Object storage, not block-level storage.
  * **Amazon RDS:** Database service, not raw storage for EC2.
  * **Amazon EFS:** Managed file storage, not block storage.

[Documentation: Amazon EBS](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSVolumes.html)

---

### 24. Which service enables you to run relational databases in a fully managed environment?

**Correct Answer:** **Amazon RDS**

**Explanation:**
Amazon RDS automates database provisioning, patching, backup, and scaling. It supports multiple engines like MySQL, PostgreSQL, SQL Server, and Oracle. With RDS, developers can focus on building applications instead of managing database infrastructure, ensuring high availability and reliability.

* **Wrong options:**

  * **Amazon DynamoDB:** NoSQL database, not relational.
  * **Amazon Aurora:** Part of RDS, but Aurora is a specific high-performance engine.
  * **Amazon Redshift:** Data warehouse, optimized for analytics, not transactional databases.

[Documentation: Amazon RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)

---

### 25. Which service provides a content delivery network for faster global content delivery?

**Correct Answer:** **Amazon CloudFront**

**Explanation:**
CloudFront is a CDN that caches content at edge locations worldwide, reducing latency and improving user experience. It works with S3, Lambda\@Edge, and other AWS services. CloudFront also supports security features like SSL/TLS encryption and integration with AWS WAF for web protection.

* **Wrong options:**

  * **Amazon S3:** Storage service, not a CDN.
  * **Elastic Load Balancing:** Distributes traffic across instances but not globally cached content.
  * **Amazon Route 53:** DNS routing, not content delivery.

[Documentation: Amazon CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)

---

### 26. Which AWS service enables monitoring of applications and resources in real-time?

**Correct Answer:** **Amazon CloudWatch**

**Explanation:**
CloudWatch collects metrics, logs, and events from AWS resources and applications. It allows you to set alarms and automate responses, such as scaling EC2 instances or sending notifications. CloudWatch provides operational visibility and is critical for performance monitoring and troubleshooting.

* **Wrong options:**

  * **AWS Config:** Monitors configuration compliance, not performance.
  * **CloudTrail:** Tracks API activity, not metrics.
  * **AWS Trusted Advisor:** Provides best-practice recommendations, not real-time monitoring.

[Documentation: Amazon CloudWatch](https://docs.aws.amazon.com/cloudwatch/)

---

### 27. Which service continuously monitors AWS resource configurations for compliance?

**Correct Answer:** **AWS Config**

**Explanation:**
AWS Config tracks AWS resource configurations, evaluates them against rules, and records changes over time. It enables compliance audits, governance, and operational troubleshooting. Config snapshots provide a complete historical view of resource configuration.

* **Wrong options:**

  * **CloudWatch:** Focused on metrics and logs, not configuration compliance.
  * **CloudTrail:** Records API calls, not resource compliance.
  * **Trusted Advisor:** Provides recommendations, not continuous evaluation.

[Documentation: AWS Config](https://docs.aws.amazon.com/config/)

---

### 28. Which service provides a managed in-memory caching system for applications?

**Correct Answer:** **Amazon ElastiCache**

**Explanation:**
ElastiCache supports Redis and Memcached for caching frequently accessed data, reducing latency and improving performance. It is fully managed, scalable, and integrates with applications for faster response times. High availability is supported with replication and automatic failover.

* **Wrong options:**

  * **S3:** Object storage, not in-memory cache.
  * **DynamoDB:** NoSQL database, not caching.
  * **RDS:** Relational database, not designed for caching.

[Documentation: Amazon ElastiCache](https://docs.aws.amazon.com/AmazonElastiCache/)

---

### 29. Which AWS service provides protection against DDoS attacks?

**Correct Answer:** **AWS Shield**

**Explanation:**
AWS Shield protects AWS applications from Distributed Denial of Service (DDoS) attacks. Shield Standard provides automatic protection against common attacks, while Shield Advanced offers enhanced detection, mitigation, and reporting. It helps maintain application availability during attacks.

* **Wrong options:**

  * **AWS WAF:** Protects against web exploits, not DDoS.
  * **IAM:** Identity management, unrelated to network protection.
  * **CloudTrail:** Logging service, not DDoS mitigation.

[Documentation: AWS Shield](https://docs.aws.amazon.com/waf/)

---

### 30. Which service allows you to provision AWS resources using templates as code?

**Correct Answer:** **AWS CloudFormation**

**Explanation:**
CloudFormation allows you to define and provision AWS infrastructure using YAML or JSON templates. This ensures repeatable, consistent deployments and supports version control of infrastructure. CloudFormation automates resource creation, updates, and deletion without manual intervention.

* **Wrong options:**

  * **AWS OpsWorks:** Configuration management, not general infrastructure provisioning.
  * **Elastic Beanstalk:** Simplifies app deployment but not full infrastructure automation.
  * **AWS Config:** Monitors resources but does not create them.

[Documentation: AWS CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)

