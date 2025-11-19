# Elastic Network Interfaces

- Logical component in a Virtual Private Cloud (VPC) that represents a virtual network card
- Can have the following attributes
  - Primary private IPv4
  - One or more secondary IPv4
  - One elastic IP per private IP
  - One Public IP
  - One or more security groups
  - MAC address
- ENIs are independent and you can move them to different EC2 instances
- Bound to a specific AZ
- Does not cost any $$
- [AWS Blog](https://aws.amazon.com/blogs/aws/new-elastic-network-interfaces-in-the-virtual-private-cloud/)