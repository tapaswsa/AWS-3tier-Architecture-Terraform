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
2. terraform plan
3. terraform apply








