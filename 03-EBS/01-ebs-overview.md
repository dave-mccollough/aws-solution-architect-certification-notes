# EBS Overview

- EBS Volume
  - EBS - Elastic Block Store
  - EBS Volume is a network drive you can attach to an instance when it is running
    - Can be moved from one EC2 instance to another
  - Allows instances to persist data even after termination
  - Only be mounted to one instance at a time
  - Bound to a specific AZ
    - To move volume, it needs to be snapshoted
  - You are billed for the provisioned capacity
  - You can increase the drives capacity over time

- Delete on termination
  - Controls EBS behavior when EC2 instance is terminated
  - Controlled via the console or CLI
  - 