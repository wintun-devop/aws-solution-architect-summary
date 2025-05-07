### AWS EBS Official
```
https://aws.amazon.com/ebs/
```
```
https://docs.aws.amazon.com/ebs/latest/userguide/what-is-ebs.html
```

### AWS Official Blog
```
https://aws.amazon.com/blogs/storage/automating-amazon-ebs-snapshot-and-ami-management-using-amazon-dlm
```

- EBS
  - az specific,can attach any instance in the same az.
  - EBS Classes
    - General Purpose SSD
    - Provisioned IOPS SSD
    - Throughput Optimized HDD
    - Cold HDD
  - Volume Types
    - https://aws.amazon.com/ebs/features/?pg=ln&sec=be#topic-3
  -Backup 
    - Snapshot
        - Backups can be created using snapshots, which are stored in Amazon S3
    - Data Life Cycle Manager
        - https://docs.aws.amazon.com/ebs/latest/userguide/snapshot-lifecycle.html
  - High Availability
    - EBS Multi-Attach
        - Replicates data within an Availability Zone to prevent failures.
        - https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-volumes-multi.html
  - Encryption
     - Offers built-in encryption for data security.(optional)