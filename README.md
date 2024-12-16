# AWS-Infrastructure-Automation-Using-Terraform

🚀 Project Overview :

This project showcases the deployment and management of a scalable, secure, and high-availability infrastructure on AWS using Terraform. It highlights the use of Infrastructure as Code (IaC) to design and implement robust cloud architecture efficiently.

Key Highlights :

Deployed and managed a scalable, secure, and high-availability infrastructure on AWS using Terraform, showcasing expertise in Infrastructure as Code (IaC). Designed a Virtual Private Cloud (VPC) with public subnets, an internet gateway, and custom route tables to enable efficient network communication. Configured EC2 instances using custom user data scripts to host web applications with Apache, ensuring automated server setup and consistent deployment. Implemented an Application Load Balancer (ALB) to distribute traffic across multiple EC2 instances, achieving redundancy and fault tolerance. Developed reusable Terraform modules to automate provisioning of key AWS resources, including S3 buckets, ALB configurations, and security groups with controlled ingress and egress rules. Created and attached target groups to the ALB for monitoring application health and optimizing performance. Additionally, leveraged the AWS CLI within user data scripts to dynamically retrieve instance metadata and enhance server functionality. Key technologies utilized include Terraform, AWS (EC2, VPC, Subnets, ALB, S3, Security Groups), Bash scripting, and the Apache web server.

Technologies Used :

Terraform: For automating cloud infrastructure deployment.
AWS Services: EC2, VPC, Subnets, ALB, S3, Security Groups.
Bash Scripting: Used for automating server setup and configuration.
Apache Web Server: To serve web applications.

Steps to configure :

1. Initialize Terraform: Terraform needs to initialize the working directory to download required provider plugins and set up the environment for applying configurations. Run the following command: terraform init
2. Validate the Configuration: Before applying the Terraform configuration, you can validate your configuration files for any errors or missing dependencies by running:
terraform validate
3. Apply the Terraform Plan: To create the infrastructure and provision resources on AWS, run the following command: terraform apply
4. Cleanup: Destroy the Terraform Infrastructure: Once you no longer need the infrastructure or want to tear it down, run the following command: terraform destroy
