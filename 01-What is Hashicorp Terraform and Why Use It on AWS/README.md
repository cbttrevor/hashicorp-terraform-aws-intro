## Learning Objectives

* Provisioning AWS cloud resources can be done using imperative APIs or declarative APIs
* AWS provides imperative REST APIs to perform resource management tasks
* Examples: create software-defined network (SDN), virtual machine, or load balancer

### What is Hashicorp Terraform?

* Infrastructure as code tool similar to AWS CloudFormation (but much more generic)
* Declarative resource management model
* Terraform CLI is [open source software](https://github.com/hashicorp/terraform) on GitHub
* Terraform is written with a provider-plugin model, hence it is cloud-agnostic; not proprietary like AWS CloudFormation
* Terraform configurations can be checked into source control (ie. git, Mercurial)

### Editions of Terraform

* Terraform CLI - open source 
* Terraform Cloud - team collaboration, governance rules, single sign-on (SSO), concurrency
* Terraform Enterprise - self-hosted version of Terraform Cloud

### What You'll Learn

* How to set up your development environment for Terraform
* How to construct Terraform configuration files
* Use Terraform CLI to plan and apply infrastructure resource configurations on AWS
* How to connect resources to each other