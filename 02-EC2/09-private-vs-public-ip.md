# Private vs Public IP (IPv4)

- Public IP
  - Public IP means the machine can be identified in the internet
  - Must be unique across the whole internet
  - Can be geo-located

- Private IP
  - Machine can only be identified on a private network only
  - Machine IP must be unique across the private network
  - 2 different private networks can have the same IPs

- Elastic IP
  - Fixed public IP you can associate to an EC2 instance
  - You can only have 5 Elastic IPs per account
  - Avoid using Elastic IPs
    - Use random public IP and register a DNS name to it
    - Use a load balancer 

- EC2 Instances
  - Private IP for internal AWS network
  - Public IP for internet
  - Public IP can change if instance is stopped/started



