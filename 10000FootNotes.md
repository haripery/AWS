## 10000 Foot Overview:
Topics need to concentrated:
1. AWS Global Infrastructure
2. Networking and content Delivery
3. Compute
4. Databases
6. Storage
7. Management Tools
8. Security and Identity
9. Messaging
10. Migration

### AWS Global Infrastrcuture:
1. Regions and Availability Zones
2. Edge Location - CDN (Cache Locations)

### Network and Content Delivery:
1. VPC - Virtual Private Cloud(how to build VPC from Memory) --Important
2. Route53 - DNS Service(Phone book example)
3. Cloud Front - CDN(Edge Locations)
4. Direct Connect - Dedicated line 

### Compute 
1. EC2 - Elastic Compute
2. EC2 Container Service(ECS) - Contains Docker services, Contains EC2 Instances
3. Elastic BeanStalk 
4. Lambda - Serverless app

### Storage
1. S3 (simple storage service)- Contains objects(Videos, songs, Files)
2. Glacier - Contains Archieve from S3(Low costs)
3. Storage Gateway - Communicates with S3 to headquaters(VM)

### Databases:
1. RDS - Relational Database Services(MySQL, PostgreSQL, MariaDB, etc.,)
2. DynamoDB - Non-Relational Database - NoSQL(MongDB)
3. Redshift - Datawarehousing Service - Used to get reports by copying contents from production
4. Elasticache - Cache service

Migration:
1. Snowball - import and Export of Disks to EC2
2. DMS - Database Migration Services
3. Server Migration Services - virtual Machines (web app machines)

### Analytics:
1. Athena - SQL queries on S3
2. EMR - Elastic MapReduce
3. Cloud Search
4. Elastic Search
5. Kinesis - Analyze real time Large data
6. Data Pipeline - Move S3 to DynamoDB
7. Quicksight - BI tool for Visualization, etc

### Security and Identity
1. IAM - Identity Access Management - Imporatnt topic create users, providing Access
2. Inspector
3. Certificate Manager - Provides SSL certifications
4. Directory Service
5. WAF - Webapplication Firewall
6. Artificats - Compliance Reports

### Management Tools:
1. Cloud Watch - Monitor Performance
2. Cloud Formation - Documents the AWS environment details --Useful Tech
3. Cloud Trail - Auditing Changes in AWS
4. OpsWorks - Automating Deployments with Shifts
5. Config - Set alerts any changes in security groups
6. Service Catalog
7. Trusted Advisor - recommend performance optimization, security updates etc

### Application Services
1. Step Functions - Visualizing app, See Microservices usage
2. SWF
3. API Gateway - useful for Angular apps
4. App Stream
5. Elastic Transcoder

### Developer Tools
1. Code Commit - Git kind
2. Code Build - Compiling Code
3. Code Deploy - EC2 Instances
4. Code Pipeline

### Mobile Services
1. Mobile Hub - Configure userAuth, push notifications, own consoleetc
2. Cognito - sign in Apps, IOS in AWS, like OAuth 2.0
3. Device Farm - Testing apps on Physical Devices
4. Mobile Analytics
5. Pin Point - like Google Analytics

### Business Productivity
1. WorkDocs
2. WorkMail

### IOT

### Desktop and App streaming
1. WorkSpaces
2. AppStream 2.0

### AI
1. Polly
2. Machine Learning - Give data to learn 
3. Rekognition - image recognition software

### Messaging
1. SNS - Email, Text Message, https endpoints
2. SQS - Decoupling Applications, Queue services - image uploads queues.
3. SES - Simple Email Services
