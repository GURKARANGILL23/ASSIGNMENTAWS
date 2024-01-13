# EC2 Instances Setup

This repository contains information on the setup of development and production EC2 instances.

## Development Instance

### Instance Details
- AMI: Amazon Linux 2
- Instance Type: t2.micro
- Security Groups:
  - SSH (Port 22) from your IP address
  - Additional groups as needed for your application

### Configuration
1. Launch an EC2 instance using the specified AMI and instance type.
2. Configure security groups to allow SSH access only from your IP.
3. Connect to the instance using your key pair.


## Production Instance

### Instance Details
- AMI:Amazon Linux 2
- Instance Type:t2.small (adjust as needed)
- Security Groups:
  - SSH (Port 22) from a limited set of IPs
  - Additional groups for production services

### Configuration
1. Launch an EC2 instance using the specified AMI and instance type.
2. Configure security groups for production-level access controls.
3. Set up any necessary production configurations.






