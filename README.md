## AWS-3tier-Architecture-Terraform

The code does the following:
1. Creates a VPC with the CIDR block provided in the region you want.
2. Creates subnets for each layer.
3. Creates an IGW and NAT gateway.
4. Creates Route tables.
5. Creates a RDS instance.
6. Configures security group for Web layer.
7. EC2 instances for webservers.
8. Application load balancer.

Command to be used:
1. terraform init
2. terraform apply

### Note: 
When running the "main.tf" file you might get an error saying that the subnet_group does not exist. In this case just run it again using " terraform apply" and you will be able to get the output.







