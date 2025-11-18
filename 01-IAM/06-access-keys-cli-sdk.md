# AWS Access Keys, CLI and SDK

- Accessing AWS
  - Management Console - Password and MFA
  - CLI - Access keys
  - SDK - Access keys/Code
- Access keys are granted through the AWS console
- Users manage their own access keys
  - Similar to passwords.. don't share them
- Access Key ID ~= username
- Secret Access Key ~= password

- AWS CLI
  - Interact with AWS services using command line
  - Direct access to AWS services public APIs
  - Create scripts to manage resources
  - [Open source](https://github.com/aws/aws-cli)
  - [Mac Install](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
    - Or use brew: `brew install awscli`
  - [Windows Install](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

- AWS SDK
  - AWS software development kit (SDK)
  - Language specific APIs
  - Allows you to access and manage AWS services programatically
  -  Support most major languages

- You can use Cloud Shell in the AWS Console to accessl the CLI
![alt text](images/cloud-shell.png)