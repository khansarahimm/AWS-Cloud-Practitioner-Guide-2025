# AWS Practice Questions – Set 6 (Answers & Explanations)

---

### 51. Which AWS service is used for orchestration of multiple AWS services into workflows?

**Correct Answer:** **AWS Step Functions**

**Explanation:**
AWS Step Functions allow you to coordinate multiple AWS services into serverless workflows. It helps manage tasks, handle errors, and ensure tasks execute in a defined order. Step Functions integrate with Lambda, SQS, SNS, and other services for automation, making it ideal for complex processes that require coordination.

* **Wrong options:**

  * **Lambda:** Executes single functions, not orchestration.
  * **CloudFormation:** Infrastructure provisioning, not workflow orchestration.
  * **SQS:** Messaging service, not workflow management.

[Documentation: AWS Step Functions](https://docs.aws.amazon.com/step-functions/)

---

### 52. Which service provides managed DNS routing for applications?

**Correct Answer:** **Amazon Route 53**

**Explanation:**
Route 53 is a highly available and scalable DNS web service. It routes users to endpoints such as EC2, S3, and Elastic Load Balancers. It also supports health checks, routing policies, and domain registration. Route 53 ensures low-latency access to your applications globally.

* **Wrong options:**

  * **CloudFront:** CDN, not DNS management.
  * **VPC:** Network isolation, not DNS routing.
  * **Elastic Load Balancing:** Distributes traffic but does not provide DNS services.

[Documentation: Amazon Route 53](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html)

---

### 53. Which AWS service is used for automated compliance checks and auditing?

**Correct Answer:** **AWS Config**

**Explanation:**
AWS Config continuously monitors and records configurations of AWS resources. It evaluates resources against predefined rules to ensure compliance. Config provides historical configuration data, enabling audits, troubleshooting, and governance in multi-account environments.

* **Wrong options:**

  * **CloudWatch:** Monitors metrics and logs, not configuration compliance.
  * **CloudTrail:** Tracks API calls for auditing, not automated compliance.
  * **Trusted Advisor:** Provides recommendations, not continuous compliance monitoring.

[Documentation: AWS Config](https://docs.aws.amazon.com/config/)

---

### 54. Which service allows running containerized applications without managing servers?

**Correct Answer:** **AWS Fargate**

**Explanation:**
AWS Fargate is a serverless compute engine for containers. It works with ECS and EKS to run containers without managing EC2 instances. Fargate automatically provisions compute, scales resources, and handles patching, making it easier to deploy and manage containerized workloads.

* **Wrong options:**

  * **Lambda:** Executes code in response to events, not full container management.
  * **EC2:** Requires server management for containers.
  * **Elastic Beanstalk:** Simplified app deployment, not container orchestration.

[Documentation: AWS Fargate](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/fargate.html)

---

### 55. Which service provides object storage with lifecycle policies for cost optimization?

**Correct Answer:** **Amazon S3**

**Explanation:**
Amazon S3 allows storing objects and automatically transitioning them to cheaper storage classes (like S3 Glacier) based on lifecycle policies. It provides durability, scalability, and integrates with analytics, CloudFront, and Lambda. Lifecycle rules help reduce storage costs for infrequently accessed data.

* **Wrong options:**

  * **EBS:** Block storage for EC2, no lifecycle management.
  * **EFS:** File storage, does not provide object lifecycle policies.
  * **RDS:** Database service, not object storage.

[Documentation: Amazon S3 Lifecycle Policies](https://docs.aws.amazon.com/AmazonS3/latest/userguide/object-lifecycle-mgmt.html)

---

### 56. Which AWS service allows analyzing large datasets using SQL without managing servers?

**Correct Answer:** **Amazon Athena**

**Explanation:**
Athena is a serverless query service that allows analyzing data stored in S3 using standard SQL. You pay only for the queries you run, with no infrastructure management. It integrates with AWS Glue for schema management and supports complex analytics without provisioning clusters.

* **Wrong options:**

  * **Redshift:** Requires data warehouse management.
  * **RDS:** Relational database, not for serverless analytics.
  * **EMR:** Managed Hadoop/Spark cluster, not serverless SQL queries.

[Documentation: Amazon Athena](https://docs.aws.amazon.com/athena/)

---

### 57. Which service provides managed security credentials and access management?

**Correct Answer:** **AWS IAM**

**Explanation:**
IAM (Identity and Access Management) allows creating users, groups, and roles with fine-grained permissions. It secures access to AWS services and resources. IAM supports MFA, policy management, and integration with AWS organizations for account-wide control, ensuring secure access management.

* **Wrong options:**

  * **KMS:** Key management for encryption, not identity management.
  * **Shield:** DDoS protection, not access control.
  * **WAF:** Protects web applications, not credentials.

[Documentation: AWS IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)

---

### 58. Which AWS service is used for DDoS protection?

**Correct Answer:** **AWS Shield**

**Explanation:**
AWS Shield protects AWS applications from DDoS attacks. Shield Standard offers automatic protection against common attacks, while Shield Advanced provides enhanced detection, mitigation, and reporting. It ensures availability and reduces the risk of downtime during volumetric attacks.

* **Wrong options:**

  * **WAF:** Protects against web exploits, not DDoS.
  * **IAM:** Access management, not security defense.
  * **CloudTrail:** Logs activity, not attack protection.

[Documentation: AWS Shield](https://docs.aws.amazon.com/waf/)

---

### 59. Which service allows content delivery at global edge locations?

**Correct Answer:** **Amazon CloudFront**

**Explanation:**
CloudFront is a global CDN that caches content at edge locations worldwide, reducing latency and improving performance. It integrates with S3, Lambda\@Edge, and WAF. CloudFront is ideal for static website content, videos, APIs, and applications requiring low-latency access.

* **Wrong options:**

  * **S3:** Storage service, not global delivery.
  * **Route 53:** DNS routing, not CDN.
  * **ELB:** Balances traffic locally, not edge caching.

[Documentation: Amazon CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)

---

### 60. Which AWS service allows provisioning infrastructure using templates as code?

**Correct Answer:** **AWS CloudFormation**

**Explanation:**
CloudFormation enables Infrastructure as Code (IaC) using JSON or YAML templates. It automates resource creation, updates, and deletion for repeatable deployments. Templates are version controlled, reusable, and reduce errors, ensuring consistent infrastructure across environments.

* **Wrong options:**

  * **OpsWorks:** Configuration management, not full IaC.
  * **Elastic Beanstalk:** Simplifies deployment, not full infrastructure automation.
  * **Config:** Monitors resources, does not provision them.

[Documentation: AWS CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)

