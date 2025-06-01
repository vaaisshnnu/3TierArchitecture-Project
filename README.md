# 3 Tier Architecture in AWS

# Tier 1 – Presentation (Frontend Layer):
Amazon EC2 (Auto Scaling Group) + IAM Role

# Tier 2 – Application (Logic Layer):
Nginx , PM2, NodeJs
AutoScaling Group
AMI's & Launch Templates
Elastic Load Balancer (ELB)
Amazon EC2 (Auto Scaling Group)
Amazon S3 (for Stroring the Code)

# Tier 3 – Data Layer:
Amazon S3 (for backups or object storage) 
Amazon RDS(MySQL)

