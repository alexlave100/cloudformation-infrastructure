# CloudFormation-Infrastructure

Building a highly available and elastic cloud architecture using CloudFormation.

## What is created:
	• A Custom VPC
	• Two public subnets
	• Two private subnets
	• An Internet Gateway
	• A Route Table
	• Resources for custom routing and route table associations with the subnets in the VPC
	• A nested compute stack for the compute resources in the infrastructure






The resources are laid out in a tree structure to simulate the nested hierarchy of the stacks. At the root of the project
you have the root stack "cfn-infra.json" containing the backbone infrastructure. In every subsequent folder is a child stack template for the resource creation of specific categories in the AWS service catalog.



To be continued...
