# IAM Policies

- Policy Structure
  - Users can have multiple policies assigned to them
- IAM Policy Structure
  - `Version`
    - Policy language version
    - Always include "2012-10-17"
  - `Id`
    - Idetifier for the policy
      - Optional
  - `Statement`
    - `Sid`
      - Identifier for the statement
        - Optional
    - `Effect`
      - Whether the statement allows or denys access
        - Allow or Deny
    - `Principal`
      - Account/user role policy applies to
    - `Action`
      - List of actions the policy allows or denys
    - `Resource`
      - List of resources the action applies to
    - `Condition`
      - Conditions when this polcy is in effect
        - Optional

![alt text](images/policy-example.png)
