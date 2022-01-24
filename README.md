# This terrform code is for creating three tier application in AWS. Refer to high level architecture diagram "Three_Tier_Architecture.png" at the root level of terraform repository.
# All terraform and bash scripts are placed inside directory "three-tier-app"

This terraform script will create below components:
1) VPC
2) EC2 Instance
3) RDS Instance
4) Internet Gateway
5) Public and Private Subnets
6) Security Groups
7) Load Balancer
8) Route Table and Subnet Association

Future Improvements
1) NAT Gateway or Bastion host for additional security and Patching instances in private subnet
2) Custom NACL's for each subnet
