# VPC Hands-on Lab - AWS Skill Builder

## Lab Name
Introduction to Amazon Virtual Private Cloud (VPC)

## Objectives
- Create a VPC with custom CIDR ranges
- Understand public vs private subnet behavior
- Configure route tables
- Validate traffic flow using gateways

## What I Built
- Custom VPC using CIDR 10.0.0.0/16
- Public and private subnets
- Internet Gateway attachment
- NAT Gateway for private subnet outbound access
- Route table associations

## Key Learnings
- Route tables determine whether a subnet is public or private
- NAT Gateway must reside in a public subnet
- Private resources can reach the internet without being publicly exposed
- Multi-AZ designs improve resilience

## Production Considerations
- Deploy NAT Gateway per Availability Zone for HA
- Use VPC Endpoints to reduce NAT cost
- Separate tiers using Security Groups
- Enable flow logs for monitoring

## Next Steps
- Build the same architecture manually in AWS Console
- Add Application Load Balancer
- Deploy EC2 instances for testing
