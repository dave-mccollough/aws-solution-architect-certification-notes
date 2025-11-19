# EC2 Hibernate

- In-memory state is preserved
- Instance boot is much faster
  - OS is not stopped/restarted
- RAM state is written to a file in the root EBS volume
- Root EBS volume must be encrypted
- Instance cannot be hibernated for more than 60 days
- not supported on all instance types
- 