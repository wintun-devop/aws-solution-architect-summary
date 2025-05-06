Secret Manager
```
https://aws.amazon.com/secrets-manager/
```
```
https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html
```
### KMS vs Secret Manager
```
https://www.cbtnuggets.com/blog/technology/networking/aws-kms-vs-secrets-manager
```
- AWS Secrets Manager is a secure vault for storing and managing sensitive information like passwords, API keys, database credentials,
  and other secrets.
  - Automated Secret Rotation – Regularly updating and refreshing credentials without manual intervention.
  - Access Control – Managing permissions and restricting access using AWS Identity and Access Management (IAM).
  - Secure Retrieval – Applications can fetch secrets programmatically without exposing them in code.
  - Encryption & Compliance – Secrets are encrypted and meet security standards for protecting sensitive data.
  - Integration with AWS Services – Works seamlessly with AWS Lambda, RDS, Redshift, and other services.
- How to use Secret Manager?
   - AWS Secrets Manager is a service that helps you securely store, manage, and retrieve sensitive information such as database credentials,
     API keys, and other secrets.
   - Instead of hardcoding sensitive data in your applications, you can store them in Secrets Manager and retrieve them securely when needed.
   - Major Usage:
    - Create a Secret: You can store a secret using the AWS Management Console, AWS CLI, or SDKs. Define the secret as a key-value pair or JSON
      structure.
    - Access the Secret: Applications retrieve secrets using the AWS SDK, Secrets Manager API, or IAM roles to ensure secure access.
    - Automatic Rotation: AWS allows secrets to be automatically rotated at a defined interval to improve security.
    - Audit and Monitoring: You can use AWS CloudTrail and AWS Config to track access and changes to secrets.
