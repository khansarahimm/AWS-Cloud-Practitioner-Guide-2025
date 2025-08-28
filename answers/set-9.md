# AWS Practice Questions – Set 9 (Answers & Explanations)

---

### 81. Which AWS service provides automated backup and restore for databases?

**Correct Answer:** **Amazon RDS**

**Explanation:**
Amazon RDS provides automated backups and snapshots for relational databases. Backups occur daily, and transaction logs allow point-in-time recovery. Multi-AZ deployments ensure high availability and automatic failover. RDS reduces operational overhead by automating backup management and database maintenance.

* **Wrong options:**

  * **DynamoDB:** NoSQL database, requires separate backup configurations.
  * **S3:** Object storage, not a database backup solution.
  * **EC2:** Compute service, not specifically for database backups.

[Documentation: Amazon RDS Backup](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_WorkingWithAutomatedBackups.html)

---

### 82. Which service allows creating, deploying, and managing RESTful APIs?

**Correct Answer:** **Amazon API Gateway**

**Explanation:**
API Gateway enables building and managing RESTful APIs at scale. It handles request routing, throttling, authentication, and monitoring. Integrating with Lambda or backend services, it allows serverless applications to expose APIs securely and reliably. API Gateway also supports caching to improve performance.

* **Wrong options:**

  * **AppSync:** Manages GraphQL APIs, not REST.
  * **Lambda:** Executes backend code, not API management.
  * **CloudFront:** Content delivery, not API management.

[Documentation: Amazon API Gateway](https://docs.aws.amazon.com/apigateway/)

---

### 83. Which AWS service provides centralized identity management for multiple accounts?

**Correct Answer:** **AWS IAM & AWS Organizations**

**Explanation:**
AWS Organizations helps manage multiple accounts under a single umbrella. IAM provides user, group, and role management within each account. Together, they enable centralized access control, policy enforcement, and governance. Organizations simplifies billing, compliance, and permission management across accounts.

* **Wrong options:**

  * **Cognito:** User authentication for apps, not account management.
  * **KMS:** Key management, unrelated to identity.
  * **CloudTrail:** Logging API calls, not identity management.

[Documentation: AWS Organizations](https://docs.aws.amazon.com/organizations/)

---

### 84. Which service allows you to encrypt data at rest and in transit?

**Correct Answer:** **AWS KMS + SSL/TLS**

**Explanation:**
AWS KMS provides encryption keys to secure data at rest across services like S3, RDS, and EBS. SSL/TLS ensures encryption during data transmission over networks. Using KMS-managed keys with proper TLS certificates ensures end-to-end encryption, safeguarding sensitive information.

* **Wrong options:**

  * **IAM:** Identity and access, not encryption.
  * **WAF:** Web security, not data encryption.
  * **CloudTrail:** Logging activity, not encryption.

[Documentation: AWS KMS](https://docs.aws.amazon.com/kms/)

---

### 85. Which AWS service enables monitoring of resource configuration changes?

**Correct Answer:** **AWS Config**

**Explanation:**
AWS Config continuously tracks resource configuration changes and evaluates compliance against defined rules. It maintains a historical record of configurations, making auditing and troubleshooting easier. Config can trigger alerts and integrate with Lambda for automated remediation of non-compliant resources.

* **Wrong options:**

  * **CloudWatch:** Monitors metrics and logs, not configuration changes.
  * **CloudTrail:** Logs API calls, not resource state changes.
  * **Trusted Advisor:** Provides best-practice recommendations, not monitoring.

[Documentation: AWS Config](https://docs.aws.amazon.com/config/)

---

### 86. Which AWS service is used to accelerate content delivery globally?

**Correct Answer:** **Amazon CloudFront**

**Explanation:**
CloudFront caches content at edge locations around the world, reducing latency for users. It integrates with S3, Lambda\@Edge, and WAF for performance and security. CloudFront supports static and dynamic content delivery, making applications faster and improving user experience globally.

* **Wrong options:**

  * **S3:** Object storage, not global delivery.
  * **ELB:** Distributes traffic regionally, not globally.
  * **Route 53:** DNS routing, not caching content.

[Documentation: Amazon CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)

---

### 87. Which service allows running serverless code triggered by events?

**Correct Answer:** **AWS Lambda**

**Explanation:**
Lambda runs code without provisioning or managing servers. It can be triggered by S3 uploads, DynamoDB streams, API Gateway requests, or custom events. Lambda scales automatically based on event volume and charges only for execution time. It simplifies building event-driven and serverless applications.

* **Wrong options:**

  * **EC2:** Requires manual server management.
  * **Fargate:** Runs containers, not individual functions.
  * **Elastic Beanstalk:** Application deployment platform, not serverless function execution.

[Documentation: AWS Lambda](https://docs.aws.amazon.com/lambda/)

---

### 88. Which AWS service helps protect against DDoS attacks?

**Correct Answer:** **AWS Shield**

**Explanation:**
AWS Shield provides managed DDoS protection for AWS applications. Shield Standard automatically protects against common attacks, while Shield Advanced provides enhanced detection, mitigation, and cost protection. It integrates with CloudFront and ELB to maintain availability during volumetric attacks.

* **Wrong options:**

  * **WAF:** Protects against web exploits, not DDoS specifically.
  * **IAM:** Manages access, not attack protection.
  * **CloudTrail:** Logs activity, not protection.

[Documentation: AWS Shield](https://docs.aws.amazon.com/waf/)

---

### 89. Which AWS service provides managed in-memory caching for fast performance?

**Correct Answer:** **Amazon ElastiCache**

**Explanation:**
ElastiCache supports Redis and Memcached for in-memory caching. It reduces database load, provides low-latency access to frequently used data, and supports replication and automatic failover. Being fully managed, it eliminates the operational overhead of setting up and maintaining caching solutions.

* **Wrong options:**

  * **S3:** Object storage, not in-memory cache.
  * **DynamoDB:** NoSQL database, not caching.
  * **RDS:** Relational database, not in-memory cache.

[Documentation: Amazon ElastiCache](https://docs.aws.amazon.com/AmazonElastiCache/)

---

### 90. Which AWS service allows creating secure APIs with throttling and authentication?

**Correct Answer:** **Amazon API Gateway**

**Explanation:**
API Gateway allows creating, deploying, and managing REST and WebSocket APIs securely. It supports authentication via IAM, Cognito, and API keys. Throttling and caching improve performance and protect backend services. API Gateway integrates with Lambda, DynamoDB, and other AWS services for serverless applications.

* **Wrong options:**

  * **AppSync:** GraphQL APIs, not REST.
  * **Lambda:** Runs functions but does not manage APIs.
  * **CloudFront:** Content delivery, not API management.

[Documentation: Amazon API Gateway](https://docs.aws.amazon.com/apigateway/)
