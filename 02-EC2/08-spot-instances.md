# EC2 Spot Instances

- Spot Instances
  - Discounted up to 90% compared to on-demand
  - Define max spot price and get instance while spot price is less than max price
    - Spot price varies based on offer and capacity
    - If spot price > max price, you can stop or terminate your instance within a 2 minute grace period

- Spot Fleets
  - Set of spot instances
  - Spot fleet will try and meet target capacity with price constraints
  - Allow us to automatically request spot instances with the lowest price