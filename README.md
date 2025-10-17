# Introduction-to-Terraform
## Definition of Terraform
Terrafrom is an infrastructure as a code tool which is used to create and manage resources safetly and efficiently in the cloud and on premises through their application programming interface (API).
## Stages in Terraform Workflow
There are fours stages in a terraform workflow. These are:
* Write: you define the resources in configuration files.
* Initialize: this prepares your workspace so that terraform can apply your configuration.
* Plan: terraform creates an execution plan which desribes the infrastructure it will create, update or destroy based on the existing infrastructure and your configuration.
* Apply: terraform provisions your infrastructure and updates the state file on approval.#
## Project Objective
The objective of this project is to create an EC2 instance and AMI using terraform.
## Project Implementation
* I installed terraform on my computer and used the command terraform --version to be sure it has been installed. Find screenshot below.
* I configured the aws CLI using access key that was created in the aws console. The command I used was aws configure.
* I created a folder called learningTerraform where all configuration files was saved.
* I created a file called main.tf and wrote the configuration below.
* 
