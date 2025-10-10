# Terraform
[Terraform University Site](https://developer.hashicorp.com/terraform)
##### _By Ako Seneki_
### What is Terraform?
* Terraform is a tool for infrastructure provisioning
* It automates and manages your infrastructure
* Provisions your platform (cloud)
* And the services that run on the platform

### Where does the Terraform comes into picture in the DevOps space?
* Provisioning infrastructure
* Deploying Application (esp. the microservices applications)

### To do the infrastructure provisioning - it means to:
* create VPC
* spin up servers
* install docker
* create Azure/AWS users and permissions

### What is the Difference between Ansible and Terraform?
* Both are Infrastructure as code (IaC)
* But the Terraform mainly deals with infrastructure provisioning
* While on the other hand, ansible is mainly a configuration tool that does the following:
    - Configure that infrastructure
    - deploy apps
    - install/update software
* Ansible is more mature while terrform is relatively new
* Terraform is more advanced in orchestration
* So to conclude, terrafrom is better at provisioning infrastructure and ansible is good for configuring that provisioned infrastructure


### Managing the Existing Infrastructure
- create infra
- changes to infra
- It is easy with the use of Terraform

### Replicating the Infrastructure
- Dev Env
- Prod Env - creates the identical infra without the need to create new infra


### How does Terrafrom do all this?
- How does Terraform connect to the platform provider?

* Terraform has two main components:
  1. Core - uses 2 input sources like the TF-Config
          * State - keeps the infra in the up to date state of what the infra desired state is
          * TF-Config
  2. Providers - like AWS, Azure | (IaaS)
  .             Kubernetes (PaaS)
  .             Fastly (SaaS)

  ### Declarative vs Imperative
  #### What does declarative mean exactly?
  * You define the end state in your config file (you declare the What you desire)
  * For example; 5 servers with following network config and one Azure user with the x amount of permissions
  #### What does imperative mean exactly?
  * define exact steps - declaring the HOW to achieve the desired state
 
  -    Dec method you just adjust the old config file and declare your new state while the imp method you have to write new steps to add resources
  #### Some Terraform commands for different stages
  1. Refresh - query infra provider to get the current state
  2. Plan - create an execution plan; determine what actions are necessary to achieve the desired state (just a preview, no changes to real resources)
  3. Apply - execute the plan
  4. Destroy - destroy the resources/infrastructure that reverses all the application of the desired state
 
## Using Terraform with Azure Cloud
#### Contents
  -    Imperative vs Declarative
  -    Terraform 101
  -    The Importance of state
  -    Structure of Terraform file
  -    Using the Azure provider for Terraform
  -    Creating resources in Azure
  -    Interacting with Azure Key Vault
  -    Calling ARM template from Terraform

#### 1. Imperative vs Declarative
-    

 







  
