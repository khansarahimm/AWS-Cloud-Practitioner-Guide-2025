# AWS Practice Questions – Set 4 (Answers & Explanations)

---

### 31. Which AWS service allows you to run code in response to events without provisioning servers?

**Correct Answer:** **AWS Lambda**

**Explanation:**
AWS Lambda is a serverless compute service that executes code in response to events such as S3 uploads, API Gateway calls, or DynamoDB changes. You don’t need to manage servers, and it automatically scales with workload. Lambda charges only for execution time, making it cost-efficient. It integrates with many AWS services for real-time processing and automation.

* **Wrong options:**

  * **Amazon EC2:** Requires server management.
  * **AWS Fargate:** Runs containers, not individual functions.
  * **Amazon RDS:** Database service, not compute.

[Documentation: AWS Lambda](https://docs.aws.amazon.com/lambda/)

---

### 32. Which service provides object storage with high durability and scalability?

**Correct Answer:** **Amazon S3**

**Explanation:**
Amazon S3 offers virtually unlimited object storage with 99.999999999% durability. It is ideal for backups, static website hosting, media storage, and analytics. Multiple storage classes optimize cost depending on access patterns. S3 integrates with other AWS services for data analytics, security, and distribution.

* **Wrong options:**

  * **Amazon EBS:** Block storage for single EC2 instances.
  * **Amazon EFS:** Shared file system, not object storage.
  * **Amazon RDS:** Relational database, not object storage.

[Documentation: Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)

---

### 33. Which AWS service enables you to provision a virtual network in the cloud?

**Correct Answer:** **Amazon VPC**

**Explanation:**
Amazon VPC allows you to create a logically isolated network with control over IP address ranges, subnets, routing tables, and gateways. It ensures secure connectivity between resources, supports VPNs, and allows private/public subnet configuration. VPC is essential for network security and architecture flexibility.

* **Wrong options:**

  * **AWS IAM:** Manages identities, not networks.
  * **Amazon EC2:** Compute, not network isolation.
  * **AWS Organizations:** Manages accounts, not virtual networks.

[Documentation: Amazon VPC](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)

---

### 34. Which service helps automate provisioning of AWS resources using templates?

**Correct Answer:** **AWS CloudFormation**

**Explanation:**
CloudFormation allows defining AWS infrastructure as code using JSON or YAML templates. It automates resource creation, updating, and deletion, ensuring consistent deployments. CloudFormation supports version control and can replicate infrastructure across multiple regions or accounts.

* **Wrong options:**

  * **AWS OpsWorks:** Configuration management with Chef/Puppet.
  * **Elastic Beanstalk:** Simplifies app deployment, not full IaC.
  * **AWS Config:** Monitors configuration, doesn’t provision resources.

[Documentation: AWS CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)

---

### 35. Which service allows you to monitor AWS resources and applications in real-time?

**Correct Answer:** **Amazon CloudWatch**

**Explanation:**
CloudWatch collects metrics, logs, and events from AWS resources and applications. It allows setting alarms for automated actions like scaling or notifications. CloudWatch dashboards provide visibility into performance trends and operational health. It’s critical for troubleshooting and operational excellence.

* **Wrong options:**

  * **AWS Config:** Tracks resource configuration, not performance.
  * **CloudTrail:** Records API calls, not metrics.
  * **Trusted Advisor:** Provides recommendations, not real-time monitoring.

[Documentation: Amazon CloudWatch](https://docs.aws.amazon.com/cloudwatch/)

---

### 36. Which service provides managed in-memory caching for applications?

**Correct Answer:** **Amazon ElastiCache**

**Explanation:**
ElastiCache supports Redis and Memcached, enabling faster data retrieval by caching frequently accessed information. It improves application performance and reduces load on databases. It is fully managed, scalable, and supports high availability with replication and automatic failover.

* **Wrong options:**

  * **S3:** Object storage, not caching.
  * **DynamoDB:** Database, not in-memory caching.
  * **RDS:** Relational database, not caching service.

[Documentation: Amazon ElastiCache](https://docs.aws.amazon.com/AmazonElastiCache/)

---

### 37. Which AWS service provides a fully managed relational database?

**Correct Answer:** **Amazon RDS**

**Explanation:**
RDS automates database tasks such as provisioning, patching, backup, and scaling. It supports engines like MySQL, PostgreSQL, Oracle, and SQL Server. RDS ensures high availability, reliability, and reduces administrative overhead for developers.

* **Wrong options:**

  * **DynamoDB:** NoSQL database, not relational.
  * **Aurora:** High-performance relational engine, still part of RDS.
  * **Redshift:** Data warehouse, not transactional database.

[Documentation: Amazon RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)

---

### 38. Which service protects AWS applications from Distributed Denial of Service (DDoS) attacks?

**Correct Answer:** **AWS Shield**

**Explanation:**
AWS Shield protects applications from DDoS attacks. Shield Standard provides automatic protection against common attacks. Shield Advanced offers enhanced detection, mitigation, and reporting. It helps maintain uptime and application availability during attacks.

* **Wrong options:**

  * **AWS WAF:** Protects against web exploits, not DDoS.
  * **IAM:** Identity management, unrelated to DDoS.
  * **CloudTrail:** Logging service, not protection.

[Documentation: AWS Shield](https://docs.aws.amazon.com/waf/)

---

### 39. Which service provides a Content Delivery Network for global content distribution?

**Correct Answer:** **Amazon CloudFront**

**Explanation:**
CloudFront caches content at edge locations worldwide, improving load times and reducing latency. It integrates with S3, Lambda\@Edge, and AWS WAF for security. CloudFront is ideal for delivering websites, videos, and APIs to users globally.

* **Wrong options:**

  * **S3:** Storage, not global distribution.
  * **Route 53:** DNS service, not a CDN.
  * **Elastic Load Balancing:** Balances traffic locally, not globally.

[Documentation: Amazon CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)

---

### 40. Which service continuously monitors AWS resource configurations for compliance?

**Correct Answer:** **AWS Config**

**Explanation:**
AWS Config records configuration changes, evaluates them against rules, and provides compliance history. It helps identify misconfigurations and ensures governance. Config provides detailed insights for auditing and operational troubleshooting.

* **Wrong options:**

  * **CloudWatch:** Metrics monitoring, not compliance.
  * **CloudTrail:** Tracks API calls, not resource compliance.
  * **Trusted Advisor:** Gives recommendations, not continuous evaluation.

[Documentation: AWS Config](https://docs.aws.amazon.com/config/)

