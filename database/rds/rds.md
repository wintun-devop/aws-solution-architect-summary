### RDS Official Documentations
```
https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html
```
### RDS Backup
- Snapshots
   - These are full backups of your RDS instance, including all databases, configurations, and settings. They allow you to 
     restore an entire database instance to a previous state. Snapshots are stored within AWS and can be used to create new RDS 
     instances.
- Exports in Amazon S3
   - This extracts data from a snapshot and stores it in an Amazon S3 bucket in Apache Parquet format. Unlike snapshots,
     exported data cannot be directly restored to an RDS instance. Instead, it is optimized for analysis using tools like
     Amazon Athena or Redshift Spectrum.

### Monitoring 
```
https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_Monitor_Logs_Events.html
```
