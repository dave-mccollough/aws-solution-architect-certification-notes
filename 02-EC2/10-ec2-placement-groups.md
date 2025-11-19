# EC2 Placement Groups

- Allows for control of EC2 placement strategy
- Placement group strategies
  - Cluster
    - Clusters instances into a low latency group in a single AZ
    - Provides fast/enhanced networking
    - If AZ fails - all AZ fails
  - Spread
    - Spreads instances across underlying hardwware
    - Spans AZs
    - EC2 instances are on different hardware
    - Limited to 7 instances for AZ per placement group
  - Partition
    - Spreads instances across many different partions within an AZ
    - Can span multiple AZs in the same region
    - Up to 100s of EC2 instances
    - Instances in a partition do not share racks with the instances in another partition
      - Failures won't impact all partitions