1. Project Overview: 	Terraform configuration for creating AWS VPC and EC2 instances.
2. Prerequisites: 		Terraform installed locally.
						AWS account with necessary permissions.
3. Setup:				Clone the repository.
						Navigate to the project directory.
						Initialize Terraform.
4. Usage:				Apply the configuration to provision resources.
						Destroy resources when done.
5. Resources Created:	VPC with specified CIDR block.
						Public and private subnets.
						Internet Gateway for public subnet.
						Route tables for subnets.
						Security group allowing inbound SSH and outbound traffic.
						Two EC2 instances in respective subnets.
6. Variables:			region, instance_type, key_name, and ami.
7. Customization:		Modify variables in terraform.tfvars for customization.
8. Author:				Ramanan Loganathan (ramanan97104@gmail.com).
