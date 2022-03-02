AWS Administrative services for DevOps:
=======================================

Basics to start with:
	1) What is cloud computing?
	2) Cloud service types
	3) On-premesis Vs Cloud Services
	4) Why AWS?

1) AWS IAM(Identity and Access Management)
	1) Users
	2) Groups
	3) Policy(custom and predefined)
	4) Roles

2) AWS Instances
	1) Regular EC2 Instances
	2) Spot Instances
	3) Reserved Instances
	4) Dedicated Instances
	5) Dedicated Host
	6) Launch Templates
	7) Scheduled Instances
	8) AMI(Amazon Machine Image)
	9) EC2 Image Build

3) VPC(Virtual Private Cloud)
	1) Basic Network principles like IP address, Subnet, CIDR, route, Firewalls etc.,
	2) VPC, subnet, routetable, subnet association
	3) Internet Gateway, NAT Gateway, NAT Instances
	4) Network ACLs, Security Groups
	5) VPC Peering connections
	6) Transit Gatway
	7) VPN(Client and site-to-site)
	8) VPC Endpoint
	9) Egress-only Internet gateway
	10) Elastic IPs

4) Storage
	1) Storage types like Block, Object and Filesystem Storages
	2) S3 Bucket
	3) EBS(Elastic Block Storage)
	4) EFS(Elastic FileSystem)

5) Databases
	1) Differences between Relational and Non-relational databases?
	2) RDS(Relational Database Service) --> Amazon Aurora, MySQL, MariaDB, PostgreSQL, Oracle and MicroSoft SQL Server

6) LoadBalancer
	1) What is LoadBalancer?
	2) OpenSource and AWS LoadBalancers
	3) Classic LoadBalancer
	4) Application LoadBalancer
	5) Network LoadBalancer
	6) Target Groups

7) Containers and Orchestration
	1) Containers basics
	2) ECS(Elastic Container Service)
	3) ECR(Elastic Container Registry)
	4) EKS(Elastic Kubernetes Service)

8) Monitoring and Events
	1) CloudWatch
	2) Amazon Prometheus
	3) Events

AWS DevOps Services:
====================
Basic understanding on DevOps Culture and OpenSource tools
	1) OpenSource tools for DevOps
	2) AWS DevOps services

1) Amazon CodeCommit
	1) Differences between CVCS(Centarlized Version Control System) and DVCS(Distributed Version Control System)
	2) Git Basics --> workflow, commits, logs, revert, rebase, branches, tags etc.,
	3) CodeCommit
	4) Pull Request
	5) Approval rule templates
	6) IAM users and Policy for CodeCommit

2) AWS CodeBuild
	1) CodeBuild advantages and usecases
	2) Benefits of CodeBuild --> Fully managed, On-demand and Out of the box
	3) How to create a Build Spec files? --> writing basic YAML files for CodeBuild to automate using events
	4) How to run CodeBuild?
	5) Sample projects for Custom Dockerfile build, Source code development etc.,
	6) VPC Endpoints
	7) Monitoring CodeBuild API using AWS CloudTrail
	8) Security using IAM users

3) AWS CodeDeploy
	1) What was the purpose of CodeDeploy and usecases?
	2) How to deploy developed code to On-premesis and Cloud Instances
	3) Application revisions
	4) Monitoring CodeDeployment using CloudWatch tools and CloudTrail

4) AWS CodePipeline
	1) what is CICD?
	2) OpenSource tools for CICD operations
	3) CodePipeline for CICD
	4) Understdnaing DevOps Pipeline for application development and deployment
	5) Monitoring Pipelines evenets and API logs using CloudTrail
	6) Manual and scheduled triggers of CodePipeline

5) AWS CodeArtifact
	1) What was Artifacts and usecases?
	2) Other tools for Artifacts
	3) Benefits of AWS Artifacts
	4) AWS Artifacts for package manager and Image storage etc.,
	5) Intigration with CodeBuild, CodeDeploy and CodePipeline

7) AWS X-Ray
	1) What X-Ray for Developers?
	2) X-Ray for Debugging, Tracing and Service map
	
Note:
1) We will be seeing and practising all from scratch.
2) Linux OS basics would be mandit for People.
3) Real-time scenarios will be replicated using AWS DevOps tools to compitate and clear the interviews and go-live.
