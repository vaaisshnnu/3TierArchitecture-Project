# 3 Tier Architecture in AWS

Tier 1 – Presentation (Frontend Layer):
IAM
Amazon S3 (for Stroring the Code)
Route 53 (DNS)

Tier 2 – Application (Logic Layer):
Nginx , PM2, NodeJs
AutoScaling Group
Launch Templates
Elastic Load Balancer (ELB)
Amazon EC2 (Auto Scaling Group)
AWS Lambda (optional microservices)

Tier 3 – Data Layer:
Amazon S3 (for backups or object storage) 
Amazon RDS (for relational database)
Amazon DynamoDB (NoSQL DB)

