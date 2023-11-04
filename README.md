# Terraform

- ### [00-Terraform-Basics](00-Terraform-Basics) - Terraform Definitions and more
- ### [01-Terraform-Installation](01-Terraform-Installation) - Install Terraform

- ### [02-Terraform-Configuration](01-Terraform-Configuration) - Configure Terraform

- ### [03-Terraform-Terminologies](03-Terraform-Terminologies) - Key Terraform Terminologies
    - **Provider** : Define the providers like AWS, Azure, GCP
    - **Resource** : Infrastructure Resources to be created, ex: VPC, S3, EC2
    - **Data Sources** (optional) : Pull the data from the provider
    - **Variable**: Give user option to enter the value for defined resources
    - **Arguments** : Inputs
    - **Attributes** : Outputs
    - **Meta-Arguments** : Terraform specific Inputs ex: count, for_each,depends_on

- ### [04-Terraform-Top-Level-Blocks](04-Terraform-Top-Level-Blocks) - Terraform Top Level Blocks
    - **Terraform Block** (>0.13 version) or Terraform Settings Block or Terraform Configuration Block 
    - **Provider Block**
    - **Resource Block**
    - **Input Variables Block**
    - **Output Values Block**
    - **Local Values Block**
    - **Data Sources Block**
    - **Modules Block**

- ### [05-Terraform-Commands](05-Terraform-Commands) - Basic Terraform Commands
    - *`terraform init`*
    - *`terraform validate`*
    - *`terraform plan`*
    - *`terraform apply`* or *`terraform apply -auto-approve`*
    - *`terraform destroy`* or *`terraform destroy -auto-approve`*

- ### [06-Terraform-VPC-Demo](06-Terraform-VPC-Demo) - Simple Demo to Create AWS VPC using Terraform

- ### [07-Terraform-Resources](07-Terraform-Resources) - Understanding Resource behavior
    - ***created***
    - ***destroyed*** 
    - ***updated***

- ### [08-Terraform-Resource-Meta-Arguments](08-Terraform-Resource-Meta-Arguments) - Terraform Meta-Arguments
    1. [***`count`***](08-Terraform-Resource-Meta-Arguments/08-01-count/) : The ***count*** Meta Argument allows you to **specify the number of instances of a resource you want to create**.
    2. [***`for_each`***](08-Terraform-Resource-Meta-Arguments/08-02-for_each/) : **Create multiple instances of a resource based on the elements of a ***`map`*** or ***`set`*****
    3. [***`depends_on`***](08-Terraform-Resource-Meta-Arguments/08-03-depends_on/) : **establish ***explicit*** dependencies between resources**
    4. [***`provider`***](08-Terraform-Resource-Meta-Arguments/08-04-provider/) : use **multiple providers** within the same configuration to **manage resources in different cloud regions or service providers**
    5. [***`lifecycle`***](08-Terraform-Resource-Meta-Arguments/08-05-lifecycle/) : control specific aspects of **how resources are managed during their lifecycle**. 








- #### Pending Notes
    - 02-Terraform-Configuration
    - 04-Terraform-Top-Level-Blocks
        - Multiple Providers
     - 05-Terraform-Commands
     - 06-Terraform-VPC-Demo
        - execute the terraform commands to create VPC using vpc.tf and update the command documentation with screenshots     
     - 07-Terraform-Resources
        - Terraform resource behavior for  in place update (add tag) destroy and recreate (change AZ)
    - 08-Terraform-Resource-Meta-Arguments
        - *for_each* for set creating iam user notes

- #### Revise following
    - terraform dependency file ?
    - terraform lock file ?
