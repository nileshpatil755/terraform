# This terrform code is for creating three tier application in AWS. Refer to high level architecture diagram "Three_Tier_Architecture.png" at the root level of terraform repository.
# All terraform and bash scripts are placed inside directory "three-tier-app"

This terraform script will create below components:
1) EC2 Instance
2) RDS Instance
3) Internet Gateway
4) Public and Private Subnets
5) Security Groups
6) Load Balancer
7) Route Table and Subnet Association

Future Improvements
1) NAT Gateway or Bastion host for additional security and Patching instances in private subnet
2) Custom NACL's for each subnet
