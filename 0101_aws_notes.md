

# AWS Services 

### Santhiya Notes

## Containers in AWS
Container management tools can be broken down into three categories: registry, orchestration, and compute.
## Compute
|Category             |Services                    |Description                                                   |
|---------------------|----------------------------|--------------------------------------------------------------|
|Instances(Virtul Machine)|Elastic cloud compute(EC2)   |  Provides secure, resizable compute capacity in the cloud. It makes web-scale cloud computing easier for developers. |
||EC2 spot| A Spot Instance is an instance that uses spare EC2 capacity that is available for less than the On-Demand price. Because Spot Instances enable you to request unused EC2 instances at steep discounts, you can lower your Amazon EC2 costs significantly. The hourly price for a Spot Instance is called a Spot price.-Run fault-tolerant workloads for up to 90% off|
||EC2 AutoScaling|Automa¬tically add or remove compute capacity to meet changes in demand|
||LightSail|Designed to be the easiest way to launch & manage a virtual private server with AWS. An easy-t¬o-use cloud platform that offers everything need to build an application or website.|
||Batch|Enables developers, scientists, & engineers to easily & effici¬ently run hundreds of thousands of batch computing jobs on AWS. Fully managed batch processing at any scale.|
||AWS Fargate|AWS Fargate is a serverless compute engine for containers. Fargate makes it easy for you to focus on building your applications.|

## Instance Pricing Model
|Instance type|pricing|
|-------------|-------|
|On-Demand|Billing by hour or second is applicable to users who do not need any upfront payment or long-term commitment.- For applications with Applications with short-term, spiky, or unpredictable workloads that cannot be interrupted.-For applications being developed or tested on Amazon EC2 for the first time.|
|Reserved Instance| - Up to 72% off the On-Demand price.- Customers that can commit to using EC2 over a 1- or 3-year term to reduce their total computing costs- For applications with steady state usage.- For applications that may require reserved capacity|
|Dedicated Host|Physical EC2 server dedicated for your use, up to 70% off the On-Demand price.-For customers who need to use existing server-bound software licenses, including Windows Server, SQL Server, SUSE Server etc.- or customers who need to meet compliance requirements.- With On-Demand instances, you pay for compute capacity by the hour or the second depending on which instances you run. No longer-term commitments |
|Spot instance|Up to 90% off the On-Demand price.- For applications that have flexible start and end times.- For applications that are stateless or fault-tolerant.|


## Resgitry
|Category             |Services                    |Description                                                   |
|---------------------|----------------------------|--------------------------------------------------------------|
|Container|Elastic Container Registry|Amazon Elastic Container Registry (Amazon ECR) is an AWS managed container image registry service that is secure, scalable, and reliable. Amazon ECR supports private repositories with resource-based permissions using AWS IAM. This is so that specified users or Amazon EC2 instances can access your container repositories and images. |
# Pricing for ECR
With Amazon ECR, you only pay for the amount of data you store in your repositories and for the data transfer from your image pushes and pulls. 

## Orchestration
|Category             |Services                    |Description                                                   |
|---------------------|----------------------------|--------------------------------------------------------------|
|Containers|Awazon Elastic Container Service | Amazon Elastic Container Service (Amazon ECS) is a fully managed container orchestration service that provides the most secure, reliable and scalable way to run containerized applications.|
||Amazon kubernet Service|Amazon Elastic Kubernetes Service (Amazon EKS) is a managed Kubernetes service that makes it easy for you to run Kubernetes on AWS and on-premises. Kubernetes is an open-source system for automating deployment, scaling, and management of containerized applications.|


3/27/2023

### Support plan

## Basic Support

The Basic Support plan is already available to all AWS customers by default and is free of charge. It also offers support for account and billing questions including requests for service limit increases.

Customer Service & Communities – You have 24×7 access to customer service, AWS documentation, whitepapers, and support forums.
AWS Trusted Advisor – This provides guidance on how to properly provision your AWS resources based on the best practices to further increase performance and improve the overall security of your cloud architecture. You are only provided access to the 7 core Trusted Advisor checks.
AWS Personal Health Dashboard – This is a personalized view of the health status of each AWS service that you currently have. It also provides an alert when your resources are impacted by an AWS-initiated activity.

||Developer|Business|Enterprise|
|-----|---------|--------|----------|
|uses case|Recommended if you are experimenting or testing in AWS|Recommended if you have production workloads in AWS|Recommended if you have business and/or mission critical workloads in AWS|
|AWS Trusted Advisor Best Practice Checks|Service quota and security checks|Full set of checks|
|Architectural Guidance|General|Contextual to your use-cases|Consultative review and guidance based on your applications|
|Technical Account Management |X|X|Designated Technical Account Manager (TAM) to proactively monitor your environment and assist with optimization.|
|Training |X|X|Access to online self-paced labs|
|Account Assistance |X|X|Concierge Support Team|
|Enhanced Technical Suppor|Business hours’ ‘ email access to Cloud Support Associates,Unlimited cases / 1 primary contact Prioritized responses on AWS re:Post|24×7 phone, email, and chat access to Cloud Support Engineers Unlimited cases / unlimited contacts (IAM supported) Prioritized responses on AWS re:Post|





# Hakans Notes

  |       Topic      |  Name  |
  |------------------|--------|
  |Security Lifecycle| Mustafa|
  |    Antivirus     |  Hakan |
  |       IDS        |  Goce  |
  |    Guard Duty    |Santhiya|

What is the definition of AntiVirus ??
Antivirus software, also known as anti-malware, is a computer program used to prevent, detect, and remove malware. Antivirus software was originally developed to detect and remove computer viruses, hence the name.
