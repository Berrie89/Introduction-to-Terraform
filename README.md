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
  <img width="1280" height="800" alt="Image" src="https://github.com/user-attachments/assets/111b1a67-2407-4cf1-badc-e1a4df76770d" />
  <img width="453" height="199" alt="Image" src="https://github.com/user-attachments/assets/34b77a78-f0d4-43fe-857b-a43487c82896" />
* I used to terraform init command to apply my configuration. Please find below.
  <img width="627" height="289" alt="Image" src="https://github.com/user-attachments/assets/77b3b468-aefb-45a7-918e-b972398e8e19" />
* I used the terraform validate command to ensure all configurations are correct. Find below.
  <img width="647" height="59" alt="Image" src="https://github.com/user-attachments/assets/e3cc4049-71c4-44b1-8b82-56a3c125a091" />
* I used the terraform plan command to create an execution plan. 
* I used the terraform apply command to provision resources. Find below.
  <img width="647" height="59" alt="Image" src="https://github.com/user-attachments/assets/cca42eec-5686-48da-9741-4fc99c5c8213" />
* An EC2 instance called Learning-trerraform, a VPC, Subnets were created. Find below.
<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/6b494f32-7b72-4dc2-b88f-0d2a6516ff15" />

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/4b52e8f9-53e1-418e-bda1-2c9e40a5fa43" />
* Lastly, I used the terraform destroy command to terminate the EC2 instance.Find below.
  

  
  
  
