# EBS Multi-attach

- Attach same EBS volume to multiple EC2 instances in the same AZ
- Each instance has full read and write permissions to the high performace volume
- Use Case
  - Achieve higher application availablity in clustered linux applications
  - Applicatios must manage conncurrent write operations
  - 