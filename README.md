# Task 5

#### Deploy a Strapi application on AWS ECS Fargate Spot using Terraform. Assign a sub-domain to it. After creation, make a Loom video of the process and destroy the service

### Terraform
- Resource created with terraform:
    - ECS Cluster
    - ECS Cluster Service
    - VPC: Subnets, internet gateway, route table
    - Application Load Balancer 

### Sub-domain configuration
- Route 53
    - Added domain: infotex.digital
    - Changed domain name servers to aws dns
    - Created A record for a sub domain

    