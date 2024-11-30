This Terraform-powered architecture implements:
- Multi-Region Deployment: VPCs span across us-east-1 and us-west-1 for high availability and disaster recovery.  
- Secure Traffic Management: ALBs in public subnets route traffic securely to backend services.  
- Private Subnets for EC2: EC2 instances run in private subnets, enhancing security and isolation.  
- Modular Design: Infrastructure is built using reusable modules for easy scaling and maintenance.  
- Fault Tolerance & Redundancy: Designed to ensure minimal downtime with seamless failover across regions.  
