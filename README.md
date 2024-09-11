# Learn-AWS
This repo is to doccument my learning on AWS

### Table of content
To master AWS at an advanced level, you need a comprehensive understanding across a wide range of categories. Here's a detailed, category-wise breakdown of topics to cover for AWS mastery:

---

### **1. Core AWS Services (Compute, Storage, Networking)**
- **[Compute](https://aws.amazon.com/products/compute/)**  
  - **[EC2 (Elastic Compute Cloud)](./topics/compute/EC2.md)**: EC2 instances, instance types, AMIs, EBS volumes
  - **Lambda**: Serverless functions, event-driven architecture, Lambda layers
  - **Elastic Beanstalk**: Deploy and manage applications
  - **Auto Scaling**: Scaling policies, lifecycle hooks
  - **Lightsail**: Simplified VPS for smaller applications

- **Storage**  
  - **S3 (Simple Storage Service)**: Buckets, versioning, lifecycle policies, storage classes, encryption
  - **EFS (Elastic File System)**: File storage, NFS
  - **FSx**: Managed file systems for Windows and Lustre
  - **EBS (Elastic Block Store)**: Volume types, snapshots, encryption
  - **Glacier**: Archival storage, retrieval options

- **Networking**  
  - **VPC (Virtual Private Cloud)**: Subnets, routing tables, NAT gateways, VPC peering
  - **Elastic Load Balancing**: ALB, NLB, cross-zone load balancing
  - **Direct Connect**: Dedicated network connection
  - **Route 53**: DNS management, health checks, routing policies (latency-based, geo-routing)

---

### **2. Security & Identity Management**
- **IAM (Identity and Access Management)**  
  - Users, groups, roles, policies (inline, managed), MFA, permission boundaries

- **KMS (Key Management Service)**  
  - Key creation, rotation, encryption at rest, data keys

- **Secrets Manager**  
  - Secure storage for API keys, passwords

- **Cognito**  
  - User authentication, federated identities, JWT tokens

- **Security Groups & NACLs (Network Access Control Lists)**  
  - Inbound/outbound rules, stateful vs. stateless filtering

- **AWS Organizations**  
  - Multi-account management, service control policies (SCPs), consolidated billing

- **GuardDuty**  
  - Threat detection, anomaly detection

- **Inspector**  
  - Automated security assessment of applications, EC2 instances

- **Macie**  
  - Data privacy protection and data classification

---

### **3. Databases & Analytics**
- **RDS (Relational Database Service)**  
  - MySQL, PostgreSQL, Aurora, Multi-AZ, read replicas, backups

- **DynamoDB**  
  - NoSQL database, global tables, DAX, Streams, transactions

- **ElastiCache**  
  - Managed Redis and Memcached, clustering, backup & restore

- **Redshift**  
  - Data warehousing, cluster management, Spectrum

- **Athena**  
  - Serverless query service for data in S3

- **EMR (Elastic MapReduce)**  
  - Big data processing with Hadoop, Spark

- **Glue**  
  - ETL service, data catalog, workflows

- **Kinesis**  
  - Data streaming, Kinesis Data Streams, Kinesis Firehose

- **Data Pipeline**  
  - Workflow orchestration for data transfer and transformation

- **QuickSight**  
  - Business intelligence service, visualizations, dashboards

---

### **4. DevOps & CI/CD**
- **CodeCommit**  
  - Managed source control service (Git repositories)

- **CodeBuild**  
  - Build automation, Docker image builds

- **CodeDeploy**  
  - Deployment automation, Blue/Green, Canary deployments

- **CodePipeline**  
  - Continuous delivery, integration with other DevOps tools

- **CloudFormation**  
  - Infrastructure as Code, stacks, templates, change sets

- **Elastic Container Service (ECS)**  
  - Container orchestration for Docker, Fargate, cluster management

- **EKS (Elastic Kubernetes Service)**  
  - Managed Kubernetes clusters, Helm charts, worker nodes

- **Systems Manager**  
  - Parameter Store, Patch Manager, Run Command, Session Manager

- **OpsWorks**  
  - Configuration management with Chef, Puppet

---

### **5. Monitoring, Logging & Auditing**
- **CloudWatch**  
  - Metrics, custom metrics, dashboards, alarms, logs, log streams, log groups

- **X-Ray**  
  - Distributed tracing for microservices, service maps

- **CloudTrail**  
  - API activity logging, audit trails

- **AWS Config**  
  - Configuration compliance, resource inventory

- **VPC Flow Logs**  
  - Capture network traffic logs

---

### **6. Serverless Computing**
- **Lambda**  
  - Event-driven execution, Lambda@Edge

- **API Gateway**  
  - Serverless REST APIs, WebSocket APIs, Lambda integration

- **Step Functions**  
  - Serverless workflows, state machines

- **S3 Events**  
  - Event notifications for bucket operations

---

### **7. Application Integration**
- **SNS (Simple Notification Service)**  
  - Publish/subscribe messaging, SMS, email notifications

- **SQS (Simple Queue Service)**  
  - Distributed queuing, FIFO queues, dead-letter queues

- **EventBridge**  
  - Event-driven service integration, rule matching

- **AppFlow**  
  - Managed data integration between AWS and SaaS applications

---

### **8. Machine Learning & AI**
- **SageMaker**  
  - Build, train, and deploy ML models, notebook instances, SageMaker Studio

- **Rekognition**  
  - Image and video analysis, object recognition

- **Polly**  
  - Text-to-speech service, multiple languages

- **Comprehend**  
  - Natural language processing (NLP), sentiment analysis

- **Lex**  
  - Build conversational bots, NLP, speech recognition

- **Transcribe**  
  - Automatic speech-to-text transcription

- **Personalize**  
  - Real-time personalization and recommendation engine

---

### **9. Edge Services**
- **CloudFront**  
  - Content Delivery Network (CDN), edge caching, Lambda@Edge

- **Global Accelerator**  
  - Network layer acceleration for global applications

- **Route 53 Latency & Geo Routing**  
  - DNS-based routing optimization for global users

---

### **10. Migration & Hybrid Cloud**
- **DMS (Database Migration Service)**  
  - Migrate databases from on-premises to AWS

- **Server Migration Service (SMS)**  
  - Migrate on-premises servers to AWS

- **Storage Gateway**  
  - Hybrid cloud storage, file, volume, and tape gateways

- **Snowball & Snowmobile**  
  - Physical data transport for large-scale data migration

- **Outposts**  
  - AWS infrastructure on-premises for hybrid cloud

---

### **11. Cost Management & Governance**
- **Billing and Cost Management**  
  - Billing dashboard, budgets, consolidated billing

- **Cost Explorer**  
  - View and analyze AWS spending trends

- **Trusted Advisor**  
  - Cost optimization, security, fault tolerance, performance checks

- **Savings Plans & Reserved Instances**  
  - Cost-saving models for compute services

- **AWS Budgets**  
  - Set custom cost and usage budgets

- **AWS Control Tower**  
  - Multi-account governance, automated landing zone

---

### **12. IoT**
- **AWS IoT Core**  
  - Connect IoT devices, MQTT, IoT Rules Engine

- **Greengrass**  
  - Local device communication and processing

- **IoT Analytics**  
  - Analyze data from IoT devices

- **IoT Device Management**  
  - Fleet management, over-the-air updates, device shadowing

---

This comprehensive list should give you a solid roadmap to master AWS at an advanced level.