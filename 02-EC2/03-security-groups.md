# Security Groups

- Fundamental for network security in AWS
- Control how traffic is allowed in or out of an EC2 instance
- Security groups contain only **Allow** rules
- Security group rules can be reference by name or IP address
- Act as a 'Firewall' for EC2 instances
- Regulate:
  - Access to ports
  - Authorized IP ranges
  - Control of inbound network to instance
  - Control of outbound network from instance
- Can be attached to multiple instances
- Locked down to a region/VPC combination
- 'Lives' outside of EC2
  - If traffic is blocked, EC2 won't see it
- If application times out or is not accessible, security group issues
- If application gives a connection refused error, application error
- All inbound traffic is blocked by default
- All outbound traffic is allowed by default

- Best practice
  - Maintain one seperate security group for SSH access

- Ports to know
  - 21: FTP
  - 22: SSH 
  - 80: HTTP
  - 443: HTTPS
  - 3389: RDP