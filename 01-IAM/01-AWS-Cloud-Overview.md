# AWS Cloud Overview

- Global Infrastructure

  - [Link](https://aws.amazon.com/about-aws/global-infrastructure/regions_az/)
  - AWS Regions
  - AWS Availability Zones (AZ)
  - AWS Data Center
  - AWS Edge Locations
    - Points of presence

- Regions
  - Regions all over the world
  - Cluster of data centers
  - Most AWS Services are region scoped
  - How to choose an AWS region
    - Compliance and/or legal requirements
      - Data sovereignty
    - Latency
      - Proximity to customers
    - Available services
    - Pricing
      - Pricing can vary from region to region
- Availability Zones (AZ)

  - Each region has multiple availability zones
    - 3-6 AZs per region
  - Each AZ is one or more discrete data center with redundant power, networking, and connectivitiy
  - Isolated from each other in the event of a disaster
  - Connected with high bandwidth/low latency networking

- Points of Presence (Edge locations)

  - 400+ points of presnce
    - 400+ edge locations
    - 10+ Regional caches
  - Content is delivered to users with lower latency

- Global Services

  - Idenity and Access Management (IAM)
  - Route 53 (DNS)
  - CloudFront (Content Delivery)
  - WAF (Web Application Firewall)

- Region scoped services include
  - Amazon EC2 (IaaS)
  - Elastic Beanstalk (PaaS)
  - Lambda (Function as a Service)
