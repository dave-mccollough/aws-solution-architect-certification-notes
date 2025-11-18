# EC2 Basics

- Elastic Cloud Compute - Infrastructure as a Service (IaaS)
- Consists of:
  - EC2: Virtual Machine 
  - EBS: Elastic Block Service - Virtual Drive
  - EFS: Elastic File Service - File storage
  - ELB: Elastic Load Balance - Distribute load across machines
  - ASG: Auto-Scaling Group - Scaling based on load

- Sizing and configurations options
- Operating Systems
  - Linux
  - MacOS
  - Windows
- CPU and core options
- RAM options
- Storage space
  - Network attached
    - EBS/EFS
  - Hardware
    - EC2 Instance Store
  - Network Card
    - Public IP Address
  - Firewall rules
    - Security Group
  - Bootstrap script
    - Configure at first launch
    - EC2 user data

- EC2 User Data
  - Bootstrap instances using an EC2 user data script
    - Bootstrapping means launching commands when a machine starts
  - Script only only runs once at the instance start
  - EC2 Suser data is used to automate boot tasks
    - Installing updates
    - Installing software
    - Downloading files
  - Runs with the root user