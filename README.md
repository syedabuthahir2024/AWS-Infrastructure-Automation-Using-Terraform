# AWS-Infrastructure-Automation-Using-Terraform

🚀 Project Overview :

This project showcases the deployment and management of a scalable, secure, and high-availability infrastructure on AWS using Terraform. It highlights the use of Infrastructure as Code (IaC) to design and implement robust cloud architecture efficiently.

Key Highlights :

VPC Design: Created a Virtual Private Cloud (VPC) with public subnets, an internet gateway, and custom route tables for seamless communication.
EC2 Provisioning: Automated the provisioning of EC2 instances using Terraform, configured with user data scripts to host web applications running on Apache.
Application Load Balancer (ALB): Set up an ALB to distribute traffic across EC2 instances for high availability and fault tolerance.
Reusable Terraform Modules: Developed modular Terraform scripts for consistent and efficient deployment of AWS resources, including S3 buckets and security groups.
Health Monitorin: Configured target groups for health checks, ensuring optimized application performance.
AWS CLI Integration: Utilized AWS CLI to dynamically retrieve instance metadata and improve server functionality.

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
