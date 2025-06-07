### AWS Data Migration Service Official Docs
```
https://docs.aws.amazon.com/dms/
```
```
https://docs.aws.amazon.com/dms/latest/userguide/Welcome.html
```
### AWS Database Services
```
https://docs.aws.amazon.com/decision-guides/latest/databases-on-aws-how-to-choose/databases-on-aws-how-to-choose.html
```
DMS
 - Cloud-based tool designed to help migrate databases to AWS quickly and securely while minimizing downtime.
 - Supports both homogeneous migrations (e.g., Oracle to Oracle) and heterogeneous migrations (e.g., SQL Server to PostgreSQL).
 - Key Features
   - Minimal Downtime: Uses Change Data Capture (CDC) to keep the source database operational during migration.
   - Supports Multiple Databases: Works with Oracle, SQL Server, MySQL, PostgreSQL, MongoDB, and more.
   - Continuous Replication: Can replicate ongoing changes to keep databases synchronized.
   - Schema Conversion: Works with AWS Schema Conversion Tool (SCT) for complex migrations.
   - Scalability & Reliability: Supports multi-AZ deployments for high availability.
 - Use Cases
   - Migrating on-premises databases to AWS-managed services like Amazon RDS or Amazon Aurora.
   - Replicating data for analytics in Amazon Redshift or Amazon S3.
   - Modernizing legacy databases by moving to cloud-native solutions.