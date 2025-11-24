# Elastic Load Balancer

- What is load balancing
  - Spread load across multiple downstream instances
  - Expose a single point of access to your application (DNS)
  - Handle failures of downstream instances
  - Regular health checks of instances
  - Provide HTTPs(SSL temination) for websites
  - Enfore stickiness with cookies
  - High availability across zones
  - Seperate public traffic from private traffic

- Elastic Load Balancer
  - AWS Managed load balancer
  - AWS guarantees it will be working
  - AWS manages upgrades, maintainance, and high availability
  - Only a few configuration options
  - Costs less to setup your own load balancer, but will be more effort
  - Integrates into several AWS products
    - EC2
    - EC2 Scaling Groups
    - ECS
    - AWS Certificate Manager (ACM)
    - CloudWatch
    - Route 53
    - AWS WAF
    - AWS Global Accelerator
  
  - Health Checks
    - Crucial part of load balancers
    - Enables load balancers to know if the instances they forward traffic to are available
    - Health check is done on a port and a route
    - If response is not 200 (OK), instance is unhealthy

- Types of AWS load balancers
  - Classic Load Balancer
    - Depricated
  - Application Load Balancer
    - HTTP
    - HTTPS
    - WebSockets
  - Network Load Balancer
    - TCP
    - TLS (Secure TCP)
    - UDP
  - Gateway Load Balancer
    - Operates at Layer 3 (network layer)
  - Some load balancers can be setup as internal (private) or external (public)