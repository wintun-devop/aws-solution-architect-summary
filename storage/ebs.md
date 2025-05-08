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
### EBS Medium Reference
```
https://medium.com/@mudasirhaji/step-by-step-process-of-how-to-add-and-mount-ebs-volume-on-ubuntu-ec2-linux-instance-a4be8870a4dd
```

- EBS
  - az specific,can attach any instance in the same az.
  - EBS Classes
    - General Purpose SSD (https://docs.aws.amazon.com/ebs/latest/userguide/general-purpose.html)
        - Balance price and performance for a wide variety of transactional workloads.
        - Virtual desktops, medium-sized single instance databases, latency sensitive interactive applications, development and test
          environments, and boot volume.
        -Limitation
          - gp3 volume can range in size from 1 GiB to 16 TiB.
          - gp2 volume can range in size from 1 GiB to 16 TiB. Keep in mind that volume performance scales linearly with the volume size.
    - Provisioned IOPS SSD (https://docs.aws.amazon.com/ebs/latest/userguide/provisioned-iops.html)
       - Provisioned IOPS SSD (io2) Block Express volumes
          - Built on the next generation of Amazon EBS storage server architecture
          - Block Express is ideal for running performance-intensive, mission-critical workloads, such as Oracle, SAP HANA, Microsoft SQL Server,
            and SAS Analytics.
          - Block Express volumes are suited for workloads that benefit from a single volume that provides sub-millisecond latency, supports
            higher IOPS and throughput, and larger capacity than gp3 volumes.
          - Sub-millisecond average latency
          - As of April 30, 2025, all new and previously created io2 volumes are io2 Block Express volumes.
          - Limitations
             - Nitro-based instances support volumes provisioned with up to 256,000 IOPS.
             - Other instancetypes can be attached to volumes provisioned with up to 64,000 IOPS, but can achieve up to 32,000 IOPS.
             - Storage capacity up to 64 TiB (65,536 GiB).
       - Provisioned IOPS SSD (io1) volumes 
          - io1 volumes are available for all Amazon EC2 instance types.
          - Maximum ratio of provisioned IOPS to requested volume size (in GiB) is 50:1.100 GiB io1 volume can be provisioned
             with up to 5,000 IOPS.
          - Limitations
            - Can range in size from 4 GiB to 16 TiB.
            - Can provision from 100 IOPS up to 64,000 IOPS per volume.
    - Throughput Optimized HDD(https://docs.aws.amazon.com/ebs/latest/userguide/hdd-vols.html)
      - low-cost HDD designed for frequently accessed, throughput-intensive workloads.
      - Throughput Optimized HDD (st1) volumes provide low-cost magnetic storage that defines performance in terms of throughput rather than IOPS.
      -  Good fit for large, sequential workloads such as Amazon EMR, ETL, data warehouses, and log processing.
      -  Bootable st1 volumes are not supported.
    - Cold HDD
      - Bootable not supported.
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
