# AWS-Three-Tier-Architecture

Create VPC in AWS 
Create Subnet - 2 Public and 2 Private 
Create Internet Gateway (IGW)
Create Route Table 
Create NAT Gateway 
Create Launch Template 
Create AutoScaling Group (ASG) - one instance in Public and one instance in Private
Create RDS Database 
Connect to EC2 Machine 
1. To pubic normally with ssh -i keypair DNS hostname
2. To Connect to Private , first copy the public keypair content and save it in a file.
3. then from public instance ....connect to Private instance using public keypair file.
Connect to Database  
