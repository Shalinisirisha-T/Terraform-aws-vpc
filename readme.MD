terraform-aws-vpc

This module creates following resources

1. VPC -> CIDR
2. IGW with VPC association
3. Subnets -> public private database
4. Route tables -> Publlic private database
5. Associtaions and Routes
6. EIP
7. NAT gateway -> to provide egress internet access to the resources in private subnets
8. Route tables entries through peering

## Inputs
project - (Required) string type . user should pass the project name
environment - (Required) string type . user should pass the environment, values should be one of dev, uat, qa and prod
## Outputs