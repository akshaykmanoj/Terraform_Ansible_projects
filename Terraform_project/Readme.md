# Terraform-AWS: AWS Infrastructure as Code (IaC)
### Project Overview
This project exemplifies the principles of Infrastructure as Code (IaC) through the use of Terraform, specifically designed to create a
comprehensive AWS infrastructure. The primary focus is on establishing a Virtual Private Cloud (VPC) complete with both public and private subnets. 
Additionally, the project involves the launch of EC2 instances, with Ansible taking charge of the subsequent installation of Git on these instances.

### Key Features
- VPC Creation: Orchestrates the creation of a VPC with distinct public (Public-1) and private (Private-1) subnets.
- EC2 Instance Deployment: Launches EC2 instances within each subnet to support the overall infrastructure.
- Ansible Integration: Utilizes Ansible for the installation of Git on the provisioned EC2 instances.
- Networking Configurations: Manages essential networking components such as Routing Tables, Internet Gateway (IG), Network Address Translation (NAT), and Security Groups.
- State Management: The Terraform state file is stored in an S3 Bucket, serving as a centralized backend for effective state management.
