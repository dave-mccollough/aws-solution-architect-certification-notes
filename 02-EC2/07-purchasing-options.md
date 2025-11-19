# EC2 Purchasing Options 

- On-Demand Instances
  - Recommended for short term uninterrupted workloads
  - Pay for what you use
    - Linux/Windows
      - Pay by second after the first minute
    - All other operating systems 
      - Bill by the hour
  - Highest cost with no upfront payment
  - No long term commitment
  
- Reserved (1 and 3 years)
  - Recommended for steady state useage applications (database)
  - Up to 72% discount compared to on-demand
  - You can reserve specific instance attributes including Type, Region, OS, etc
  - Reservation period
    - 1 year: 1x discount
    - 3 year: 3x discount
  - Payment options
    - No upfront
    - Partial upfront
    - All upfront
  - Resevered instances can be region scoped
  - You can buy and sell reserved instances in the Reserved Instance Marketplace
  - Convertible Reserved Instance
    - Can change instance type, family, OS, etc

- Savings Plan
  - Get discount back on long term usage
  - Commit to a certain type of usage
  - Usage beyond savings plan is billed at on-demand price
  - Locked to a specific instance family and region
  - Flexible across
    - Instance size
    - OS - Windows and Linux

- Spot Instances
  - Can be discounted up to 90% compared to on-demand
  - Can lose instance if your max price is less than current spot price
  - Most efficient AWS instances
  - Useful for
    - Batch jobs
    - Data analysis
    - Image processing
    - Distributed workloads
    - Workloads with flexible start and end times
  - Do not use for critical jobs or applications

- Dedicated Hosts
  - Physical server with EC2 instance capacity fully dedicated to your use
  - Use for compliance requirements or to leverage existing software licenses
  - Purchasing options
    - On demand
    - Reserverd (1 or 3 years)
  - Most expensive option

- EC2 Capacity Reservations
  - Recommened for short-term uninterrupted workloads that need to be in a specific AZ
  - Reserve on-demand instance capacity in a specific AZ for any duration
  - Always have hacces to EC2 capacity when you need it
  - No time commitment
  - Charged on demand rate whether you run instances or not