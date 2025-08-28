
# AWS Practice Questions – Set 1 (Answers & Explanations)

---

### 1. Which AWS service is used to run containerized applications without managing servers?

**Correct Answer:** **AWS Fargate**

**Explanation:**
AWS Fargate allows you to run containers without having to manage the underlying servers or clusters. It integrates with both Amazon ECS and Amazon EKS, enabling a true serverless container execution model. You only pay for the resources required to run your containers, making it cost-efficient and scalable. Unlike EC2, you don’t have to worry about provisioning, patching, or scaling servers. This makes it ideal for microservices-based applications.

* **Wrong options:**

  * **Amazon EC2:** Requires manual management of servers.
  * **AWS Lambda:** Runs functions, not long-running containerized apps.
  * **Amazon Lightsail:** Simplified VPS, not optimized for containers.

[Read more in AWS Docs](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Fargate.html)

---

### 2. Which service provides object storage with virtually unlimited scalability?

**Correct Answer:** **Amazon S3**

**Explanation:**
Amazon S3 (Simple Storage Service) is designed to store and retrieve any amount of data at any time. It provides 99.999999999% (11 9’s) durability, making it highly reliable for storing backups, big data, and media. Its scalability is automatic, and you don’t need to provision capacity. S3 also supports multiple storage classes to optimize cost.

* **Wrong options:**

  * **Amazon EBS:** Block storage for single EC2 instances.
  * **Amazon EFS:** Scalable file storage for multiple EC2 instances.
  * **Amazon RDS:** Relational database service, not object storage.

[Read more in AWS Docs](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)

---

### 3. Which service is best suited for real-time data streaming?

**Correct Answer:** **Amazon Kinesis**

**Explanation:**
Amazon Kinesis is designed for collecting, processing, and analyzing real-time streaming data such as logs, IoT telemetry, or clickstream data. It provides low-latency ingestion and processing at scale, enabling analytics in seconds rather than minutes or hours. Kinesis also integrates seamlessly with Lambda and S3 for downstream processing and storage.

* **Wrong options:**

  * **Amazon SQS:** Message queuing, not real-time streaming.
  * **Amazon SNS:** Pub/Sub messaging, not designed for continuous streams.
  * **Amazon EMR:** Big data batch processing, not real-time ingestion.

[Read more in AWS Docs](https://docs.aws.amazon.com/streams/latest/dev/introduction.html)

---

### 4. Which database service is fully managed and designed for NoSQL workloads?

**Correct Answer:** **Amazon DynamoDB**

**Explanation:**
Amazon DynamoDB is a fully managed NoSQL database service that delivers single-digit millisecond performance at any scale. It supports key-value and document models and is ideal for web apps, gaming, IoT, and other workloads requiring low latency. With on-demand and provisioned capacity modes, DynamoDB offers flexibility and cost control.

* **Wrong options:**

  * **Amazon RDS:** Relational database, not NoSQL.
  * **Amazon Redshift:** Data warehouse for analytics.
  * **Amazon Aurora:** Relational, MySQL/PostgreSQL compatible.

[Read more in AWS Docs](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html)

---

### 5. Which service helps distribute incoming traffic across multiple resources?

**Correct Answer:** **Elastic Load Balancing (ELB)**

**Explanation:**
Elastic Load Balancing automatically distributes incoming application or network traffic across multiple targets, such as EC2 instances, containers, and IP addresses. It improves fault tolerance and availability by ensuring no single instance is overloaded. AWS offers multiple load balancers (ALB, NLB, and CLB), each designed for different workloads.

* **Wrong options:**

  * **Amazon Route 53:** DNS service, not load balancing.
  * **Amazon CloudFront:** CDN, not direct load distribution.
  * **AWS Auto Scaling:** Adjusts capacity, not request distribution.

[Read more in AWS Docs](https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/what-is-load-balancing.html)

---

### 6. Which AWS service is designed for data warehousing and analytics?

**Correct Answer:** **Amazon Redshift**

**Explanation:**
Amazon Redshift is a fully managed data warehouse that allows you to analyze structured and semi-structured data using SQL. It supports petabyte-scale storage and integrates with BI tools for dashboards and reporting. Redshift is optimized for analytical queries (OLAP), making it suitable for business intelligence workloads.

* **Wrong options:**

  * **Amazon RDS:** Relational databases for transactions, not analytics.
  * **Amazon DynamoDB:** NoSQL, not designed for data warehousing.
  * **Amazon Aurora:** Relational, OLTP not OLAP.

[Read more in AWS Docs](https://docs.aws.amazon.com/redshift/latest/mgmt/welcome.html)

---

### 7. Which service allows you to create isolated sections of the AWS Cloud?

**Correct Answer:** **Amazon VPC (Virtual Private Cloud)**

**Explanation:**
Amazon VPC enables you to provision a logically isolated section of the AWS cloud where you can launch resources in a virtual network you define. You control IP ranges, subnets, route tables, and network gateways. It’s fundamental for building secure and scalable cloud architectures.

* **Wrong options:**

  * **AWS Organizations:** Manages multiple accounts, not networks.
  * **Amazon EC2:** Compute service, not networking.
  * **AWS IAM:** Identity and access management, not network isolation.

[Read more in AWS Docs](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)

---

### 8. Which service provides a fully managed message queuing system?

**Correct Answer:** **Amazon SQS**

**Explanation:**
Amazon SQS (Simple Queue Service) provides secure, durable, and highly available message queues. It decouples microservices and allows asynchronous communication between distributed components. SQS supports both Standard queues (high throughput) and FIFO queues (ordered and exactly-once processing).

* **Wrong options:**

  * **Amazon SNS:** Pub/Sub notifications, not queuing.
  * **Amazon MQ:** Managed message broker, heavier than SQS.
  * **Amazon Kinesis:** Real-time streaming, not queues.

[Read more in AWS Docs](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html)

---

### 9. Which AWS service automates infrastructure as code?

**Correct Answer:** **AWS CloudFormation**

**Explanation:**
AWS CloudFormation allows you to model and provision AWS resources using templates (YAML or JSON). This enables infrastructure as code (IaC), ensuring consistent environments across dev, test, and prod. With CloudFormation, you can automate deployments, reduce manual errors, and version control infrastructure.

* **Wrong options:**

  * **AWS OpsWorks:** Configuration management, not IaC templates.
  * **AWS Elastic Beanstalk:** Simplified app deployment, not full IaC.
  * **AWS Config:** Tracks configuration changes, not provisioning.

[Read more in AWS Docs](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)

---

### 10. Which service helps you monitor AWS resources and applications in real-time?

**Correct Answer:** **Amazon CloudWatch**

**Explanation:**
Amazon CloudWatch provides monitoring and observability for AWS resources and applications. It collects metrics, logs, and events to help you understand performance and troubleshoot issues. CloudWatch Alarms can trigger automated actions, such as scaling policies or notifications. This makes it critical for operational excellence in AWS environments.

* **Wrong options:**

  * **AWS Config:** Compliance monitoring, not performance metrics.
  * **AWS X-Ray:** Traces requests, not broad monitoring.
  * **Amazon GuardDuty:** Threat detection, not general monitoring.

[Read more in AWS Docs](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html)


