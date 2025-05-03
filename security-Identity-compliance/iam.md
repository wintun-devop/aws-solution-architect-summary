### AWS IAM Officail Documentation
```
https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html
```
### AWS Security Whitepaper
```
https://docs.aws.amazon.com/whitepapers/latest/introduction-aws-security/identity-and-access-control.html
```
### Identities
- Root User
- IAM User
- IAM Role
- Identity Fedration
- Temporay Credential
   - sts
   - IAM Role Anywhere (https://docs.aws.amazon.com/rolesanywhere/latest/userguide/introduction.html)
- IAM Tag Resources


### Monitoring and Logging
- IAM Access Analyzer
  - External Access Analysis
    - Identifies resources in your AWS account or organization that are shared with external entities.
    - Generates findings when a resource-based policy grants access to a principal outside your zone of trust.
    - helps us to detect unintended access and potential security risks.
  - Unused Access Analysis
    - Focuses on identifying IAM roles, user credentials, and permissions that have not been used within a specified time frame.
    - Helps us clean up unnecessary access, reducing security risks and improving compliance.

### IAM Cross Account Access 
```
https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies-cross-account-resource-access.html
```

### IAM Policy Sample
- Administrator Access
```
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Action": "*",
            "Resource": "*"
        }
    ]
}
```
- IAM Full Access
```
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Action": [
                "iam:*",
                "organizations:DescribeAccount",
                "organizations:DescribeOrganization",
                "organizations:DescribeOrganizationalUnit",
                "organizations:DescribePolicy",
                "organizations:ListChildren",
                "organizations:ListParents",
                "organizations:ListPoliciesForTarget",
                "organizations:ListRoots",
                "organizations:ListPolicies",
                "organizations:ListTargetsForPolicy"
            ],
            "Resource": "*"
        }
    ]
}
```