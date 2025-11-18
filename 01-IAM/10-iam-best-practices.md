# IAM Best Practices

- Reserve the root account for initial setup only—never for daily operations.
- Manage access through groups; map permissions to groups, not individual users.
- Enforce a strong, standardized password policy across the environment.
- Require MFA for all users.
- Use IAM roles to grant services the permissions they need - avoid hardcoding credentials.
- Use access keys strictly for programmatic access (CLI/SDK), and rotate them regularly.
- Continuously audit privileges using IAM Credential Reports and Access Advisor.
- Never share IAM users or access keys.