# High Availability and Scalability

- Vertical Scalability
  - Increasing the size of the instance your applications runs on
    - t2.micro scales to t2.large
  - Common for non-distributed systems like a database
  - RDS. ElastiCache are services that can scale vertically
  - There is typically a hardware limit on how much you can scale vertically

- Horizontal Scalability
  - Increasing the number of instances your application runs on
  - Typically implies distributed systems
  - Common pattern for modern applications

- High Availability
  - Goes hand in hand with horizontal scaling
  - Running your application in at least 2 data centers/availability zones
  - Passive
    - RDS Multi AZ
  - Active
    - Horizontal scaling

- High availability and scalability in EC2
  - Vertical scaling
    - Increase instance size
  - Horizontal scaling
    - Add more instances
      - Autoscaling group
      - Load balancer
  - High Availability   
    - Run instances for the same applications across multiple AZx
      - Autoscaling group multi az
      - Load Balancer multi az