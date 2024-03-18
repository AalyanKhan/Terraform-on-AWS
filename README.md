# Terraform on AWS Projects

This repository contains my Terraform projects that I created while following the "Terraform on AWS with SRE & IaC DevOps" course. These projects demonstrate real-world infrastructure automation using Terraform on AWS.

## Projects Completed
01. Infrastructure as Code (IaC)
02. Terraform Basics
  - Install Tools on MacOs, LinuxOS and WindowsOS
  - Terraform Command Basics
  - Terraform Language Syntax
03. Terraform Settings, Providers and Resources
04. Terraform Variables and Datasources
05. Terraform Loops, Meta-Arguments and Splat Operators
06. AWS VPC 3-Tier Architecture
07. AWS EC2 Instances and Security Groups in a VPC
08. AWS Classic Load Balancer
09. AWS ALB Application Load Balancer
10. AWS ALB Context-Path based Routing 
11. AWS ALB Host-Header based Routing
12. AWS ALB HTTP Header and Query String Redirects
13. AWS DNS to DB Implementation
14. AWS Autoscaling with Launch Configuration
15. AWS Autoscaling with Launch Templates
16. AWS Network Load Balancer with TCP and TLS
17. AWS CloudWatch Alarms for ALB, ASG and CIS
18. Develop and Reference Terraform Modules locally
19. Develop Terraform Module from scratch
20. Remote State Storage with AWS S3 and DynamoDB
21. Terraform Remote State Datasource
22. IaC DevOps using AWS CodePipeline 

## AWS Services Covered
01. AWS VPC Virtual Private Cloud 
02. AWS VPC NAT Gateways for Outbound Communication
03. AWS VPC Public and Private Subnets
04. AWS EC2 Instances
05. AWS Security Groups
06. AWS Classic Load Balancer
07. AWS ALB Application Load Balancer - Basic
08. AWS ALB Context-Path based Routing
09. AWS ALB Host-Header based Routing
10. AWS ALB Custom-HTTP Header based Routing
11. AWS ALB Query String based Redirects
12. AWS Autoscaling with Launch Configurations
13. AWS Autoscaling with Launch Templates
14. AWS Network Load Balancer
15. AWS CloudWatch Alarms
16. AWS Certificate Manager (ACM)
17. AWS Route53 
18. AWS CodeBuild
19. AWS CodePipeline 
20. AWS RDS Database 
21. AWS Elastic IP
22. AWS SNS

## Terraform Concepts Covered 
01. Terraform Install
02. Command Basics (init, validate, plan, apply)
03. Language Syntax (Blocks, Arguments)
04. Settings Block
05. Provider Block
06. Resources Block
07. Resource Meta-Arguments (depends_on, count, for_each)
08. Input Variables - Basics
09. Input Variables - Assign When Prompted
10. Input Variables - Override default with cli var
11. Input Variables - Assign with terraform.tfvars
12. Input Variables - Assign with tfvars var-file argument
13. Input Variables - Assign with auto tfvars
14. Input Variables - Lists
15. Input Variables - Maps
16. Input Variables - Sensitive Input Variables
17. Function: File
18. Output Values
19. Local Values
20. Datasources
21. Backends - Remote State Storage
22. File Provisioner
23. local-exec Provisioner
24. remote-exec Provisioner
25. Null Resource
26. Modules from Public Registry
27. Build Local Module
28. For Loop with Lists
29. For Loop with Maps
30. For Loops with Advanced Maps
31. Legacy Splat Operator
32. Latest Splat Operator
33. Function: toset
34. Function: tomap
35. Function: keys
36. Module Upgrades
37. Random Resource
39. Terraform Import 

## What I Learned
Through this course, I gained hands-on experience with:
- Mastering Terraform in a real-world perspective with 22 practical demos
- Building AWS VPC 3-Tier Architecture using Terraform
- Implementing various Load balancers (CLB, ALB, and NLB) using Terraform
- Creating DNS to DB Architecture on AWS using Terraform
- Building Autoscaling with Launch Configuration using Terraform
- Building Autoscaling with Launch Templates using Terraform
- Implementing AWS CloudWatch Alarms using Terraform
- Setting up IaC DevOps using AWS CodePipeline for Terraform Configurations
- Learning about Terraform State, Local and Remote Backends
- Implementing all Terraform Provisioners
- Working with Terraform Modules (Public and Local Modules)

## Course Information
- **Course**: Terraform on AWS with SRE & IaC DevOps
- **Prerequisites**: AWS Cloud account for hands-on activities
- **Level**: Beginner to Advanced Terraform concepts


## Repository Structure
This repository is organized into folders corresponding to each course module:
- Each folder contains Terraform configurations for specific AWS services
- Configuration files follow Terraform best practices
- Includes variables, outputs, and proper resource organization

## Additional Learning Resources
- [HashiCorp Terraform Documentation](https://www.terraform.io/docs)
- [AWS Provider Documentation](https://registry.terraform.io/providers/hashicorp/aws/latest/docs)
- [Terraform Best Practices](https://www.terraform.io/docs/cloud/guides/recommended-practices/index.html)





