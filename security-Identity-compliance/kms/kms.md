### AWS Key Management Service
```
https://aws.amazon.com/kms/getting-started/
```
```
https://docs.aws.amazon.com/kms/
```
```
https://docs.aws.amazon.com/kms/latest/developerguide/overview.html
```
- AWS Key Management Service (AWS KMS) is a managed encryption service that enables you to create and control cryptographic keys for securing 
  your data across AWS services and applications.
  - Create a Key: You can create and manage Customer Managed Keys (CMKs) using the AWS Console, AWS CLI, or SDKs.
  - Encrypt and Decrypt Data: Use KMS to encrypt sensitive data, ensuring secure storage and transmission.
  - Integrate with AWS Services: AWS KMS works seamlessly with services like S3, RDS, Lambda, and Secrets Manager to provide automatic encryption.
  - Manage Key Policies: Set granular permissions for key usage using AWS Identity and Access Management (IAM).
  - Audit and Monitor: AWS CloudTrail logs all key-related actions for security and compliance tracking.
 
### KMS Reference
```
https://www.genesesolution.com/aws-key-management-service-kms-secure-encryption-compliance/
```
### KMS vs Secret Manager
```
https://www.cbtnuggets.com/blog/technology/networking/aws-kms-vs-secrets-manager
```


### Cloud HSM vs KMS
- AWS CloudHSM: A dedicated hardware security module (HSM) that provides full control over cryptographic keys. It is single-tenant, meaning 
  you have exclusive access to the hardware. CloudHSM is ideal for organizations needing strict compliance (e.g., FIPS 140-2 Level 3) and custom cryptographic operations.
- AWS KMS: A multi-tenant managed service that simplifies key management. AWS controls the underlying infrastructure, but users manage their 
  encryption keys. KMS integrates seamlessly with most AWS services and supports automatic key rotation, making it more convenient for general 
  encryption needs.


- CloudHSM
  - Tenancy : Single-tenant
  - Key Control:	Full control
  - Compliance : FIPS 140-2 Level 3
  - Integration	: Limited AWS service integration
  - Scalability	: Manual scaling
  - Pricing	: Higher cost
  
- KMS
  - Tenancy : Multi-tenant
  - Key Control : AWS-managed infrastructure
  - Compliance	: FIPS 140-2 Level 2 (recently upgraded to Level 3)
  - Integration :	Broad AWS service integration
  - Scalability	: Automatic scaling
  - Pricing	:Lower cost

AWS CloudHSM Use Cases
- Regulatory Compliance – Organizations needing strict compliance with FIPS 140-2 Level 3, PCI DSS, or HIPAA often use CloudHSM for
  secure key management.
- Custom Cryptographic Operations – If you need custom encryption algorithms, digital signatures, or public key infrastructure (PKI), CloudHSM 
  provides full control over cryptographic keys.
- Dedicated Hardware Security – CloudHSM is single-tenant, meaning you get exclusive access to the hardware, making it ideal for 
  high-security environments.
- Secure Key Storage & Export – Unlike KMS, CloudHSM allows key export, which is useful for on-premises integration or 
  multi-cloud environments.
- Database Encryption – CloudHSM integrates with Oracle RDS and Amazon Redshift, making it suitable for securing 
  sensitive database transactions.

AWS KMS Use Cases
- General Encryption Needs – KMS is ideal for encrypting data at rest in AWS services like S3, EBS, RDS, and DynamoDB.
- Automatic Key Rotation – KMS simplifies key management with automatic key rotation, reducing operational overhead.
- Seamless AWS Integration – KMS integrates with AWS services like Lambda, CloudTrail, and Secrets Manager, making it easy to implement     
  encryption across applications.
- Multi-Region Key Replication – KMS supports multi-region keys, ensuring high availability and disaster recovery.
- Access Control & Auditing – KMS provides IAM-based access control and CloudTrail logging, making it easier to track key usage.
### Choosing Between CloudHSM and KMS
- If you need full control, compliance, and custom cryptographic operations, go with CloudHSM.
- If you want ease of use, AWS service integration, and automatic key management, KMS is the better choice.