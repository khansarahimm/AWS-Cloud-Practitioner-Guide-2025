# Set 2 - Answers and Explanations

## Q1. Which AWS service is best suited for monitoring application performance and generating alarms based on thresholds?

**Correct Answer:** Amazon CloudWatch

**Explanation:**
Amazon CloudWatch is specifically designed for monitoring AWS resources and applications. It collects metrics, logs, and events, allowing you to set alarms on thresholds such as CPU utilization or latency. When thresholds are breached, CloudWatch can trigger notifications or automated actions.

* **Why not others?**

  * **AWS Config:** Focuses on compliance and resource configuration tracking, not performance metrics.
  * **AWS Trusted Advisor:** Provides best practice recommendations, not real-time monitoring.
  * **AWS CloudTrail:** Tracks API activity and governance, not performance monitoring.

[Read more: AWS CloudWatch Documentation](https://docs.aws.amazon.com/cloudwatch/)

---

## Q2. Which AWS service helps in decoupling application components using messaging?

**Correct Answer:** Amazon SQS (Simple Queue Service)

**Explanation:**
Amazon SQS allows applications to communicate asynchronously by sending, storing, and receiving messages between components. This decouples producers and consumers, improving scalability and fault tolerance.

* **Why not others?**

  * **Amazon SNS:** Good for pub/sub messaging but not designed for queue-based message storage and retrieval.
  * **Amazon Kinesis:** Focused on real-time data streaming, not decoupling application requests.
  * **Amazon MQ:** Useful for enterprise-grade message brokers but not the simplest solution like SQS.

[Read more: Amazon SQS Documentation](https://docs.aws.amazon.com/sqs/)

---

## Q3. Which service allows you to run Docker containers on AWS without managing servers?

**Correct Answer:** AWS Fargate

**Explanation:**
AWS Fargate is a serverless compute engine for containers that lets you run Docker containers without managing EC2 instances. It handles scaling, provisioning, and resource allocation automatically.

* **Why not others?**

  * **Amazon ECS (without Fargate):** Requires managing EC2 infrastructure.
  * **Amazon EKS:** Focused on Kubernetes, requiring more cluster management.
  * **AWS Lambda:** Good for serverless functions but not suitable for long-running containerized apps.

[Read more: AWS Fargate Documentation](https://docs.aws.amazon.com/fargate/)

---

## Q4. Which service provides a fully managed NoSQL database?

**Correct Answer:** Amazon DynamoDB

**Explanation:**
Amazon DynamoDB is a fully managed, serverless NoSQL database with single-digit millisecond performance at scale. It supports key-value and document data models.

* **Why not others?**

  * **Amazon RDS:** Relational database, not NoSQL.
  * **Amazon Redshift:** Data warehouse, not NoSQL.
  * **Amazon Aurora:** Relational DB compatible with MySQL/PostgreSQL, not NoSQL.

[Read more: Amazon DynamoDB Documentation](https://docs.aws.amazon.com/dynamodb/)

---

## Q5. Which AWS service helps in distributing traffic across multiple EC2 instances?

**Correct Answer:** Elastic Load Balancing (ELB)

**Explanation:**
Elastic Load Balancing automatically distributes incoming traffic across multiple EC2 instances, containers, and IP addresses. It improves fault tolerance and scalability.

* **Why not others?**

  * **Amazon Route 53:** Primarily DNS service, not a load balancer.
  * **AWS CloudFront:** Content delivery network (CDN), not traffic load distribution across servers.
  * **Auto Scaling:** Adds/removes instances but does not balance incoming traffic.

[Read more: Elastic Load Balancing Documentation](https://docs.aws.amazon.com/elasticloadbalancing/)

